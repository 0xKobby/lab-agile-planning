---
name: User Story
about: Template for creating user stories e.g. Restock alert for Warehouse Manager
title: ''
labels: ''
assignees: ''

---

**As a** Warehouse Manager  
 **I need** to be able to receive an alert when items in stock fall below a certain number 
 **So that** make request for restocking before goods run out  
   
 ### Details and Assumptions
 * We maintain a database for the e-commerce site
   
 ### Acceptance Criteria  
   
 ```Gherkin
 Given n number of pieces of any particular item on the e-commerce site 
 When n < 50
 Then Warehouse Manger should receive an email alert to request a restock of that item.
 ```
