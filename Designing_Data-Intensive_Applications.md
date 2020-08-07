# Designing Data-Intensive Applications by Martin Kleppmann

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
* "The main arguments in favor of the document data model are schema flexibility, better performance due to locality, and that for some applications it is closer to the data structures used by the application. The relational model counters by providing better support for joins, and many-to-one and many-to-many relationships." (pg. 38)
* "*Document databases* target use cases where data comes in self-contained documents and relationships between one document and another are rare. *Graph databases* go in the opposite direction, targeting use cases where anything is potentially related to everything." (pg. 63)
* "One thing that document and graph databass have in common is that they typically don't enforce a schema for the data they store, which can make it easier to adapt applications to changing requirements. However, your application most likely still assumes that data has a certain structure; it's just a question of whether the schema is explicit (enforced on write) or implicit (handled on read)." (pg. 63)

## Chapter 3 - Storage and Retrieval
