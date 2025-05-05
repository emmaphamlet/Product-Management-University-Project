This section identifies key risks, assumptions, and dependencies that affect system delivery.

#### Risks and Mitigation

1.  **Server overload during registration** – _Mitigation_: Implement load testing and auto-scaling cloud infrastructure.
    
2.  **Low adoption due to UI change** – _Mitigation_: Provide in-app tutorials and launch webinars.
    
3.  **Integration failure with SIS or LMS** – _Mitigation_: Establish early API contracts and testing sandboxes.
    
4.  **Security breaches or FERPA non-compliance** – _Mitigation_: Perform quarterly audits and enforce role-based access.
    
5.  **Accessibility non-compliance** – _Mitigation_: Partner with accessibility consultants during design and test with diverse users.
    

#### Key Assumptions

1.  Students and faculty have reliable internet access.
    
2.  GSU IT will provide technical support during deployment.
    
3.  All third-party systems offer documented APIs.
    
4.  Mobile access is critical due to high student device usage.
    
5.  University registration dates will remain fixed as scheduled.
    

#### Dependencies

1.  **SIS** – Required for real-time course and student data.
    
2.  **Notification APIs** – Needed for waitlist messages via email/SMS.
    
3.  **Cloud hosting** – Platform for uptime and autoscaling (e.g., Azure).
    
4.  **Accessibility tools** – Tools like Axe/WAVE for WCAG validation.
    
5.  **University IT department** – Support deployment, patching, and operational handoff.