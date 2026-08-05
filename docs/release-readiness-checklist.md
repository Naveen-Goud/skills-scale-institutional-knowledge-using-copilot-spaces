# Release Readiness Checklist

Purpose: A checklist to confirm readiness before production deployments to reduce failed releases and missing handoffs.

Pre-release (before deployment)
- [ ] All PRs merged and linked to issues with acceptance criteria
- [ ] CI passing (tests, linting, security scans)
- [ ] Database migration plan documented and reviewed
- [ ] Release notes drafted and reviewed by PdM
- [ ] Rollback plan documented and tested
- [ ] Stakeholders (Support/CS, Product, PM) notified of release window
- [ ] Monitoring and alerting runbooks prepared
- [ ] UX/Docs updates staged and reviewed

Deployment day
- [ ] Release Manager confirmed deployment window
- [ ] Platform/DevOps lead available to run pipeline
- [ ] QA smoke tests ready to run in staging and production
- [ ] Customer Success / Support aware of changes and FAQs

Post-release (immediate)
- [ ] Smoke tests executed and passed
- [ ] Release Owner confirms success metrics collection
- [ ] Post-deploy verification (basic flows) completed
- [ ] Support/CS ready for early customer contacts

Post-release (follow-up)
- [ ] Monitor metrics for 24–72 hours
- [ ] Capture any incidents or regressions in issue tracker
- [ ] Schedule post-release retro if significant issues occurred

Where to use:
- Add this checklist as a required artifact for any release; Release Manager must confirm items before sign-off.
