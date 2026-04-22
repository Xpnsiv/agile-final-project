---
name: User Story
about: User Story
title: ''
labels: ''
assignees: ''

---

**As a** Inventory Manager  

 **I need** the ability to delete a product from the catalog  

 **So that** I can remove items that are no longer being sold  

   

 ### Details and Assumptions

 * Deletion might be "soft" (archived) or "hard" (removed from DB).
   

 ### Acceptance Criteria  
 

 ```gherkin```

Given a product "Old Phone" exists

When I select the option to delete this product

Then the product should no longer be visible in the public catalog
