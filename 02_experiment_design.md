# Experiment Design – Login Optimisation

## 1. Experiment Overview

The experiment will compare the existing email/password login experience with the proposed mobile number and OTP login experience.

The objective is to determine whether OTP-based authentication improves the login success rate.

## 2. Experiment Variants

| Group | Type | Login Experience |
|---|---|---|
| A | Control | Existing email/password login |
| B | Treatment | New mobile number + OTP login |

## 3. Target Audience

The experiment will include eligible e-commerce users who reach the login page during the experiment period.

Users who are not eligible for the new authentication method will be excluded based on predefined eligibility criteria.

## 4. Randomisation

Users will be randomly assigned to either Group A or Group B.

- 50% of eligible users will be assigned to Group A.
- 50% of eligible users will be assigned to Group B.
- Each user will remain in the same group throughout the experiment.

Randomisation helps ensure that differences in outcomes are attributable to the login experience rather than systematic differences between user groups.

## 5. Experiment Unit

The randomisation unit will be the **unique user**.

Each user will be counted only once in the primary login success rate analysis.

## 6. Primary Success Metric

**Login Success Rate**

\`Login Success Rate = Successfully Logged-in Users / Total Assigned Users × 100\`

The primary metric will compare the percentage of assigned users who successfully log in across both groups.

## 7. Experiment Duration

The experiment will run until:

- The required sample size is reached in both groups.
- The predefined experiment duration is completed.
- Data quality and guardrail metrics remain acceptable.

The experiment will not be stopped early just because the results appear statistically significant.

## 8. Experiment Considerations

- Both groups should run during the same period.
- Users should not switch between variants.
- Login events must be tracked consistently.
- The same eligibility criteria should apply to both groups.
- Sample ratio mismatch and data quality issues must be checked before analysis.
