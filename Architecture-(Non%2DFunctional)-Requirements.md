Architecture/Non-functional Requirements for Modern University Course Registration System
=========================================================================================

### Overview
  
This page outlines and defines the non-functional requirements (NFRs) for the Modern University Course Registration System. These requirements are put in place to help ensure that the system meets the stakeholder criteria for security, scalability, availability, interoperability, sustainability, and standards/compliance needs. 
  
## 1.  Security Needs
-----------
    
  
**NFR-001: Data Protection and Authentication**
  
**Description:** The system must protect sensitive academic and personal data using modern security best practices, including encryption, role-based access control, and session management.
  
**Rationale:** Compliance with FERPA, GDPR, and internal IT policies is essential to protect sensitive information and maintain trust among the various stakeholders. Trust in system security is crucial for student adoption and institutional reputation.
  
**Metrics:**
  
*   100% of sensitive data will be encrypted both at rest and in transit
    
*   OAuth 2.0 and multi-factor authentication for administrators, students, and faculty
    
*   Role-Based Access Control, implementing the least privilege principle
    
*   Is compliant with the FERPA, GDPR, and NIST SP 800-53 security standards (NIST, n.d.).
    
*   Quarterly security auditing and logging of all user activity
    
  
**Acceptance Criteria:**
  
*   Regular security auditing schedule (every quarter)
    
*   Continuously maintains adherence to the guidelines of FERPA, GDPR, and NIST SP 800-53 security standards (NIST, n.d.).
    
*   No critical/high-severity issues detected from the audit
    
*   All sensitive data remains encrypted and access-logged
    
  
## 2.  Scalability Needs
----
    
  
**NFR-002: Growth Capacity**
  
**Description:** GSU is a very large university, so the system must be able to handle high volumes of user load and data efficiently, especially during peak registration periods. 
  
**Rationale:** With a total combined student population of 45,000, 3,200 faculty/staff, and 300 majors/programs combined, the system must continuously be able to support users and data at a large scale, without performance degradation.
  
**Metrics:** 
  
*   Support a 20% annual increase in users
    
*   Handle 30% growth in peak traffic loads
    
*   Assist in expansion into various new potential course types and academic programs
    
*   Manage capacity without downtime
    
*   Integration with future departmental systems
    
  
**Acceptance Criteria:**
  
*   No system downtime present during growth periods
    
*   User metrics demonstrate stable and consistent performance under increased user load conditions
    
*   Is able to successfully integrate at least two new systems annually
    
  
## 3.  Availability Needs
-----
    
  
**NFR-003: System Uptime and Recovery**
  
**Description:** The system must sustain high availability at all times, be easily accessible, and recover quickly from unexpected outages.
  
**Rationale:** High availability is crucial during peak periods like course registration and finals because without it, student, faculty, and staff satisfaction may decrease significantly since they won’t be able to efficiently complete their tasks.
  
**Metrics:**
  
*   Uptime: 99.9% annually during normal operations and 99.99% annually during peak registration periods (99.95% overall)
    
*   Recovery Time Objective (RTO): ≤ 2 hours
    
*   Recovery Point Objective (RPO): ≤ 5 minutes
    
  
**Acceptance Criteria:**
  
*   System issues are automatically identified and detected in real-time through monitoring and logging
    
*   System updates do not result in downtime for users
    
*   No more than 5 minutes of data is lost during any incident
    

## 4. Interoperability Needs
---    
  
**NFR-004: System Integration**
  
**Description:** The system must integrate and exchange data between different university departmental systems (e.g., SIS, LMS) smoothly to securely share student records, course information, and scheduling data.
  
**Rationale:** An efficient course registration system should be well-integrated with other university and external systems to provide a seamless experience, minimizing manual work and establishing data consistency. 
  
**Metrics:**
  
*   Real-time data synced across all integrated systems in under 10 minutes
    
*   API uptime: at least 99.9%
    
*   95% of API calls respond in less than 500ms
    
  
**Acceptance Criteria:**  
  

*   All APIs are documented and include a full set of automated integration tests
    
*   The system successfully integrates with all other major university and external systems
    
*   Successful integration of OAuth
    
  
## 5.  Sustainability Goals and Needs
----
  
**NFR-005: Environmental Responsibility**
  
**Description:** The system must be designed with the main priority to minimize environmental impact during both deployment and operations.
  
**Rationale:** With thousands of users estimated daily, GSU’s course registration system must align with sustainable IT practices to reduce carbon footprint/emissions, and improve operational efficiency (Maslova, 2023).
  
**Metrics:**
  
*   Limit log/telemetry data to less than or equal to 20MB per user/day
    
*   Enable auto-scaling
    
*   Cloud provider uses at least 70% renewable energy
    
  
**Acceptance Criteria:**


*   Successfully implements auto-scaling
    
*   Includes annual review of energy and carbon footprint metrics
    
*   Hosted on a cloud platform with defined and published sustainability metrics
    

## 6.  Standards and Compliance Needs
---
  
**NFR-006: Regulatory and Accessibility Compliance**
  
**Description:** The system must comply with all legal, accessibility, and institutional standards to protect sensitive data and maintain equitable access.
  
**Rationale:** Compliance with FERPA, GDPR, HIPAA, and WCAG 2.1 AA is crucial to ensuring privacy, security, and inclusivity, which are all basic foundations for user trust.
  
**Metrics:**
  
*   100% alignment with FERPA, HIPAA, and GDPR
    
*   At least 95% success rate in WCAG 2.1 AA accessibility audits
    
*   All system documentation demonstrates compliance controls
    
  
**Acceptance Criteria:**
  
*   Annual audit confirms full compliance
    
*   Accessibility testing passes WCAG benchmarks
    
*   System updates do not result in regressions in compliance
    
  
