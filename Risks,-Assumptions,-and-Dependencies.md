This section identifies key risks, assumptions, and dependencies that affect system delivery.


## Risks, Assumptions, and Dependencies -

### Risks
1.  System overload during peak registration:
    
*   Description: Heavy system traffic can potentially crash the system.
    
*   Mitigation: To mitigate this, we plan to conduct load testing quarterly and we’ll use auto-scaling on cloud infrastructure to maintain performance.
    
2.  Low adoption due to UI unfamiliarity:
    
*   Description: The new interface may take some time to adjust to, so students and faculty may struggle with the usability of it at first.
    
*   Mitigation: With sufficient support, like offering in-app tutorials, training webinars, and other helpful resources, this issue can be mitigated.
    
3.  Failure to successfully integrate SIS/LMS:
    
*   Description: If these two applications don’t sync properly, it may cause registration errors among students/faculty
    
*   Mitigation: Utilize more API contracts and do sandbox testing prior to launch.
    
4.  Security breaches or FERPA violations:
    
*   Description: Unauthorized access can compromise student data.
    
*   Mitigation: Ensure that there is strong encryption and perform regularly scheduled security audits.
    
5.  Accessibility gaps:
    
*   Description: Gaps in compliance for accessibility can make it difficult for students with disabilities to thrive in an academic environment.
    
*   Mitigation: Conduct quarterly usability testing and collaborate with accessibility experts to ensure that standards are being met.
    
### Assumptions
1.  Users have internet access and personal devices
    
*   Impact: The system is heavily reliant on web-based access.
    
*   Rationale: Most students and faculty access digital services on a laptop, using the internet, regularly.  
      
    
2.  GSU  IT will support system deployment:
    
*   Impact: Without active collaboration from the IT department, deployment may be significantly delayed.
    
*   Rationale: IT’s cooperation and role is crucial for all university-wide tech releases.  
      
    
3.  APIs are available and stable:
    
*   Impact: Data flow from SIS/LMS is important for real-time updates
    
*   Rationale: This is a modern system and it is expected that we are able to provide documentation.
    
      4.  Users have a basic level of tech literacy:
*   Impact: The interface is designed for independent use without comprehensive onboarding.
    
*   Rationale: Most students/staff are already familiar with digital systems at the university.
    
      5. Registration dates continuously remain fixed:
*   Impact: System configuration and testing are largely dependent on known deadlines.
    
*   Rationale: Academic calendars are stringent and rarely change.  
      
    
### Dependencies
1.  SIS (Student Information System): Required for real-time student and course data exchange.  
      
    
2.  Email/SMS gateway providers: Needed for automated waitlist and notification functionality.  
      
    
3.  Cloud hosting platform (e.g., Azure/AWS): Required for deployment and scaling.  
      
    
4.  Accessibility testing tools: Necessary to validate WCAG 2.1 compliance.  
      
    
5. University IT operations: Required for support, uptime monitoring, and incident response.  
