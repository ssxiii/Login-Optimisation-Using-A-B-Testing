# Data Validation – Login Optimisation

## 1. Objective

Validate the experiment data to ensure that user assignment, event tracking and collected metrics are accurate and reliable before performing A/B test analysis.

## 2. Data Quality Checks

| Validation Check | Purpose |
|---|---|
| Randomisation Check | Ensure users are randomly assigned to Groups A and B |
| Sample Ratio Mismatch (SRM) | Check whether actual group allocation differs significantly from the planned 50:50 split |
| Duplicate Users | Ensure each user is counted only once in the primary analysis |
| Missing Values | Identify missing user IDs, group assignments or login outcomes |
| Event Tracking | Verify that login success and failure events are recorded correctly |
| Cross-Exposure | Identify users exposed to both login experiences |
| Data Consistency | Ensure both groups follow the same metric definitions |

## 3. Sample Ratio Mismatch (SRM)

SRM occurs when the observed distribution of users across experiment groups differs significantly from the expected allocation.

For this experiment, the expected allocation is:

- Group A: 50%
- Group B: 50%

A significant mismatch may indicate problems with randomisation, eligibility rules, assignment logic or data collection.

## 4. User-Level Validation

The primary analysis will use unique assigned users.

Validation will ensure:

- Each user has one experiment group assignment.
- Each user is counted only once in the primary analysis.
- Login outcomes are linked to the correct assigned group.
- Users exposed to both variants are identified and investigated.

## 5. Event Tracking Validation

The following events should be tracked consistently:

| Event | Description |
|---|---|
| Login Page Viewed | User opens the login page |
| Login Started | User begins the authentication process |
| Login Successful | User completes authentication successfully |
| Login Failed | User fails authentication |
| Login Abandoned | User starts but does not complete login |

Event definitions and measurement windows must be consistent across both groups.

## 6. Validation Outcome

Statistical analysis should begin only after critical data quality issues have been investigated and resolved.

Any exclusions or corrections should be documented to maintain transparency and reproducibility.
