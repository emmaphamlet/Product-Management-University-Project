**

### DFD Summary for Search & Filter Courses 
(User Story #52)

This Data Flow Diagram (DFD) illustrates the flow of data in the GSU course registration system’s course search and filtering functionality. The diagram focuses on the interactions between students and the system as they search for and filter courses based on their schedule preferences.
Key elements include:
*   External Entity: Student submits a search request and receives filtered course results.  
      
    
*   Processes:  
      
    
    *   Submit Search Request: Captures student’s search criteria.  
          
        
    *   Retrieve Course Data: Retrieves course information from the Course Catalog.  
          
        
    *   Apply Filters: Applies the student’s filter criteria to narrow down results.  
          
        
    *   Return Filtered Results: Prepares and returns the matching course list.  
          
        
*   Data Stores:  
      
    
    *   Course Catalog: Stores all course information.  
          
        
    *   User Preferences: Stores student-specific search criteria.  
          
        
*   Data Flows: Include search requests, course data, filter criteria, and filtered results.  
      
    
This DFD demonstrates how the system supports high-performance search and filtering, aligning with Epic #20’s goal of seamless student course registration. The diagram clarifies the system’s logical data flow, emphasizing how user preferences and course data interact to deliver filtered search results.![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeZWKqNQFz26YoeDuLQlq_yanvEudutx70EDqjaEACdCdrlusyiCbvqC-5m45mRkr0CDUFiA8RiTzU7vNdsmChwJuZGF-ozPnhYw5657sSiO3kljBRW1n8vgSu2DIWeFB5uhGSCaA?key=CCY4zK8XX7j-YndUtNuULQ)
  
  
![截屏2025-06-08 下午11.15.19.png](/.attachments/截屏2025-06-08%20下午11.15.19-3dd0cd73-0c3e-4851-aa87-f2f17106889a.png)DFD 
### **DFD Summary for Waitlist for Full Classes**

_(User Story 53: As a student, I want to be waitlisted for full classes so that I don't miss a chance to enroll.)_
This Level 1 Data Flow Diagram (DFD) depicts how students at GSU are automatically added to a course waitlist when a class is full, ensuring they don’t miss enrollment opportunities. The diagram expands the basic waitlist automation logic, including advisor manual intervention and structured student notification processes.

####  Key elements include:

**External Entities:**
*   **Student**: Submits a registration request and receives confirmation and waitlist status updates.
    
*   **Advisor**: Assists in special cases by manually reviewing and updating waitlist records when needed.
    
**Processes:**
*   **1.1 Submit Registration Request**: Captures and processes the student’s registration request.
    
*   **1.2 Add to Waitlist**: Checks course availability using data from the Course Catalog. If the course is full, the student is added to the waitlist based on a timestamp.
    
*   **1.3 Notify Student**: Displays waitlist status in the student interface and triggers feedback loop.
    
*   **1.4 Send Email Notification**: Sends a confirmation email to the student within 1 minute of waitlist entry.
    
*   **1.5 Advisor Manual Notification**: Advisor intervenes when escalated and may notify students directly or update waitlist records.
    
**Data Stores:**
*   **Course Catalog**: Stores up-to-date course capacity and enrollment data.
    
*   **Waitlist Records**: Stores waitlist entries, timestamps, student data, and manual overrides if applicable.
    
**Data Flows:**  
Include registration requests, course data queries, timestamped waitlist entries, student status updates, advisor input, and automated email confirmations.