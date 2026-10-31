# Experiment Planning – Login Optimisation

## 1. Objective

Define the experiment parameters and calculate the required sample size before launching the test.

## 2. Planning Parameters

| Parameter | Planned Value | Description |
|---|---:|---|
| Baseline Login Success Rate | 65% | Expected success rate of the existing login experience |
| Minimum Detectable Effect (MDE) | 2 percentage points | Smallest improvement considered meaningful |
| Expected Treatment Rate | 67% | Baseline rate plus the planned MDE |
| Significance Level (Alpha) | 0.05 | Acceptable Type I error rate |
| Statistical Power | 80% | Ability to detect the planned effect |
| Confidence Level | 95% | Corresponds to a two-sided alpha of 0.05 |
| Test Type | Two-tailed | Detects improvement or deterioration |
| Traffic Allocation | 50:50 | Equal allocation between Groups A and B |

These are planning assumptions for the project, not actual experiment results.

## 3. Minimum Detectable Effect (MDE)

MDE is the smallest difference in login success rates that the experiment is designed to detect with the specified statistical power and significance level.

For this experiment:

- Baseline login success rate = 65%
- Planned treatment login success rate = 67%
- MDE = 67% − 65% = 2 percentage points

The MDE should reflect the smallest improvement that would be meaningful to the business.

## 4. Sample Size Calculation

The required sample size will be calculated using an online A/B testing sample size calculator.

**Inputs:**

- Baseline conversion rate: 65%
- Expected treatment conversion rate: 67%
- Significance level: 5%
- Statistical power: 80%
- Test type: Two-tailed
- Allocation ratio: 50:50

The calculator output will determine the required number of users in each group.

The sample size result will be documented before the experiment begins.

## 5. Experiment Duration

Experiment duration will depend on:

- Required sample size per group.
- Expected eligible users per day.
- Traffic allocation.
- Business seasonality and weekly usage patterns.

The experiment should cover representative user behaviour, including relevant weekday and weekend patterns.

## 6. Stopping Criteria

The experiment should not be stopped early simply because the p-value becomes statistically significant.

The test should run until the predefined sample size and experiment duration requirements are satisfied, unless a predefined safety or data-quality stopping condition is triggered.

## 7. Planning Summary

The experiment will use a two-tailed two-proportion test with a 5% significance level and 80% statistical power.

The final sample size and duration will be recorded after completing the calculator-based planning exercise.
