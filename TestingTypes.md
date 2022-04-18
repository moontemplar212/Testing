# Testing Types

## Functional Testing

### Unit testing:
  * Individual units / modules / functions of code action

Unit testing is the most basic form of testing where single functions usually with one or a few inputs and a single output are tested to make sure they meet requirements specifications and documentation. What differentiates this type of testing from others is that functions should be tested in isolation without any dependancies or interactions outside of it's own scope. This enables confirmation that the function works as intended by itself.

> **Example**
><br>
><br>
> function (a, b) {<br>
> &ensp; return a + b;<br>
>}<br>

The above function is a simple sum of two elements a and b. The scope of the function is that it takes two inputs and returns one output. There are no outside dependencies such as global variables or reliance on other functions.

Unit testing tends to be simple as it only deals with single functions.

### Integration testing:
  * Groupings of individual code actions

Integration testing is the most basic type of testing after unit testing where two or more functions are combined and tested together. The interaction of groups of functions when combined together gives this testing type it's name and scope. Integration testing is where the fun begins in terms of testing where many and complex interactions start to emerge due to the reliance on external actions for inputs and outputs instead of simple inputs and outputs. Indeed, external actions which might not be under direct control can have wide and unintended consequences when modified. When components begin to be integrated the principle of defect clustering is a powerful technique to utilise, as many defects can be discovered at once and together to reduce the overall testing load and focus testing effort.

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