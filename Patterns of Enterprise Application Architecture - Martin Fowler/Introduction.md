# Introduction
## Architecture
- "Highest-level breakdown of a system into its parts"
- aka "decisions that are hard to change"
- a shared understanding of a system's design by the expert developers on a project
    - in the form of *major components of the system and how they interact*

## Enterprise Applications

Examples:
- Payroll
- Patient records
- Shipping tracking
- Cost analysis
- etc.

### Enterprise applications usually involve **persitent data**
- Data is persistent because it needs to be around *between multiple runs of the program*
- Also, during its lifetime, there will be changes in the programs that *use* it.

### Enterprise applications usually have **a lot of data**
- Modern systems usually use *databases*, mostly relational databases.


### Enterprise applications usually have many people **access data concurrently**
- With # of people, there are *issues* to make sure that all can *access the system properly* 
- In simplest terms, there needs to be a system in place to ensure that *two people don't access the same data at the same time* in a way that causes errors

### There's usually **a lot of user interface screens**
- Data has to be presented *lots of different ways* for different purposes.

### They usually need to **integrate with other enterprise applications**

## Kinds of Enterprise Application