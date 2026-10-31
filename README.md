# Login Optimisation Using A/B Testing

## Project Overview

This project evaluates whether introducing mobile number and OTP-based authentication improves the login success rate compared with the existing email/password authentication process on an e-commerce platform.

An A/B testing approach will be used to compare both experiences, measure their performance, and determine whether the new authentication method delivers a statistically significant improvement.

## 1. Business Problem

The existing email/password authentication process may create friction for users, resulting in unsuccessful login attempts and potential user abandonment.

The product team proposes introducing a mobile number and OTP-based authentication process to simplify the login experience.

The experiment will help determine whether this change improves login success.

## 2. Business Objective

To evaluate whether the new OTP authentication experience increases the user login success rate compared with the existing email/password authentication process.

## 3. Experiment Design

Two versions will be compared:

| Version | Description |
|---|---|
| A – Control | Existing email/password login |
| B – Treatment | New mobile number + OTP login |

Users will be randomly assigned to either Version A or Version B.

Each user should consistently receive their assigned experience.

## 4. Key Performance Indicators (KPIs)

### Primary KPI

**Login Success Rate**

Percentage of users who successfully complete authentication.

Formula:

`Login Success Rate = Successful Logins / Total Assigned Users × 100`

### Secondary KPIs

- Login abandonment rate
- Login failure rate
- Average login completion time

### Guardrail Metrics

- OTP delivery failure rate
- Authentication errors
- Login response time
- Security incidents
- Customer support complaints

These metrics help ensure that improvements in login success do not negatively affect the overall user experience or system reliability.

## 5. Hypothesis

The experiment will test whether the new OTP authentication experience improves login success.

**Null Hypothesis (H₀):**

There is no difference in login success rates between Version A and Version B.

**Alternative Hypothesis (H₁):**

There is a difference in login success rates between Version A and Version B.

A two-tailed test will be used because both improvement and deterioration are important business outcomes.

## 6. Experiment Planning

Before launching the experiment, the following parameters will be defined:

| Parameter | Purpose |
|---|---|
| Baseline Conversion Rate | Current login success rate |
| Minimum Detectable Effect (MDE) | Smallest meaningful improvement |
| Significance Level (Alpha) | Acceptable false-positive risk |
| Statistical Power | Ability to detect the planned effect |
| Sample Size | Required users in each group |
| Experiment Duration | Time required to collect sufficient data |

The required sample size will be calculated before the experiment starts.

## 7. Data Validation

Before performing statistical analysis, the experiment data will be checked for:

- Correct random user assignment
- Sample Ratio Mismatch (SRM)
- Duplicate users
- Missing values
- Incorrect event tracking
- Users exposed to multiple experiment versions
- Data consistency between groups

## 8. Analysis Methodology

The following analysis will be performed:

1. Calculate login success and failure rates.
2. Calculate absolute conversion lift.
3. Calculate relative conversion lift.
4. Calculate pooled proportion.
5. Perform a two-proportion Z-test.
6. Calculate the Z-score and p-value.
7. Evaluate statistical significance.
8. Calculate the 95% confidence interval.
9. Evaluate experiment sample size and planned statistical power.
10. Review guardrail metrics.

## 9. Business Decision

Based on the analysis, the experiment will help the product team decide whether to:

- Launch the new OTP authentication experience.
- Continue testing if more data is required under a valid testing plan.
- Improve the new authentication experience.
- Retain the existing login experience.

The final recommendation will consider statistical significance, improvement size, confidence interval and guardrail performance.

## 10. Tools and Technologies

Third-party tools will be used for calculations and statistical validation.

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data preparation, KPI calculations and validation |
| Google Sheets | Data organisation and metric calculations |
| Online A/B Test Sample Size Calculator | Required sample-size calculation |
| Online Two-Proportion Z-Test Calculator | Z-score, p-value and significance testing |
| Online Confidence Interval Calculator | 95% confidence interval calculation |
| Git and GitHub | Project documentation and version control |

All third-party calculation results will be checked against the underlying formulas to ensure accuracy.

## Expected Outcome

Develop an end-to-end A/B testing project that demonstrates how product analytics and statistical methods can support data-driven product decisions.
