# AlloyDB Backup and Restore Drill

## Drill details
- Project:
- Region:
- Cluster:
- Source backup:
- Drill date:
- Operator:
- Approver:

## Pre-checks
- [ ] Correct project and region are verified.
- [ ] Backup exists and retention policy is understood.
- [ ] Restore target is isolated from production traffic.
- [ ] Required IAM permissions are approved.
- [ ] Data sensitivity and access controls are applied to the restore target.
- [ ] Application owners know that this is a recovery test.

## Execution record
| Step | Start time | End time | Result | Evidence |
|---|---|---|---|---|
| Verify backup | | | | |
| Restore to isolated target | | | | |
| Verify database connectivity | | | | |
| Validate schema and row counts | | | | |
| Run application smoke tests | | | | |
| Confirm cleanup/retention | | | | |

## Recovery objectives
- Target RPO:
- Observed data-loss window:
- Target RTO:
- Observed restore duration:
- Deviations:

## Outcome
- Recovery successful?:
- Data integrity issues:
- Follow-up actions and owners:
- Approver and date:

Never run a destructive restore over production as part of a drill.
