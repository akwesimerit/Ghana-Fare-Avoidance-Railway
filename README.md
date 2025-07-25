
# What Demographic and Attitudinal Factors Influence the Justification of Transportation Fare Evasion in Ghana?

**Implications for Traffic Congestion and Railway Modernization**

## 📘 Project Overview

This project investigates the demographic and attitudinal factors that influence whether people in Ghana consider transportation fare evasion justifiable. Using nationally representative data from the World Values Survey (Wave 6, Ghana 2011–2012), the study examines how personal characteristics and ethical attitudes relate to this behavior.

The analysis connects these findings to broader transport policy issues, specifically traffic congestion and the public’s potential support for railway modernization in Ghana.

## 🎯 Research Objective

To determine which categories of people in Ghana justify transportation fare evasion and understand the underlying demographic and attitudinal drivers. The study also explores how these justifications may shape or reflect issues such as urban congestion and investment in modern rail transport systems.

## 📊 Dataset

* **Source**: World Values Survey (WVS) Wave 6 – Ghana (2011–2012)
* **Format**: `.sav` file (SPSS), used in R with the `haven` package
* **Access**: [WVS Official Documentation](https://www.worldvaluessurvey.org/WVSDocumentationWV6.jsp)

## 🧩 Key Variables Used

**Dependent Variable**

* `fare_just` (V199): Justifiability of fare evasion (scale: 1 = never, 10 = always)

**Demographic Predictors**

* `age` (V242)
* `gender` (V240)
* `income` (V239)
* `education` (V248)
* `employment` (V229)
* `social_class` (V238)
* `town_size` (V253)

**Attitudinal and Ethical Predictors**

* `bribe` (V202): Justifiability of bribery
* `evade_tax` (V201): Justifiability of tax evasion
* `stealing` (V200): Justifiability of stealing

**Institutional Trust Predictors**

* `trust_police` (V113)
* `trust_court` (V114)
* `trust_gov` (V115)
* `trust_parties` (V116)
* `trust_parl` (V117)

**Other Control Variable**

* `life_satisfaction` (V23): Satisfaction with life (proxy for financial or emotional pressure)

## 🔬 Methodology

1. **Exploratory Data Analysis (EDA)** to understand trends and distributions
2. **Logistic regression modeling** to identify significant predictors of fare evasion justification
3. **Interpretation** of findings in the context of public transport behavior, congestion challenges, and potential railway policy solutions

## 🌍 Policy Relevance

Understanding who justifies fare evasion and why can help policymakers:

* Identify vulnerable groups facing economic pressure
* Address gaps in institutional trust and transport service delivery
* Promote support for modern, fair, and sustainable transport systems, including rail modernization

## ✍️ Author

This is a personal project by **Emmanuel**, built on open data and hosted for transparency, learning, and policy engagement. It extends a previous mini-project on public willingness to pay for transport, focusing now on rule-breaking behavior and its transport implications.

