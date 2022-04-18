# Testing Types

## Functional Testing

Functional testing refers to the testing of the software system against the functional requirements/specifications of that system. This is performed by using an appropriate assortment of inputs to exercise the code functions and compare the outputs against expected outputs. 

### Unit testing:
  * Individual [ units / modules / functions ] actions

Unit testing is the most basic form of testing where single functions or parts of the system, ideally with one ( or a few ) inputs and a single output, are exercised. Functions should be tested in isolation without any dependancies or interactions with other code outside its own function scope. This ensures that the function works as intended by itself.

> **Example**
><br>
><br>
> function (a, b) {<br>
> &ensp; return a + b;<br>
>}<br>

This function sums two elements a and b. The scope of the function is that it takes two inputs and returns one output. There are no outside dependencies such as global variables or reliance on other functions.

Unit testing tends to be simple as it only deals with single functions. The corresponding tests should be short, to the point and self-documenting as the complexity is low.

### Integration testing:
  * Groupings of individual actions

Integration testing occurs mainly when two or more functions or parts of the system are combined and tested together. Many and complex interactions can emerge due to the combination of inputs, outputs and reliance on external actions for inputs and outputs between functions. As actions outside the scope of the function become relevent to that function and hence effect the outcome of that function, unknown or unintendied modifications can cause unintended consequences as testing occurs. A second interpretation of external actions are external dependencies outside the system altogether such as a third party API that might be used within the system under test. Here, even more so than internal combinations, changes of which you have no control over might be implemented and need to be tested to ensure the software is still in working condition. As a general rule, when components begin to be integrated, the principle of defect clustering is a powerful technique to utilise as many defects can be discovered together and works to reduce the overall testing load and focus testing effort.

### Interface testing:
  * Boundaries between parts of a system

Interface testing as the name suggests focuses on the interface between components. More specifically, this can be summarsised as any data migration that goes between two different function scopes. If the migration was inter-function, then most likely the testing could be completed as a unit test. However, when the passage of data takes place over more than one function therein lies an interface between them.

### System testing:
  * Entire code base

### Acceptance testing:
  * User validation of the system

Acceptance testing or User Acceptance Testing (UAT) is a type of testing that takes place at the same level as System Testing whereby the customer or external stakeholder uses the system under test and validates it against a set of pre-defined criteria, most often, the requirements specification document to verify the system is working with given inputs and producing expected outputs as required by the business needs.  

### Regression testing:
  * Checking for regression in parts of the system where changes have been made elsewhere

Regression testing is where most of the time in software testing is spent. Regression as the name suggests checks for reverted behaviour in the system due to other code changes not directly related to the area under test. 

### Alpha/Beta testing: 
  * Testing two version of the same feature

Alpha / Beta testing 

### Confirmation testing:
  * Checking the defect fix produces the correct result

Confirmation testing checks that the bugfix has removed the cause of the defect in the system.

### Sanity testing:
  * High level critical functionality

A sanity test of the system is a high level check that core functionality and components work as expected and in a rational way. Do the components work the way we expect them to?

### Smoke testing: 
  * Brief high level critical functionality

Smoke testing is a brief high level check that core functionality and components work as expected after a new build.  

### Exploratory testing:
  * Non-structured testing

Exploratory testing like the name suggests is a non-structure exploration of the system with no pre-defined checklist or goals to be achieved during testing. Often it is used when the tester has experience and intuition about the system being tested whereby defects are likely to be found in a quicker timeframe than running down a checklist of items one by one.

### Checklist based testing:
  * Structured testing using a list of items

Checklist based testing is a rigorously structured method of testing with a pre-defined checklist of items or goals to be achieved during testing. This type of testing is best used when minimum standards or levels of verification must be met and a record kept. This type of testing 

### Blackbox testing:
  * Not knowing the interal structure of the system

### Whitebox testing:
  * Knowing the internal structure of the system

### End to end testing:
  * Full application pathway

### API testing:
  * abc

### UI testing:
  * Front end browser based elements

## Non-functional Testing

### Performance testing:
  * Platform responsiveness, transaction handling

### Security testing:
  * How secure is the platform

### Compliance testing:
  * Comply with laws, regulations, industry standards

### Localisation testing:
  * Values and timezone specific to region

### Volume testing:
  * How much volume can the platform handle, users, transactions, requests

### Load testing:
  * How much load can the platform handle

### Stress testing:
  * How does the platform respond at peak load

### Destructive testing:
  * How does the platform handle too many transactions, requests

### Usability testing:
  * Is the platform user friendly?

### Portability testing:
  * How portable is the platform to other hardware, software, architectures, platforms?

### Recovery testing:
  * Ability of system to recover from backups, restore points

### Reliability testing:
  * Uptime, how reliable is the platform?

### Maintainability testing:
  * How maintainable is the platform, how easy is it to implement change or fix issues?

### Accessibility testing:
  * Colourblind, epileptic, disabilities

### Browser compatibility testing:
  * How does the platform respond on different browsers

### Backwards compatability testing:
  * How backwards compatable are versions of the platform, do new versions work with older versions?