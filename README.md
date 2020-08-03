# Recruitment-Database
**Recruitment Database for the Human Resource Department of a Company**

1. **Problem Statement**
2. **ER Diagram**
3. **Entity Relationship mappings**
4. **Tools used**

**Problem Statement**

This project is built to implement the Recruitment database for the Human Resource (HR) Department of a company. The project includes design implementation and testing of the database for a company to maintain the data of each candidate who applies for any job role in the company. The design is implemented to handle the data from the application till the onboarding process for each candidate applied to the company. I have created relevant tables to this application which holds relevant information on the candidates, jobs, applications, interviews, interviewers, onboarding, Reimbursement Status and several others accordingly. All the tables and data are compared to the real-world application of the Recruitment database in any company and appropriate relationships are established in the design.

**ER Diagram**

![](RackMultipart20200803-4-4ynn0v_html_479c1fde05aa1727.png)
  
The design of the database is depicted using the crow&#39;s foot entity relationship model that is divided into 6 parts according to the data entities.

1. Jobs.
2. Recruiters application evaluation and status.
3. Applications, applicant and document
4. Reimbursement
5. Interviews and Feedback
6. Onboarding and Blacklisting.

**Relationships between Tables:**

1. Department to Job: One-to-Many
2. JobOpenings to Job: One-to-Many
3. Candidate to Application: One-to-Many
4. Candidate to CandidateAddress: One-to-One
5. Application to ApplicationDocument: One-to-Many
6. Document to ApplicationDocument: One-to-Many
7. Application to Document: Many-to-Many
8. Job to Application: One-to-Many
9. Application to HotelReservation: One-to-Many
10. Application to AirLineReservation: One-to-Many
11. Application to CarRental: One-to-Many
12. Application to ReimbursementStatus: One-to-Many
13. Application to OnsiteInterview: One-to-Many
14. Application to OnlineInterview: One-to-Many
15. ApplicationStatus to ApplicationStatuschange: One-to-Many
16. Interviewer to OnlineInterview: One-to-Many
17. Interviewer to OnsiteInterview: One-to-Many
18. Application to OfferAcceptanceStatus: One-to-Many
19. OfferStatus to OfferAcceptanceStatus: One-to-Many

**Tools used:**

1. Microsoft SQL Server Management Studio.
2. Vertabelo for ER diagram representation
