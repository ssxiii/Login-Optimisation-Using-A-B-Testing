# Data Analysis – Login Optimisation

## 1. Objective

Compare the login performance of Group A (existing email/password login) and Group B (new mobile number + OTP login) to determine whether the new experience improves login success.

## 2. Dataset Overview

The experiment dataset will contain user-level records with the following fields:

| Column | Description |
|---|---|
| user_id | Unique user identifier |
| experiment_group | Assigned group (A or B) |
| login_started | Whether the user started login |
| login_success | Whether the user successfully logged in |
| login_failed | Whether the login attempt failed |
| login_time_seconds | Time taken to complete login |
| experiment_date | Date of experiment activity |

The dataset will use synthetic practice data until actual experiment data is available.

## 3. Descriptive Analysis

Calculate the following metrics separately for Groups A and B:

- Total assigned users
- Successful users
- Failed users
- Login success rate
- Login failure rate
- Login abandonment rate
- Average login completion time

## 4. Conversion Rate Comparison

Calculate the login success rate for each group.

**Group A:**

Login Success Rate = Successful Users in A / Total Assigned Users in A × 100

**Group B:**

Login Success Rate = Successful Users in B / Total Assigned Users in B × 100

## 5. Conversion Lift

### Absolute Lift

Absolute Lift = Login Success Rate (B) − Login Success Rate (A)

This measures the difference in percentage points between the two groups.

### Relative Lift

Relative Lift = [(Login Success Rate (B) − Login Success Rate (A)) / Login Success Rate (A)] × 100

This measures the percentage improvement relative to the control group.

## 6. Statistical Analysis

A two-proportion Z-test will be used to compare the login success rates.

The analysis will calculate:

1. Pooled proportion
2. Pooled standard error
3. Z-score
4. P-value
5. Statistical significance at a 5% significance level

The null hypothesis will be rejected if the two-tailed p-value is below 0.05.

## 7. Confidence Interval

Calculate the 95% confidence interval for the difference in login success rates.

The confidence interval will help assess:

- Direction of the treatment effect.
- Range of plausible effect sizes.
- Whether the interval includes zero.

## 8. Guardrail Analysis

Compare the guardrail metrics across both groups:

- OTP delivery failure rate
- Authentication error rate
- Login response time
- Security incidents
- Customer support complaints

A positive primary KPI result should not automatically lead to a rollout if important guardrail metrics deteriorate.

## 9. Tools

The analysis will use:

- Microsoft Excel
- Google Sheets
- Online two-proportion Z-test calculator
- Online confidence interval calculator

All calculations and assumptions will be documented for reproducibility.

## 10. Final Analysis Output

The final analysis will present:

- Group A and Group B performance.
- Absolute and relative lift.
- Statistical test results.
- 95% confidence interval.
- Guardrail metric comparison.
- Evidence-based business recommendation.
