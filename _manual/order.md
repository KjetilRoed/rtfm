---
layout: single
title: "Order Process"
permalink: /manual/order/
author_profile: false
sidebar:
  nav: "manual"
---
## Goal


## SIPOC
**Supplier:**  


**Inputs:**  
Under normal circumstances work should not start without the following:
*Kanban cards*  
Cards shall provide information regarding:  
* Product routing
* Requirements to welding
* Drawing no.
* Quantity  

*Items*  
The product process shall receive all neccessary items from the **item process**.


**Process:**

```
|--- Requested
  |--- New requests
  |--- Waiting for items
  |--- Ready to start
|--- In progress
  |--- Welding
  |--- Ready for inspection
  |--- Inspection
  |--- Ready for testing
  |--- Testing  
  |--- Ready for external services  
  |--- External services  
|--- Done
```

**Outputs:**  


**Customers:**  
