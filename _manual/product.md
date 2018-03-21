---
layout: single
title: "Product Process"
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

### Inputs
Under normal circumstances work should not start without *full kit* consisting of:

#### Kanban cards
Cards shall provide information regarding:  
* What does the customer want - specification & drawing  
* When does the customer want it - due date  
* What amount does the customer want - quantity  
* Product routing  

#### Items
The product process shall receive all the neccessary items required to build the product from the **item process**.

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

### Outputs

### Customers
