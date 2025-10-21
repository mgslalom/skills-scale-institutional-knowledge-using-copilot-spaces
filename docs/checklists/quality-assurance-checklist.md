# Quality Assurance Checklist

This checklist ensures consistent quality verification throughout the project lifecycle. Use this to validate that deliverables meet acceptance criteria and quality standards before release.

---

## QA Entry Criteria

Before QA activities begin, verify that the following conditions are met:

- [ ] Acceptance criteria are clearly defined and documented
- [ ] Test environment is configured and accessible
- [ ] Code changes are committed and build is successful
- [ ] Unit tests are passing
- [ ] Feature is code-complete and ready for testing
- [ ] Test data and test accounts are available
- [ ] Dependencies and integrations are in place

---

## Review Steps

### Requirements and Design Review

- [ ] Review acceptance criteria for completeness and testability
- [ ] Validate that requirements are clear and unambiguous
- [ ] Identify edge cases and negative scenarios
- [ ] Review design documents and technical specs
- [ ] Confirm alignment between requirements and implementation plan

### Test Planning

- [ ] Create or update test plan based on acceptance criteria
- [ ] Identify test scenarios (positive, negative, edge cases)
- [ ] Define test data requirements
- [ ] Plan for integration, regression, and performance testing
- [ ] Identify automation opportunities

### Test Execution

- [ ] Execute functional tests against acceptance criteria
- [ ] Perform integration testing with dependent systems
- [ ] Conduct regression testing to ensure no unintended side effects
- [ ] Test error handling and boundary conditions
- [ ] Verify security requirements (authentication, authorization, data protection)
- [ ] Validate accessibility and usability requirements (if applicable)
- [ ] Test in production-like environment

### Defect Management

- [ ] Log defects with clear reproduction steps
- [ ] Prioritize defects based on severity and impact
- [ ] Verify defect fixes and retest
- [ ] Track defect metrics and trends
- [ ] Ensure all critical and high-priority defects are resolved

---

## Test Coverage Expectations

- [ ] All acceptance criteria have corresponding test cases
- [ ] Code coverage meets project standards (e.g., 80% minimum)
- [ ] Critical paths and high-risk areas are thoroughly tested
- [ ] Integration points are validated
- [ ] Regression test suite is maintained and executed
- [ ] Automated tests are included where feasible

---

## Sign-Off Criteria

Before approving a release, confirm:

- [ ] All test cases mapped to acceptance criteria have passed
- [ ] No open critical or high-severity defects
- [ ] Regression testing is complete with no new issues
- [ ] Performance and security requirements are met
- [ ] Documentation is complete and accurate
- [ ] Rollback plan is documented and tested
- [ ] Stakeholders have reviewed and approved deliverables
- [ ] Quality metrics meet or exceed thresholds

---

## Handoff Steps for Release

- [ ] Provide QA sign-off to Project Manager and Change Manager
- [ ] Share test results and quality metrics
- [ ] Document known issues and workarounds (if any)
- [ ] Provide verification steps for post-deployment smoke testing
- [ ] Update test artifacts and test suite for future releases
- [ ] Participate in release readiness review
- [ ] Support deployment team during release (as needed)
- [ ] Verify production deployment via smoke tests
- [ ] Close QA cycle and archive test results

---

## Acceptance Criteria Alignment

This checklist aligns with issue #4 acceptance criteria by:

- Providing clear QA entry and exit criteria for consistent quality gates
- Defining comprehensive review and testing steps aligned with project standards
- Ensuring test coverage expectations are documented and measurable
- Establishing sign-off criteria that validate acceptance criteria are met
- Detailing handoff steps to support smooth release processes

**Reference:** [Issue #4](https://github.com/mgslalom/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)
