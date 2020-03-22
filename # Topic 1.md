- [Topic 1 System Fundamentals](#topic-1-system-fundamentals)
  - [1.1.2 Change management](#112-change-management)
  - [1.1.3 Legacy systems](#113-legacy-systems)
  - [1.1.4 Client hardware implementation vs SaaS](#114-client-hardware-implementation-vs-saas)
  - [1.1.5 Types of conversions:](#115-types-of-conversions)
  - [1.1.6 data migration](#116-data-migration)
  - [1.1.7 Testing:](#117-testing)
  - [1.1.8 User documentation](#118-user-documentation)
  - [1.1.9 Types of user documentation](#119-types-of-user-documentation)
  - [1.1.10 User training methods](#1110-user-training-methods)
  - [1.1.11 Data loss](#1111-data-loss)
  - [1.1.12 Consequences of data loss](#1112-consequences-of-data-loss)
  - [1.1.13 Prevention of data loss](#1113-prevention-of-data-loss)
  - [1.1.14 managing releases](#1114-managing-releases)
  - [1.2.1 Definitions](#121-definitions)
  - [1.2.2 Network roles](#122-network-roles)
  - [1.2.3 Social/ethical issues](#123-socialethical-issues)
  - [1.2.4 Stakeholders](#124-stakeholders)
  - [1.2.5 Data from stakeholders](#125-data-from-stakeholders)
  - [1.2.6 Data gathering](#126-data-gathering)
  - [1.2.7 Illustrations](#127-illustrations)
  - [1.2.8 Prototypes](#128-prototypes)
  - [1.2.9 Iterative design process](#129-iterative-design-process)
  - [1.2.10 Involve end users](#1210-involve-end-users)
  - [Know some social and ethical issues](#know-some-social-and-ethical-issues)
  - [1.2.12 Usability](#1212-usability)
- [Vocabulary](#vocabulary)

# Topic 1 System Fundamentals

## 1.1.2 Change management
- Change management
  - requires training
  - recruitment concerns
  - compatibility concerns
  - dependencies

## 1.1.3 Legacy systems

> Legacy system - an old technology/computer system; often inherited from another company during merger

## 1.1.4 Client hardware implementation vs SaaS

- Mergers can cause compatibility issues
- Legacy systems are not replaced because:
  - too costly
  - users are comfortable
- In house vs outsourced pros/cons
  - initial cost
  - technical skill required
  - ongoing costs
  - full vs partial control
  - security risk

> SaaS - software distribution model; third party hosts applications over the internet - software as a service; remote hosting of data; remote processing; cheaper setup cost; data managed remotely; 

## 1.1.5 Types of conversions:

|Parallel running|Pilot running|Phased conversion|Direct Changeover|
|---             |---          |---              |---              |
|Old and new at the same time|New system used by a small group|Going from old to new system in steps|Flicking the switch|
|Low Risk because old system is still there|Low risk|Low risk because each phase implies a small change|High risk|
|Needs extra employees|Risks that system problems won't be discovered; cheaper than running in parallel|Not always possible|Low cost|

## 1.1.6 data migration
>Data Migration: moving data from one system to another; can cause compatibility issues; **conversion** process for data

## 1.1.7 Testing:

- Debugging - ongoing during development
- Alpha/Beta testing - done by future users on an almost complete system
- White-box testing - from the POV of the programmer, who knows what it does and how
  - Con - subconscious bias of input, Pro - more coverage of codebase/functionality
- Black-box testing - testing the system; POV of user; no knowledge of what it does/how
  - More genuine input/realistic; less coverage of the codebase because the user has no idea what it does
- Unit-testing - testing components/modules separately; testing individual units
  - Every component is tested, nothing overlooked; con - doesn't test the system together
- System-testing - testing the whole system
  - Less easy to ensure all components are tested
- Acceptance testing - last testing phase before sign-off by the user
- Automated testing - using a computer/software to test the product

## 1.1.8 User documentation

- Facilitate changeover
- Less wordy/technical than system documentation

## 1.1.9 Types of user documentation

Paper copy; Online version; Interactive; Dedicated support call line

## 1.1.10 User training methods

- Groups
- Online/remote
- Support department
- Forums
- Dedicated support phoneline
- Using the final system is preferable

## 1.1.11 Data loss

Malware; disaster; power loss; fire; hardware loss; **user error**; backups needed (offsite)

## 1.1.12 Consequences of data loss

Reputation loss; replacement costs; loss of business

## 1.1.13 Prevention of data loss

- Backups (offsite/online)
- Malware deletion/maintenance
  
> Failover - process of finding primary system failure and switching users to redundant system
> Redundant system - clone/copy of the previous system that can perform the same functions; can be switched to

## 1.1.14 managing releases

- Software life cycle
- Releases; Updates; patches
- Automatic updates

## 1.2.1 Definitions

> Hardware - physical components that make up a computer system
> Software - the data and instruction sets that direct a computer system
> Peripheral - a computer device; adds functionality
> Network - linkages of computers
> Human resources - workers and other soft resources

## 1.2.2 Network roles

> Client - computer system that makes requests to servers on a network
> Server - computer system that responds to client requests
> Router - computer system; on the network; routes packets to appropriate clients
> Firewall - rules which limit data or packet transmission across a network (based on ports or source/destination, etc)

## 1.2.3 Social/ethical issues

## 1.2.4 Stakeholders

End users; customers; shareholders; unions; community; etc.

## 1.2.5 Data from stakeholders

Interviews; Direct observation; surveys

## 1.2.6 Data gathering

Examine system; competing product comparison; organizational issues; look at previous solutions to similar problems, adapt them.

##  1.2.7 Illustrations

Data flow diagrams; <mark>Systems flowcharts</mark>; structure diagrams (division of problems into smaller ones)

## 1.2.8 Prototypes

Client feedback; easy to understand; reduction of costs; is the solution appropriate

## 1.2.9 Iterative design process

Issues/new requirements/improvements can come up after systems implementation; 

Needs assessment → Design specs → Development → Implementation → Support → Evaluate

## 1.2.10 Involve end users

Users provide specs

## Know some social and ethical issues

- E-waste
- Power consumption
- Pollution
- Automation takes jobs
- Overdependence
- Addiction
- War
- QoL improvements
- Robots do dangerous work

## 1.2.12 Usability

> How easy to learn and use a system is

# Vocabulary

Hardware: collection of physical components
Software: computer programs/libraries
Peripheral device: an auxiliary device communicating with the computer
Computer network: a combination of hardware and software to transport data
HR: personnel workers in an organization

Client: computer system/software that requests a service from a server on the network
Server: computer system/software application that provides a service the other computer systems on the network
Email Server: A computer on a network dedicated to sending mail
Domain Name System Server: Translation of domain names and hostnames into IP addresses 
Acceptance testing: done once the software is finished
Router: network device, routes packets between networks to a final destination
Firewall: network security system controlling network traffic

Reliability: Data is unreliable if it is entered incorrectly – confidence in values of a system
Integrity: Completeness and accuracy of stored data
Security: protection from unauthorized access
Privacy: ability for individuals to determine what happens to their data and information
Authenticity: establishment of a user’s identity beyond a reasonable doubt
Intellectual property: ideas, writings, software, etc. which can be protected legally
Surveillance: Use of IT to monitor
Policies: enforceable measures to promote usage
Standards and Protocols: technical rules and conventions; ensure compatibility and interoperability
Digital Citizenship: responsible, ethical, legal approach

Stakeholders: individuals, groups, teams with an interest in the realization/outcome of a project

Interviewing Stakeholders: Allows you to be aware of things you hadn’t thought of, unlike a restricted survey
Questionnaires: unambiguous responses, closed/open format questions, 
Direct Observation: requires in situ, unbiased, time consuming, con: Observer Bias

Examining Current systems: Determine needs, satisfaction, documents, modeling
Analysis of Competing products: strengths and weaknesses, new ways to achieve
Examine Organizational Capability: a team of resources must work together

Data Processing: collection and manipulation of data to produce information
Batch Processing: similar jobs/tasks grouped together
Online Processing: User communicated directly with the system
Real-time processing: processed in real time (alarm system in hazard)
Flowchart: diagram representing algorithm, workflow, process showing steps and boxes of different kinds
Data flow diagram: graphical representation of flow of data through an information system
Structure chart: squares representing different modules of the system, modular design tool (top down) Open circles: data Closed Circles: data coupling for end of file

Prototyping: simpler model of a system to check functionality/requirements
Validation: confirmation a product meets design function (correct system?)
Verification: confirmation that it meets specifications (built correctly?)
Data validation: evaluate data input following limits and ranges
Data verification: checking data at the source is the same as inputted data

System life cycle model: process from idea to delivery of product to client
Analysis (feasibility report)-Design(Iterative design)-Development-Implementation+support-Maintenance(improvements, updates)
Waterfall methodology: linear process, step by step, best for low likelihood of major changes projects
Agile software development: incremental, iterative, changing requirements

End-user must be involved in the process because: scope may be wrong, not suitable for intended use, alpha/beta, features

New IT systems may have ethical issues: addiction, job loss, environment, socialization

Usability: assesses how easy to use user interfaces are
Learnability: time used to accomplish tasks the first time
Efficiency: Task completion time after adjusting period
Memorability: Time, number of clicks, how users adjust
Errors: Number, type, and time needed to recover
Satisfaction: Attitude of users toward applications
Complexity/Simplicity: effort required to find a solution
Effectiveness: completeness and accuracy of reaching a goal
Readability/Comprehensibility: how easily users understand the content presented
Accessibility: ability for everyone regardless of disability to use systems
Ergonomics: designing for people, optimizing comfort and safety

Usability issues: Learnability, efficiency, memorability, errors, satisfaction, accessibility, ergonomics

Impairment: within accessibility, any abnormality of function
Disability: a restriction or lack of ability to perform an activity considered normal

(subtitles, cognitive disabilities, hypersensitivity, limited hand mobility, foreigners, language concerns, wheelchair accessibility, readable text for screen readers by blind people, transcripts of video, documentation in both auditory and written format)

Master file: permanent file holding complete set of data
Transaction file: temporary file used to update the master file with new information

