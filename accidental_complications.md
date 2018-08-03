Status: draft

# Accidental Complications

- what are accidental complications?
	- out of the Tar Pit: not ideal
	- not black and white
	- everything that keeps you from working on your task that is not intrinsic to the task
	- in the end it's a personal choice
	

## The List

### Segregation

Ease of switching between execution and authoring environments.

**Bad**: Usually completely different environments. Especially no clear path from execution to authoring. Example: C, Java

**OK**: Different but close environments. Example: Python, PHP

**Good**: Possible to do non-permanent changes in execution environment. Example: Web

**Excellent**: Signle environment. Example: Smalltalk


### Set-Up

Getting from zero to authoring.

**Bad**: Platform costly to acquire or requiring expert knowledge to install. Example: MatLab

**OK**: Not free or cumbersome installation. Example: Python

**Good**: Free download and simple installation. Example: Java, PHP

**Excellent**: Usually no set-up required or free download without installation. Example: JavaScript, Scratch, Smalltalk


### Dependencies

Managing thrid-party modules and services.

**Bad**: Manual download and management necessary. Example: MatLab

**OK**: Services must be downloaded and managed but tool support is common. Example: JavaScript

**Good**: Direct access without installation but usually requires authentication. Example: Web

**Excellent**: Services can be directly accessed without installation or authentication


### Syntax

Burden of learning a specific syntax.

**Bad**: Diffuclt to learn, no support. Example: C, Perl, Java, JavaScript

**OK**: Difficult to learn but good feedback. Example: Java + IDE

**Good**: Easy to learn with quick and precise feedback on errors. Example: Haskell + IDE (?)

**Excellent**: No syntax needs to be memorized. Example: Scratch


### Comprehensibility

Ease of understanding someone else's software in order to learn its model or modify it.

**Bad**: Source code usually not available. Example: Java (JAR), C (EXE)

**OK**: Source code is usually available, but not well structured. Example: Python, PHP, JavaScript

**Good**: Code is usually well structured and categorized. Dynamic behaviour can be explored. Example: Smalltalk

**Excellent**: Focus on comprehensibility, not executability. Example: Eve


### State Visibility

How easily runtime state can be examined and visualized.

**Bad**: Execution state not accessible. Example: Java (JAR), C (EXE)

**OK**: Debugger or logging required but usually possible. Example: Python, C

**Good**: All state accessible through execution environment. Example: Smalltalk, JavaScript

**Excellent**: All state visualized during execution and authoring.


### State Volatility

How easily execution state is lost.

**Bad**: It is very difficult to persist state. Example: C

**OK**: Good support for persisting state. Example: JavaScript

**Good**: Execution state is always persisted. Example: Smalltalk

**Excellent**: State is always persisted and can be shared between different executions.


### Service Discovery

Finding useful third-party services.

**Bad**: Very difficult to discover anything

**OK**: Context switch for discovery usually necessary. Example: JavaScript

**Good**: In-context discovery of functionality and usage common, good documentation of existing services

**Excellent**: built-in discovery of service functionality and usage, and new services


### Protocol Discovery

Ease of discovering how a computational module is used.

**Bad**: Example: C

**OK**: Example: Smalltalk

**Good**: Example: Java + IDE

**Excellent**: Dynamic discovery and experimentatin while authoring.


### Platform Lock-In

How easy it is to use software written in other languages.

**Bad**: Usually not possible. Example. JavaScript

**OK**: Requires serialization but simple and common. Example: Web

**Good**: Foreign function interface exists for many platforms.

**Excellent**: Any software written in any language can easily be used.


### Serialization

Need for and ease of serialization

**Bad**: Complicated serialization causing much frustration

**OK**: Good tool support for serialization, standardized formats exist

**Good**: Little serialization neccessary, usually automated

**Excellent**: Serialization completely automated


### Interpretation



**Bad**: 

**OK**: 

**Good**: 

**Excellent**: 


### Information Fragility

Risk of losing software (program or data)

**Bad**: Manual data management, tools uncommon

**OK**: Third-party tools available and common

**Good**: Built-in tools for data safety

**Excellent**: Almost impossible to lose data


### Sharing

Giving access to your software to somebody else

**Bad**: Very unlikely to access without considerable effort

**OK**: Receipient must meet certain criteria and expand some effort

**Good**: Very likely to access and well-defined group

**Excellent**: Extremely likely that any receipient can access software with almost no trouble


### Security

Protection of identity and information

**Bad**: No built-in security measures

**OK**: Unreliable security, breaks are common

**Good**: Effective security, very rare breaks

**Excellent**: Very secure against technological and social attacks, no single point of failure


### Autonomy

Dependencies on others

**Bad**: Depends completely on single, private authority

**OK**: Controlled by private authority, permission likely to be granted

**Good**: Controlled by public authority, permission always granted

**Excellent**: No permission required, not controlled by anyone
