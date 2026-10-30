# First-Order Reaction Kinetics | Chemical Engineering Portfolio Project

## Overview

This project investigates first-order chemical reaction kinetics through concentration data analysis, logarithmic transformation, linear regression, and mathematical modeling.

Using a simulated concentration-versus-time dataset, I developed an exponential decay model to estimate reactant concentrations and evaluate how closely the model represents the data.

The project demonstrates the application of chemical engineering principles and quantitative analysis using spreadsheet-based computational tools.

## Project Objectives

- Analyze reactant concentration changes over time.
- Apply logarithmic transformations to linearize first-order kinetics.
- Determine the reaction-rate constant using linear regression.
- Develop a predictive mathematical model.
- Compare simulated concentration data with model predictions.
- Evaluate model fit and discuss limitations.

## Methodology

### 1. Data Analysis

A simulated dataset containing 11 concentration measurements between 0 and 20 minutes was analyzed using Google Sheets.

### 2. First-Order Rate Law

The integrated first-order rate equation is:

**C(t) = C₀e^(-kt)**

Where:
- C(t) = Reactant concentration at time t
- C₀ = Initial reactant concentration
- k = First-order reaction-rate constant
- t = Time

### 3. Logarithmic Transformation

Taking the natural logarithm produces:

**ln(C) = ln(C₀) − kt**

This allows linear regression to be applied to the transformed concentration data.

### 4. Regression Analysis

The fitted linear equation was:

**ln(C) = −0.09888t − 0.0044**

The reaction-rate constant was determined from the negative slope of the regression line.

## Key Results

| Parameter | Result |
|---|---|
| Reaction-rate constant | 0.09888 min⁻¹ |
| Coefficient of determination (R²) | 0.99967 |
| Fitted initial concentration | 0.9956 mol/L |
| Analysis period | 0–20 minutes |
| Dataset | Simulated concentration measurements |

### Predictive Model

**C(t) = 0.9956e^(-0.09888t)**

The high R² value indicates that the logarithmically transformed data closely follow the fitted linear relationship.

## Visualizations

### Concentration vs. Time

Comparison of simulated concentration data with predicted concentrations.

[View Concentration Graph](Concentration%20%28mol_L%29%20vs.%20Time%20%28min%29.pdf)

### Linearized First-Order Kinetics

Logarithmic transformation of concentration data with a fitted linear regression model.

[View Linear Regression Graph](ln%28Concentration%29%20vs.%20Time.pdf)

## Project Files

- [Technical Report](First_Order_Reaction_Kinetics_Engineering_Report%20.pdf) — Complete methodology, results, discussion, and conclusions.
- [Excel Spreadsheet](Chemical%20Engineering%20Project.xlsx) — Concentration data, regression analysis, and calculations.
- [Graphs PDF](Chemical%20Engineering%20Project%20-%20Graphs.pdf) — Project visualizations.

## Skills Demonstrated

- Chemical reaction kinetics
- Data analysis and interpretation
- Mathematical modeling
- Linear regression
- Spreadsheet calculations
- Predictive modeling
- Technical report writing

## Limitations

The concentration dataset was simulated rather than collected through a physical laboratory experiment. Therefore, this project demonstrates mathematical modeling and data analysis rather than experimental validation.

Additionally, the fitted model is evaluated over the available 0–20 minute dataset. Further work could investigate measurement uncertainty, alternative kinetic models, and the effects of temperature on reaction rates.

## Conclusion

This project demonstrates how first-order reaction kinetics can be investigated through mathematical analysis and regression modeling. The resulting model provides a close fit to the simulated concentration data and illustrates foundational techniques used in chemical engineering analysis.

**Project Type:** Independent Chemical Engineering Portfolio Project

**Tools:** Google Sheets, Microsoft Excel

**Focus:** Chemical Reaction Kinetics, Data Analysis, and Mathematical Modeling
