---
layout: single
title: "Item Process"
permalink: /manual/item/
author_profile: false
sidebar:
  nav: "manual"
---
## Goal
The goal of the item process is to provide the required materials, in the required quantity at the required time to it's customer.

## SIPOC
**Supplier:**  
Steel vendors

**Inputs:**  
Kanban cards detailing shape, material grade and quantity

**Process:**

```
|--- Requested
|--- Cut
      |--- Cutting
            |--- Waterjet
            |--- Saw
            |--- Shear
            |--- Manual
      |--- Cutting done
|--- Form
      |--- Forming
            |--- Bend
            |--- Roll
            |--- Machine
      |--- Forming done
|--- Done
```

**Outputs:**  
Items ready for fit-up in steel assemblies and material traceability records (if applicable)

**Customers:**  
The main customer of the item process is the product process, but might also include department 61 Workshop or the end customer
