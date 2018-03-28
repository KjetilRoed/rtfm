---
layout: single
title: <i class="fas fa-cubes"></i> Product Process
permalink: /manual/product/
author_profile: false
sidebar:
  nav: "manual"
toc: true
toc_label: Index
toc_icon: list-ol
---
## Goal
The goal of the Product process is to ...

## SIPOC
### Supplier
The main suppliers are:  
* Order process  
* Item process  


---  

### Inputs
Under normal circumstances work should not start without *full kit* consisting of:

#### Kanban cards
Cards shall provide information regarding:  
* What does the customer want - specification & drawing  
* When does the customer want it - due date  
* What amount does the customer want - quantity  
* Product routing  

#### Items
The product process shall receive all the neccessary items required to build the product from the **Item** process.  

---  

### Process
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
<details><summary>Process steps</summary>  
<p>  
**REQUESTED**  
The Requested step gives us information about upcomming work.  
{: .notice--info}

**New requests - Queue**  
Fresh work that enters the process, items have not been started yet.  
{: .notice--info}

**Waiting for items - Queue**  
The items process has started to fabricate the needed items, but are not yet finished.  
{: .notice--info}

**Ready to start - Queue**  
The items process has finished all required items, start when you have capacity.  
{: .notice--info}  

**IN PROGRESS**  
The In Progress step gives us information about our current WIP - work in process.  
{: .notice--warning}

**Welding - Activity**  
Products that have withdrawn *full kit* from the *item stockpile* and started welding.  
{: .notice--warning}

**Ready for inspection - Queue**  
Products waiting for inspection.  
{: .notice--warning}

**Inspection - Activity**  
Finished welded products that are subject to visual inspection & dimensional control.  
{: .notice--warning}

**Ready for testing - Queue**  
Products that have passed inspection and are waiting for testing.  
{: .notice--warning}

**Testing - Activity**  
Products that are subject to further testing outside of the **Construction** system. I.e pressure testing, lift testing etc.  
{: .notice--warning}

**Ready for external services - Queue**  
Products that have been fully tested and accepted and are waiting for external services.  
{: .notice--warning}

**External services - Activity**  
Products that have been sent to external service providers. I.e non-destructive testing & surface treatment.  
{: .notice--warning}  
---  
</p>  
</details>  
### Outputs
The expected output from the **Products** process consists of:  
* Products without any quality related issues regarding:  
  - Dimensions and parts - we are sure it will fit  
* Documentation that validates that all requirements have been met regarding:  
  - Welding traceability  
    *we know how it was welded and by whom*  
  - Welding operator qualifications  
    *we know how to weld it*  
  - Non-destructive testing records  
    *we know that our welds are free of defects*  
  - Proof testing records  
    *we know our welds and materials will not fail*  
  - Surface treatment records  
    *we know that our product will endure*  

---  

### Customers
The main customer of the *Products* process is the downstream system *Assembly*.  

---
