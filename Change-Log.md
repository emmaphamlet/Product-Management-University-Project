---
title: Change-Log
---

**Change Log**
  
After reviewing the feedback we received on Milestone 2, we made some revisions aimed at sharpening the clarity of our deliverables. Here is an outline of the changes made:
*   Current State: Reviewers indicated that our Current State Page was satisfactory and met all deliverables for the Milestone 2 assignment. As a result, we have no revisions to report for our Current State.
    
*   Stakeholders: In Milestone 2, we populated a “Features Requested” column within our stakeholder analysis table which represented a wish-list style view of any feature a given stakeholder was looking for in the new course registration system. Feedback suggested we reformat this “Features Requested” section to a “Core Challenges/Frustrations” section. This would allow us to more explicitly state challenges with the old system instead of inferring features for the new system. This made problems with the old system more clearly defined and better showcased requested areas of improvement with the new system. To create this change, more precise analysis of stakeholder interviews were done to accurately identify challenges and frustrations with the old system. Additionally, we refactored phrasing and delivering of key challenges that stakeholders faced to better convey their frustrations in one unified table. This change not only improved the readability of our stakeholder analysis, but also better represented stakeholders needs rather than our inferences of what they’d translate to when thinking about features for the new system.
    
*   Research Summary Page: Reviewers indicated that our Research Summary Page was satisfactory and met all deliverables for the Milestone 2 assignment. As a result, we have no revisions to report for our Research Summary.

**Change Log – Milestone 7: Final Vision and Scope**
--------------------------------------------------------

**1. Objectives and Key Results (OKRs)**
*   **Updated Objective 1, Key Result 1** to clarify specific MVP features required for a “fully functional” course registration system. Feedback from TA suggested adding feature-level detail to ensure alignment on MVP definition.

**2.** **User Story** #43 **
*   **Revised Acceptance Criteria** to specify:
    *   Which user roles have access to departmental dashboards (e.g., Department Chairs, Associate Chairs, Program Coordinators).
        
    *   The data fields used for department vs. university comparisons (e.g., course fill rate, enrollment totals, course completion statistics).
        
*   Change made in response to TA feedback requesting greater specificity.

**3. Risks, Assumptions, and Dependencies**
*   **Adjusted visual formatting** to properly indent nested bullet points for improved readability. This was a minor presentation fix based on TA feedback.

**4. Roadmap**
*  **Added more specificity** to roadmap by including all 8 features main features to implement rather than only 3. This allowed us to get more indepth with the roadmap and show in more detail what each iteration and quarter would offer in terms of feature rollout goals, and other supporting tasks.
* **Broader goals focus** to show what accomplishments should be occuring each quarter rather than focusing on what each feature's goals should be in that quarter to give a more broadstroke overview of the development process
* **Timeline and overview modification** to better align with real development cycles and to give a more accurate estimate of development time and how feature rollout would occur chronologically

**5. Data Flow Diagram**
![截屏2025-06-08 下午10.41.41.png](/.attachments/截屏2025-06-08%20下午10.41.41-b8adc89b-fe45-42d2-840d-c76d82df4951.png)
**Data Flow Diagram (DFD) Enhancements**
*   **Decomposed Level 0 process into Level 1 subprocesses**  
    Split the original “Search and Filter Courses” process into clearly defined subprocesses:
    *   1.1 Receive Search Request
        
    *   1.3 Match Against Preferences
        
    *   2.1 Save to My Plan
        
    *   3.1 Submit Plan to Advisor
        
    *   3.2 Advisor Feedback
        
*   **Added advisor interaction and feedback loop**  
    Introduced a new external entity, “Advisor,” and added processes 3.1 and 3.2 to reflect realistic student-advisor planning behavior. This better supports academic guidance and approval workflows.
    
*   **Integrated new data store: My Plan**  
    Added “My Plan” as a data storage layer to support course saving and advisor review workflows, clarifying how student choices are persisted and shared.
    
*   **Clarified and restructured data flows**  
    Improved clarity by relabeling flows (e.g., “Save to Plan,” “Course Selection,” “Feedback”) and making directional logic more explicit.
    
*   **Replaced inferred logic with user-defined preferences**  
    “Filter Criteria” and “User Preferences” are now separate from “Course Catalog,” showing more precise filtering driven by student input rather than embedded in system logic.
    
*   **Improved labeling and visual hierarchy**  
    Renamed and standardized terminology in the diagram for consistency across the Vision & Scope document. Also adjusted layout for better directional flow and readability.

![截屏2025-06-08 下午11.15.19.png](/.attachments/截屏2025-06-08%20下午11.15.19-2f252ff9-f657-4bf5-8a70-e8db052d3fcb.png)
**Data Flow Diagram (DFD) Enhancements – Waitlist for Full Classes**
*   **Decomposed Level 0 process into Level 1 subprocesses**  
    Split the original high-level waitlist functionality into clearly defined subprocesses:
    *   1.1 Submit Registration Request
        
    *   1.2 Add to Waitlist
        
    *   1.3 Notify Student
        
    *   1.4 Send Email Notification
        
    *   1.5 Advisor Manual Notification
        
*   **Added advisor interaction and manual intervention support**  
    Introduced a new external entity, “Advisor,” and process 1.5 to reflect manual handling of escalated waitlist cases. This acknowledges scenarios where advisor input is necessary to override or clarify waitlist status.
    
*   **Integrated new data store: Waitlist Records**  
    Added a dedicated “Waitlist Records” data store to log student entries, timestamps, advisor adjustments, and notification status. This enables traceability and audit readiness.
    
*   **Expanded and separated notification flows**  
    Divided student communication into two processes: 1.3 handles in-system waitlist status updates, and 1.4 handles timed confirmation emails. This reflects a multi-channel communication strategy and ensures compliance with NFRs.
    
*   **Refined data flow logic for automation and escalation**  
    Relabeled data flows to clearly distinguish between registration input, system-determined actions, and advisor-triggered responses (e.g., “Escalated Waitlist Review,” “Status Update”).
    
*   **Standardized terminology and layout for consistency**  
    Harmonized process labels and entity names with other DFDs in the system (e.g., using consistent naming for "Student", "Advisor", and "Course Catalog") to improve readability and maintain consistency across the Vision & Scope documentation.
