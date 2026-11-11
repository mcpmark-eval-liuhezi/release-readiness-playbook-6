# Rollback Plan

- [ ] Recall all in-flight deployments and set owner on-call for the release window
- [ ] Identify the last known good version tag and confirm it is deployable
- [ ] Roll back the release from production back to the last known good revision
- [ ] Notify the rollback owner and on-call teams that a rollback has begun
- [ ] Verify health: error rates, latency, and key customer flows return to baseline
- [ ] If problem persists, escalate to the incident commander and consider a full service restart
- [ ] Document the rollback reason, timeline, and root cause in the incident ticket
- [ ] Schedule a post-rollback review and update this plan with the lessons learned
