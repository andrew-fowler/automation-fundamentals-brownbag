# System Test Automation
## Fundamentals

---

## What is it?
_Automated checking that things that were previously known to be true, still are._

Note:
As opposed to testing, which looks to surface new information.
---

## What is it for?
_A low execution-cost way to learn information about the health of the build_

Note:

---

## Why do it?
_Properly built and maintained test automation helps you to change with confidence, and so change at speed._

---

## Context: Test Pyramid

![Image of test pyramid](http://blog.primehammer.com/wp-content/uploads/2017/02/image02-300x259.png)

Note:
The test pyramid is a model often used to describe different things.
The most useful way to think of it is to see it as illustrating dimensions of isolation, and confidence.
Isolation is proportional to determinism and speed of execution.
Isolation is inversely proportional to system confidence.

  - Integration testing in the large/small
  - How it relates to API testing
  - Q: What’s the difference between system and acceptance testing?

---

#### Fundamental Principles

## Stability > Performance > Coverage

Note:
High coverage but poor performance results in tests that aren't ran as there's too much time friction.
High performance but poor stability results in tests that aren't ran as they're too expensive to extract information from.

It's better to have one stable and performant test that many tests that are slow and / or unstable.
---

#### Fundamental Principles

## Signal : Noise

---

## Design pattern/s

  - Basic 3 layer
    - Test specification 
    - User behavior 
    - System abstraction 

  - Q: What about BDD/Tools?

---

## Workflow
  - Capturing scenarios
  - Building the abstraction
  - Proving code
  - Proving compatibility
  - Proving stability
  - Local execution vs Remote execution

---

## Common pitfalls
  - Degradation
  - Silo’d ownership
  - Over reliance
  - Over engineering

---
## Webdriver Overview

  - Selenium webdriver project
    - Spec
    - Bindings
    - Server 
      - Infra
    - Drivers

---

## Known Issues
  - Driver immaturity
  - Remote execution performance
  - Notable absences from specification
