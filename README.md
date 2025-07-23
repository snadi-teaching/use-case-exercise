# Use Case Exercise

Exercise for fleshing out user stories into detailed use case specifications with main and alternative flows 


## Task

Your are building a university registration system and are given the following user story:

**As a student, I want to register for a course in an upcoming term.**

Flesh out the above user story into a detailed use case specification. Your use case should have the following sections:

- **Use Case Name**
- **Primary Actor**
- **Preconditions**
- **Main Success Scenario (Basic Flow)**
- **Alternative Flows/Extensions**
- **Success Guarantee/Postconditions**

## Sample solution

- **Use Case Name:** Register for Course  
- **Primary Actor:** Student  
- **Preconditions:**  
  - Student is logged into the system  
  - Registration period is open  
  - Student does not have a registration hold  

- **Main Success Scenario:**  
  1. Student navigates to the course registration page  
  2. System displays available courses  
  3. Student selects a course from the list  
  4. System checks:
     - Course availability (not full)
     - Student eligibility (prerequisites met)
  5. System registers the student in the selected course  
  6. System updates enrollment data and confirms registration  

- **Alternative Flows:**  
  - **4a. Course is full:**  
    - System displays a message and offers to join the waitlist  
  - **4b. Prerequisites not met:**  
    - System informs the student and blocks registration for that course  

- **Postconditions:**  
  - Student is enrolled in the selected course  
  - Course seat count is decremented  
  - Registration appears in student’s dashboard  

