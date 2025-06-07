This section identifies key risks, assumptions, and dependencies that affect system delivery.


## Risks, Assumptions, and Dependencies -

# Risks

**1. System overload during peak registration:**
*   _Description:_ Heavy system traffic can crash the system.
    
*   _Mitigation:_ To mitigate this, we plan to conduct load testing quarterly and we’ll use auto-scaling on cloud infrastructure to maintain performance.

**2. Low adoption due to UI unfamiliarity:**
*   _Description:_ The new interface may take some time to adjust to, so students/faculty may struggle with the usability of it at first.
    
*   _Mitigation:_ With sufficient support, like offering in-app tutorials, training webinars, and other helpful resources, this issue can be mitigated.
 
**3. Failure to successfully integrate SIS/LMS:**
*   _Description:_ If these two applications don’t sync properly, it may cause registration errors among students/faculty.
    
*   _Mitigation:_ Utilize more API contracts and do sandbox testing prior to launch.
 
    
**4. Security breaches or FERPA violations:**
*   _Description:_ Unauthorized access can compromise student data.
    
*   _Mitigation:_ Ensure that there is strong encryption and perform regularly scheduled security audits.    

**5. Accessibility gaps:**
*   _Description:_ Gaps in compliance for accessibility makes it difficult for students with disabilities to thrive in an academic environment.
    
*   _Mitigation:_ Conduct quarterly usability testing and collaborate with accessibility experts to ensure that standards are being met.
    
# Assumptions

**1. Users have internet access and personal devices**
*   _Impact:_ The system is heavily reliant on web-based access.
    
*   _Rationale:_ Most students and faculty access digital services on a laptop, using the internet, regularly.
      
    
**2. GSU IT will support system deployment**
*   _Impact:_ Without active collaboration from the IT department, deployment may be significantly delayed.
    
*   _Rationale:_ IT’s cooperation and role is crucial for all university-wide tech releases.
      
    
**3. APIs are available and stable**
*   _Impact:_ Data flow from SIS/LMS is important for real-time updates.
    
*   _Rationale:_ This is a modern system and it is expected that we are able to provide documentation.
    
**4. Users have a basic level of tech literacy**
*   _Impact:_ The interface is designed for independent use without comprehensive onboarding.
    
*   _Rationale:_ Most students/staff are already familiar with digital systems at the university.
    
**5. Registration dates continuously remain fixed**
*   _Impact:_ System configuration and testing are largely dependent on known deadlines.
    
*   _Rationale:_ Academic calendars are stringent and rarely change.
      
##     
# Dependencies
- SIS (Student Information System): Required for real-time student and course data exchange.  
      
    
- Email/SMS gateway providers: Needed for automated waitlist and notification functionality.  
      
    
- Cloud hosting platform (e.g., Azure/AWS): Required for deployment and scaling.  
      
    
- Accessibility testing tools: Necessary to validate WCAG 2.1 compliance.  
      
    
- University IT operations: Required for support, uptime monitoring, and incident response.  
