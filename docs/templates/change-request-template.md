# Change Request Template

Use this template to document and track change requests for production systems or significant project changes. This ensures changes are planned, reviewed, and implemented with appropriate controls.

---

## Change Request Information

### CR-[NUMBER] - [Brief Title]

**Requestor:** [Name and Role]  
**Date Submitted:** [YYYY-MM-DD]  
**Target Implementation Date:** [YYYY-MM-DD]  
**Change Type:** [ ] Standard / [ ] Normal / [ ] Emergency / [ ] Organizational  

---

## Description

### Summary
Provide a concise description of the change (2-3 sentences).

[Description here]

### Business Justification
Explain why this change is needed and the expected benefits.

[Justification here]

### Technical Details
Describe what will be changed (systems, code, configuration, process, etc.).

[Technical details here]

---

## Impact Assessment

### Systems Affected
List all systems, applications, or processes impacted by this change.

- [System 1]
- [System 2]
- [System 3]

### Stakeholders Impacted
Identify users, teams, or customers affected by this change.

- [Stakeholder group 1]
- [Stakeholder group 2]

### Risk Level
**Risk Rating:** [ ] Low / [ ] Medium / [ ] High / [ ] Critical

**Risk Factors:**
- [Risk factor 1]
- [Risk factor 2]

**Mitigation Strategies:**
- [Mitigation 1]
- [Mitigation 2]

### Dependencies
List any dependencies or prerequisites for this change.

- [Dependency 1]
- [Dependency 2]

---

## Priority

**Priority Level:** [ ] P1 - Critical / [ ] P2 - High / [ ] P3 - Medium / [ ] P4 - Low

**Justification:**
[Explain why this priority level is appropriate]

---

## Approvers

Changes must be reviewed and approved before implementation.

| Approver Role | Name | Status | Date |
|--------------|------|--------|------|
| Change Manager | [Name] | [ ] Pending / [ ] Approved / [ ] Rejected | [Date] |
| Quality Assurance Lead | [Name] | [ ] Pending / [ ] Approved / [ ] Rejected | [Date] |
| Project Manager | [Name] | [ ] Pending / [ ] Approved / [ ] Rejected | [Date] |
| Technical Lead/Architect | [Name] | [ ] Pending / [ ] Approved / [ ] Rejected | [Date] |
| Project Sponsor (if required) | [Name] | [ ] Pending / [ ] Approved / [ ] Rejected | [Date] |

**Approval Notes:**
[Any conditions, concerns, or comments from approvers]

---

## Rollback Plan

### Rollback Trigger Conditions
Define the conditions that would require a rollback.

- [Trigger condition 1]
- [Trigger condition 2]

### Rollback Procedure
Document step-by-step instructions to revert the change.

1. [Rollback step 1]
2. [Rollback step 2]
3. [Rollback step 3]

### Rollback Testing
- [ ] Rollback procedure has been tested
- [ ] Rollback can be completed within [X] minutes/hours
- [ ] Data backup/recovery plan is in place

---

## Communication Plan

### Stakeholder Notification

**Pre-Implementation:**
- [ ] Stakeholder groups notified [X] days in advance
- [ ] Communication channels: [Email / Slack / Portal / etc.]
- [ ] Advance notice includes: change description, timeline, expected impact

**During Implementation:**
- [ ] Real-time status updates provided via [channel]
- [ ] Escalation contacts identified and communicated

**Post-Implementation:**
- [ ] Completion notification sent to stakeholders
- [ ] Summary of changes and next steps provided
- [ ] Feedback mechanism available

### Communication Timeline

| Milestone | Audience | Message | Channel | Date |
|-----------|----------|---------|---------|------|
| Change Approved | [Stakeholders] | Change scheduled for [date] | [Email] | [Date] |
| 48hrs Before | [Users] | Reminder and preparation steps | [Portal] | [Date] |
| Implementation Start | [Stakeholders] | Change in progress | [Slack] | [Date] |
| Implementation Complete | [All] | Change complete, verification steps | [Email] | [Date] |

---

## Implementation Workflow

### Example Approval Workflow

1. **Submit Change Request**
   - Requestor completes this template
   - Submits to Change Manager for review

2. **Initial Review** (Change Manager)
   - Assess completeness and risk level
   - Route to appropriate approvers based on change type
   - Request additional information if needed

3. **Technical Review** (QA Lead, Technical Lead)
   - Evaluate technical feasibility and risk
   - Validate rollback plan
   - Approve or request modifications

4. **Project Alignment** (Project Manager)
   - Confirm alignment with project schedule
   - Assess resource availability
   - Approve or negotiate timeline

5. **Executive Approval** (Project Sponsor - if required)
   - High-risk or high-impact changes only
   - Review business justification and risk
   - Final go/no-go decision

6. **Implementation**
   - Schedule change window
   - Execute change according to plan
   - Monitor for issues

7. **Verification and Close**
   - Verify change meets acceptance criteria
   - Confirm no adverse impacts
   - Document lessons learned
   - Close change request

### Implementation Checklist

- [ ] All approvals obtained
- [ ] Implementation date/time confirmed with stakeholders
- [ ] Implementation team briefed
- [ ] Pre-implementation backup completed
- [ ] Rollback plan ready and tested
- [ ] Monitoring and alerting in place
- [ ] Change implemented as planned
- [ ] Post-implementation verification complete
- [ ] Stakeholders notified of completion
- [ ] Documentation updated

---

## Post-Implementation Review

**Actual Implementation Date:** [YYYY-MM-DD]  
**Change Success:** [ ] Successful / [ ] Successful with Issues / [ ] Failed / [ ] Rolled Back

**Outcome Summary:**
[Brief description of results]

**Issues Encountered:**
- [Issue 1]
- [Issue 2]

**Lessons Learned:**
[What went well, what could be improved]

**Follow-Up Actions:**
- [ ] [Action item 1]
- [ ] [Action item 2]

---

## Acceptance Criteria Alignment

This change request template aligns with issue #4 acceptance criteria by:

- Providing structured fields for requestor, description, impact assessment, and priority
- Including a comprehensive approver workflow with clear roles and sign-off tracking
- Documenting rollback plans to ensure changes can be safely reverted if needed
- Defining detailed communication plans for stakeholder engagement before, during, and after changes
- Including an example workflow that demonstrates the approval and implementation process
- Ensuring changes are traceable, accountable, and aligned with project governance

**Reference:** [Issue #4](https://github.com/mgslalom/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)
