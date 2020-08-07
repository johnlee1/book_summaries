# Designning Data-Intensive Applications by Martin Kleppmann

## Chapter 1 - Reliable, Scalable, and Maintainable Applications
* "*Reliability* means making systems work correctly, even when faults occur. Faults can be in hardware (typically random and uncorrelated), 
software (bugs are typically systematic and hard to deal with), and humans (who inevitably make mistakes from time to time). Fault-tolerance techniques can hide 
certain types of faults from the end user." (pg. 22)
* "*Scalability* means having strategies for keeping performance good, even when load increases. In order to discuss scalability, we first need ways of describing 
load and performance quantitatively... In a scalable system, you can add processing capacity in order to remain reliable under high load." (pg. 22-23)
* "*Maintainability* has many facets, but in essence it's about making life better for the engineering and operations teams who need to work wih the system.
Good abstractions can ehlp reduce complexity and make the system easier to modify and adapt for new use cases. Good operability means having good visibility into
the system's health, and having effective ways of managing it." (pg. 23)

## Chapter 2 - Data Models and Query Languages
### Relational verses Document Databases
* "The main arguments in favor of the document data model are schema flexibility, better performance due to locality, and that for some applications it is closer to the data structures used by the application. The relational model counters by providing better support for joins, and many-to-one and many-to-many relationships." (pg. 38)

