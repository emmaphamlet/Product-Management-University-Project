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
  
  
DFD Summary for Waitlist for Full Classes 
(User Story #53)
This Data Flow Diagram (DFD) depicts the process through which students at GSU are automatically added to a course waitlist when a class is full, ensuring they don’t miss enrollment opportunities.
Key elements include:
*   External Entity: Student submits a registration request and receives confirmation and waitlist status updates.  
      
    
*   Processes:  
      
    
    *   Submit Registration Request: Processes student’s registration request.  
          
        
    *   Check Availability: Checks course capacity using Course Catalog data.  
          
        
    *   Add to Waitlist: Automatically adds student to waitlist if the course is full.  
          
        
    *   Notify Student: Sends confirmation emails and waitlist status updates to the student.  
          
        
*   Data Stores:  
      
    
    *   Course Catalog: Stores course capacity and availability data.  
          
        
    *   Waitlist Records: Stores waitlist entries, timestamps, and student information.  
          
        
*   Data Flows: Include registration requests, course data, waitlist entries, confirmation emails, and waitlist statuses.  
      
    
This DFD captures the waitlist management functionality’s logical flow, highlighting the system’s ability to handle course capacity checks, waitlist entry management, and timely notifications. It supports Epic #20’s goals of streamlining registration workflows and improving user experience.
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdAY1Exqpssc9SiIoa0zyXMWDCmm9632i_1agJCQ5HFRxY55RPLn6l9JgflXbE4qCF_PzYsEMESvZuA64fphtJfsCVCGc5bvQ0_AmpMYthkSuiyB4apHhEoay4E-t0iHv1sc1A18w?key=CCY4zK8XX7j-YndUtNuULQ)
**