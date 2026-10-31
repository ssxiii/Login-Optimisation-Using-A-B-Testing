# A/B Testing Calculation Guide – Login Optimisation

## 1. Objective

Calculate and compare login performance between Group A (existing email/password login) and Group B (new mobile number + OTP login).

All calculations will use the synthetic dataset in `10_sample_dataset.csv`.

## 2. Basic Metrics

Calculate the following for each experiment group:

| Metric | Calculation |
|---|---|
| Total Assigned Users | Count of unique assigned users |
| Login Started | Count of users who started login |
| Successful Logins | Count of users with successful login |
| Failed Logins | Count of users with failed login |
| Abandoned Logins | Count of users who did not start login |
| Login Success Rate | Successful Logins / Total Assigned Users × 100 |
| Login Failure Rate | Failed Logins / Total Assigned Users × 100 |
| Login Abandonment Rate | Abandoned Logins / Total Assigned Users × 100 |

## 3. Conversion Lift

**Absolute Lift**

Login Success Rate (B) − Login Success Rate (A)

**Relative Lift**

[(Login Success Rate (B) − Login Success Rate (A)) / Login Success Rate (A)] × 100

## 4. Statistical Testing

A two-proportion Z-test will be used to compare the login success rates.

Calculations:

1. Pooled proportion
2. Pooled standard error
3. Z-score
4. Two-tailed p-value
5. Statistical significance decision

## 5. Confidence Interval

Calculate the 95% confidence interval for the difference between the two login success rates using an appropriate two-proportion interval method.

## 6. Third-Party Online Tools

| Tool | Purpose |
|---|---|
| Capture.Study – Two-Proportion Sample Size Calculator | Sample size and statistical power |
| Social Science Statistics – Z-Test Calculator | Z-score and p-value |
| Epitools – Two-Sample Z-Test | Confidence interval and proportion comparison |

Calculator outputs will be checked against the underlying statistical formulas.

## 7. Statistical Decision

Significance level: 0.05.

- If p-value < 0.05: Reject the null hypothesis.
- If p-value ≥ 0.05: Fail to reject the null hypothesis.

The direction of the observed difference and confidence interval must also be considered.

## 8. Documentation

For each calculation, record:

- Input values
- Third-party calculator used
- Calculator output
- Final interpretation

All results from the synthetic dataset must be identified as practice results, not actual business experiment findings.
