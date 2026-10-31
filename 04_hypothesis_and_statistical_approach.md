# Hypothesis and Statistical Approach

## 1. Experiment Objective

Determine whether mobile number and OTP-based authentication improves the login success rate compared with the existing email/password authentication.

## 2. Hypothesis Formulation

Let:

- \(p_A\) = Login success rate of Group A.
- \(p_B\) = Login success rate of Group B.

**Null Hypothesis (H₀):**

\[
p_A = p_B
\]

There is no difference in login success rates between the two groups.

**Alternative Hypothesis (H₁):**

\[
p_A \neq p_B
\]

There is a difference in login success rates between the two groups.

A two-tailed test will be used because both improvement and deterioration are important.

## 3. Statistical Test

A **Two-Proportion Z-Test** will be used to compare the login success rates of Group A and Group B.

This test is appropriate because:

- The outcome is binary: successful login or unsuccessful login.
- Two independent user groups are being compared.
- The objective is to compare two proportions.

## 4. Statistical Parameters

| Parameter | Planned Value |
|---|---|
| Significance Level (Alpha) | 0.05 |
| Confidence Level | 95% |
| Statistical Power | 80% |
| Test Type | Two-tailed |
| Statistical Test | Two-Proportion Z-Test |

## 5. Statistical Calculations

The analysis will include:

1. Pooled proportion
2. Standard error
3. Z-score
4. P-value
5. Critical Z-value
6. 95% Confidence Interval

## 6. Decision Criteria

At a 5% significance level:

- If p-value < 0.05, reject the null hypothesis.
- If p-value ≥ 0.05, fail to reject the null hypothesis.

For the two-tailed test, the critical Z-values are approximately -1.96 and +1.96.

The confidence interval will also be reviewed to understand the range of plausible values for the difference in login success rates.

## 7. Interpretation

Statistical significance alone will not determine the business decision.

The final recommendation will also consider:

- Direction and size of the observed improvement.
- Confidence interval.
- Practical business impact.
- Guardrail metric performance.
