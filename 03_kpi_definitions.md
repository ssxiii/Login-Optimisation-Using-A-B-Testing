# KPI Definitions – Login Optimisation

## 1. Primary KPI

### Login Success Rate

Measures the percentage of assigned users who successfully complete the login process.

**Formula:**

Login Success Rate = (Unique Users Who Successfully Logged In / Total Unique Users Assigned) × 100

This is the primary metric used to determine whether OTP authentication improves login performance.

## 2. Secondary KPIs

### Login Failure Rate

Measures the percentage of assigned users who fail to complete login.

**Formula:**

Login Failure Rate = (Unique Users Who Failed to Log In / Total Unique Users Assigned) × 100

### Login Abandonment Rate

Measures the percentage of assigned users who start the login process but leave without completing it.

**Formula:**

Login Abandonment Rate = (Users Who Abandoned Login / Users Who Started Login) × 100

### Average Login Completion Time

Measures the average time taken by users to complete authentication.

**Formula:**

Average Login Completion Time = Total Login Completion Time / Number of Successful Login Attempts

## 3. Guardrail Metrics

| Metric | Purpose |
|---|---|
| OTP Delivery Failure Rate | Monitor OTP delivery issues |
| Authentication Error Rate | Monitor login system errors |
| Login Response Time | Monitor system performance |
| Security Incidents | Monitor authentication-related security risks |
| Customer Support Complaints | Monitor negative user feedback |

## 4. KPI Comparison

All KPIs will be calculated separately for Group A and Group B using consistent definitions.

The primary comparison will be the difference in login success rates between the two groups.

**Absolute Lift:**

Login Success Rate (B) − Login Success Rate (A)

**Relative Lift:**

[(Login Success Rate (B) − Login Success Rate (A)) / Login Success Rate (A)] × 100

## 5. Measurement Considerations

- Use unique users as the denominator for the primary KPI.
- Count each user only once in the primary analysis.
- Apply identical event definitions to both groups.
- Ensure login success and failure events are tracked consistently.
- Analyse guardrail metrics before making the final rollout decision.
