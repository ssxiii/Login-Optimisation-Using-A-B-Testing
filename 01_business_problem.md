# Business Problem – Login Optimisation

## 1. Background

An e-commerce platform currently uses email and password authentication for users to access their accounts.

The product team has identified that some users may experience friction during the login process due to forgotten passwords, incorrect credentials, or difficulties completing authentication.

To simplify the login experience, the team proposes introducing mobile number and OTP-based authentication.

## 2. Problem Statement

The existing email/password login process may result in unsuccessful login attempts and user abandonment.

However, introducing OTP-based authentication does not automatically guarantee a better experience.

The product team needs evidence to determine whether the new login method improves the login success rate compared with the existing method.

## 3. Proposed Solution

Conduct an A/B test to compare two authentication experiences:

| Group | Login Experience |
|---|---|
| A – Control | Existing email/password authentication |
| B – Treatment | New mobile number and OTP authentication |

Eligible users will be randomly assigned to one of the two groups.

## 4. Business Objective

Determine whether OTP-based authentication improves the login success rate without negatively affecting other important user experience and system performance metrics.

## 5. Key Business Question

Does mobile number and OTP-based authentication increase the login success rate compared with the existing email/password authentication?

## 6. Expected Business Impact

If the new authentication method performs better, it could:

- Improve successful user logins.
- Reduce login abandonment.
- Simplify the authentication experience.
- Improve user experience and account accessibility.

The final decision will be based on experiment results, statistical evidence, and guardrail metrics.
