# Business Recommendation – Login Optimisation

## 1. Objective

Translate the A/B testing results into an actionable recommendation for the product team.

The decision will be based on login success rate, statistical significance, confidence interval and guardrail metrics.

## 2. Decision Framework

| Experiment Outcome | Recommended Action |
|---|---|
| Group B performs better, result is statistically significant, and guardrails are acceptable | Recommend rolling out OTP login |
| Group B performs better, but result is not statistically significant | Do not claim a proven improvement; review the confidence interval and follow the predefined testing plan |
| Group B performs worse and the difference is statistically significant | Retain the existing login experience and investigate the reasons |
| Group B performs better, but important guardrail metrics deteriorate | Investigate and resolve the issues before rollout |
| No meaningful difference between groups | Evaluate implementation cost and other business considerations before deciding |

## 3. Evaluation Criteria

The final recommendation will consider:

- **Login success rate:** Did OTP authentication improve successful logins?
- **Absolute lift:** How many percentage points did the login success rate change?
- **Relative lift:** What was the percentage improvement compared with the control?
- **Statistical significance:** Is there sufficient evidence of a difference?
- **Confidence interval:** What range of treatment effects is plausible?
- **Guardrail metrics:** Did the new experience negatively affect reliability or user experience?

## 4. Final Recommendation Format

The final experiment report will include:

1. Business objective
2. Experiment design
3. Sample size and experiment duration
4. Group A and Group B performance
5. Absolute and relative lift
6. Z-score and p-value
7. 95% confidence interval
8. Guardrail metric comparison
9. Final business recommendation

## 5. Important Note

No actual experiment results or business recommendation will be claimed until the dataset has been analysed.

Any practice results generated using synthetic data will be clearly identified as illustrative.
