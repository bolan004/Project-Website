cat <<'EOF' > playbooks/website-build/README.md
# OCTech Website Build — Playbook (v1)

**Offering Name:** OCTech Website Build  
**Version:** v1.0  
**Status:** Locked (Baseline)  
**Owner:** Operational Core Technologies (OCTech)  
**Last Updated:** 2025-12-29  

---

## 1. Purpose

This playbook defines the standardized delivery model for the OCTech Website Build service.

It serves as the single source of truth for:
- Service delivery
- Consultant onboarding
- Scope control
- Quality assurance
- Audit and review

All engagements delivered under OCTech Website Build v1 must follow this playbook unless an approved exception is documented.

---

## 2. Service Overview

The OCTech Website Build is a fixed-scope, consulting-led website foundation service designed to deliver a professional, payments-ready website with clear scope, predictable delivery, and upgrade paths.

### Core Objectives
- Establish online credibility
- Enable payments readiness (Stripe)
- Implement SEO fundamentals
- Provide a clean foundation for future growth

### Target Clients
- Small businesses
- Professional services firms
- Startups requiring a fast, credible web presence

---

## 3. In-Scope vs Out-of-Scope

### In Scope (All Tiers)
- Hosting evaluation and recommendation
- Template selection and configuration
- Core pages:
  - Home
  - About
  - Services
  - Contact
- Stripe connection (payments readiness)
- SEO baseline (titles and meta descriptions)
- Cross-device QA
- Delivery handoff and sign-off

### Out of Scope (Unless Explicitly Added)
- Custom application development
- Advanced SEO or content strategy
- Ongoing maintenance
- Security monitoring
- Customer portals or authentication
- Paid advertising or campaign setup

Out-of-scope items may be offered as post-launch add-ons.

---

## 4. Delivery Model (v1)

Delivery follows a linear, checklist-driven model to minimize rework.

### Phases
1. Discovery
2. Build
3. Content
4. Integrations
5. QA
6. Handoff

Each phase has defined entry criteria, tasks, and exit conditions.

---

## 5. Roles & Responsibilities

### OCTech (Consultant)
- Owns delivery execution
- Manages scope and timeline
- Performs configuration, QA, and handoff
- Requests formal sign-off

### Client
- Provides brand inputs and access
- Reviews content in a timely manner
- Confirms completion and acceptance

Delays in client input may impact delivery timelines.

---

## 6. Jira Execution Model

Each engagement is instantiated using the Website Build v1 Jira CSV.

### Jira Structure
- 1 Epic: Website Foundation Build
- Multiple Tasks mapped to delivery phases

The Jira CSV located at:

/ops/jira/octech-website-build-v1-jira-import.csv

is the canonical execution template and must not be modified without versioning.

---

## 7. Quality Gates & Acceptance Criteria

### QA Checklist (Required)
- Mobile and desktop rendering verified
- Navigation and links validated
- Primary CTA tested
- Stripe connection validated (test mode)
- SEO titles and meta descriptions set

### Acceptance
Delivery is considered complete when:
- Website is published
- Stripe connection is validated
- Client receives completion summary
- Client approval or sign-off is requested

---

## 8. Commercial Guardrails

- Fixed scope per selected tier
- Revisions limited by tier
- Any scope expansion requires written approval
- Add-ons are quoted separately post-launch

This protects delivery velocity and margin.

---

## 9. Versioning & Change Control

### Current Version
- v1.0 — Baseline launch offering

### Future Enhancements (Examples)
- v1.1: Pricing refinements, minor process optimizations
- v2.0: Portal-ready builds, advanced analytics, security bundles

Changes must be documented, versioned, and communicated prior to use.

---

## 10. Reuse & Scaling Guidance

This playbook is designed for reuse across clients and rapid onboarding of new consultants.

Do not fork or customize per client.  
Instantiate via Jira and apply client-specific inputs at execution time.

---

## 11. Audit & Review

This document may be used for:
- Internal reviews
- Delivery audits
- Scope disputes
- Client clarification

Any deviations must be documented.

---

## 12. Final Notes

This playbook represents the authoritative v1 delivery standard for the OCTech Website Build offering.

If it’s not in this document, it is not part of v1.

---

END OF DOCUMENT
EOF

