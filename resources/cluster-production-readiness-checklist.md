# AlloyDB Cluster Production Readiness Checklist

## Environment and architecture
- [ ] Correct project, region, cluster, and instance are confirmed.
- [ ] Primary and read pool sizing matches the workload.
- [ ] Private connectivity is preferred where practical.
- [ ] Network paths, authorized networks, PSC/PSA, and firewall rules are reviewed.
- [ ] High availability and regional failure assumptions are documented.

## Identity and secrets
- [ ] IAM roles follow least privilege.
- [ ] IAM database authentication is preferred where supported.
- [ ] Service agents have only required permissions.
- [ ] Passwords and connection secrets are stored in Secret Manager or equivalent.
- [ ] Public IP access is restricted to approved CIDRs.
- [ ] No credential is passed in shell history or committed to source control.

## Operations
- [ ] Backup retention and point-in-time recovery requirements are confirmed.
- [ ] Restore has been tested in a separate environment.
- [ ] Maintenance windows and restart impact are understood.
- [ ] Monitoring, alerts, and ownership are configured.
- [ ] Connection pooling and capacity limits are considered.
- [ ] Cost estimates are based on current official pricing.

## Approval
- Change owner:
- Reviewer:
- Environment:
- Rollback/recovery plan:
- Approval reference:
