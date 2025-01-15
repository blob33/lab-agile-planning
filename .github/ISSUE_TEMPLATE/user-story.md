---
name: User Story
about: Describes user stories.
title: ''
labels: ''
assignees: ''

---

**As a** Marketing Manager  
 **I need** list of customers.  
 **So that** I can send promotional mails to them.
   
 ### Details and Assumptions
 * Customers have opted in for promotional mail.
 * We maintain customer details.
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given 100 customers out of 90 have opted-in for promotional emails.
 When I request customer details
 Then I should see 90 customers. 
 ```
