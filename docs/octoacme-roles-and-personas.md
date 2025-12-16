# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions with Other Roles
- **Product Managers**: Clarify requirements, discuss feasibility and trade-offs, estimate effort
- **Project Managers**: Report progress, escalate blockers, participate in planning
- **UX Designers**: Review design specs, collaborate on implementation approach, provide technical constraints
- **Data Analysts**: Implement tracking and instrumentation, provide data for analysis
- **Scrum Masters**: Communicate impediments, participate in ceremonies, provide team feedback
- **SMEs**: Seek guidance on architecture, security, and domain-specific patterns

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- **Developers**: Define requirements, review implementations, prioritize technical debt
- **Project Managers**: Align on scope and timelines, manage stakeholder expectations
- **UX Designers**: Partner on feature definition, validate user needs, prioritize design work
- **Data Analysts**: Define success metrics, review performance data, inform roadmap decisions
- **Scrum Masters**: Communicate product priorities, participate in backlog refinement
- **SMEs**: Understand domain constraints, validate feature feasibility

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- **Developers**: Track progress, remove blockers, coordinate releases
- **Product Managers**: Align on timelines and scope, manage stakeholder communication
- **UX Designers**: Schedule design reviews, ensure design delivery aligns with development
- **Data Analysts**: Request metrics for project tracking, include in status reports
- **Scrum Masters**: Coordinate on team processes, share risk and dependency information
- **SMEs**: Schedule reviews, ensure domain requirements are incorporated

---

## UX Designer

### Role Summary
UX Designers create user-centered experiences by researching user needs, designing interfaces, and validating solutions. They ensure products are intuitive, accessible, and aligned with user expectations.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Define information architecture and interaction patterns
- Collaborate with Product Managers and Developers on feature design
- Maintain design systems and accessibility standards
- Validate designs through user feedback and metrics

### Goals
- Improve user satisfaction and task completion rates
- Reduce friction and cognitive load in user flows
- Ensure consistent, accessible experiences across products
- Balance user needs with business and technical constraints

### Typical Communication
- Design reviews with stakeholders and engineering
- User research findings and usability test reports
- Figma/Sketch files with annotations and specs
- Collaboration in sprint planning and backlog refinement

### Interactions with Other Roles
- **Product Managers**: Partner on feature definitions, validate user needs, align on priorities
- **Developers**: Provide design specs, collaborate on implementation feasibility, review UI implementations
- **Project Managers**: Communicate design dependencies, participate in timeline planning
- **Data Analysts**: Review analytics to identify usability issues, validate design impact
- **QA/Testing**: Define acceptance criteria for UI/UX, participate in acceptance testing

---

## Data Analyst

### Role Summary
Data Analysts transform raw data into actionable insights that inform product decisions, measure outcomes, and identify opportunities. They enable data-driven decision-making across teams.

### Responsibilities
- Design and implement metrics, dashboards, and reports
- Analyze user behavior, feature adoption, and business metrics
- Conduct A/B tests and experiments to validate hypotheses
- Identify trends, anomalies, and improvement opportunities
- Partner with stakeholders to define success metrics
- Ensure data quality and integrity

### Goals
- Enable evidence-based product and business decisions
- Improve visibility into product performance and user behavior
- Identify high-impact opportunities through data insights
- Democratize data access across the organization

### Typical Communication
- Weekly metrics reviews and trend analysis
- Experiment design and results presentations
- Dashboard creation and metric definitions
- Ad-hoc analysis requests and findings reports

### Interactions with Other Roles
- **Product Managers**: Define success metrics, analyze feature performance, inform roadmap priorities
- **Developers**: Implement instrumentation and tracking, provide data infrastructure requirements
- **Project Managers**: Report on project metrics, identify risks through data signals
- **UX Designers**: Share user behavior insights, measure design impact
- **Stakeholders**: Present business metrics and strategic insights

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile practices. They create an environment where teams can deliver value efficiently while continuously improving.

### Responsibilities
- Facilitate sprint ceremonies (planning, dailies, reviews, retrospectives)
- Remove blockers and impediments that slow team progress
- Coach team members on agile principles and practices
- Shield the team from external interruptions
- Track team velocity and help optimize workflow
- Foster a culture of continuous improvement and psychological safety

### Goals
- Maximize team productivity and delivery predictability
- Minimize waste and unplanned work
- Build high-performing, self-organizing teams
- Maintain sustainable pace and team morale

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker escalation and resolution tracking
- Team health metrics and retrospective summaries
- Coaching conversations and process improvement proposals

### Interactions with Other Roles
- **Developers**: Remove blockers, facilitate collaboration, protect focus time
- **Product Managers**: Facilitate backlog refinement, communicate capacity and velocity
- **Project Managers**: Coordinate on dependencies and timelines, align on risk management
- **UX Designers**: Include in sprint planning, ensure design readiness
- **Data Analysts**: Request metrics for team performance and flow optimization

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts provide specialized domain knowledge in areas such as security, compliance, architecture, or specific business domains. They guide teams on best practices and ensure solutions meet domain-specific requirements.

### Responsibilities
- Provide domain expertise and technical guidance
- Review designs and implementations for compliance with standards
- Define best practices, patterns, and guardrails
- Participate in architectural and design reviews
- Help teams navigate complex domain-specific challenges
- Mentor team members and share knowledge

### Goals
- Ensure solutions meet domain-specific requirements and standards
- Reduce technical debt and architecture drift
- Prevent costly mistakes through early guidance
- Build organizational knowledge and capability

### Typical Communication
- Design review meetings and architecture discussions
- Documentation of patterns, standards, and guidelines
- Office hours and ad-hoc consultations
- Training sessions and knowledge sharing presentations

### Interactions with Other Roles
- **Developers**: Provide technical guidance, review code for domain compliance
- **Product Managers**: Advise on feasibility, constraints, and domain-specific opportunities
- **Project Managers**: Identify domain-specific risks, estimate review timelines
- **UX Designers**: Ensure designs comply with domain standards (e.g., accessibility, security)
- **Data Analysts**: Define domain-specific metrics and compliance reporting

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Core personas (Developers, Product Managers, Project Managers) are involved in most projects.
- Extended personas (UX Designer, Data Analyst, Scrum Master, SME) are engaged based on project needs and complexity.

