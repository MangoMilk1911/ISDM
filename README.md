# Assignment 1 - Analysis, Planning, Architecture, & Design

## Group
**Tut 07 Juan 12:00pm**\
Oliver Sarker (13636838)\
Leon Salsiccia (13550494)\
Olivia Pham (13634124)\
Sam Stephens (13027216)


## Project Objectives
The goal of this project is to address the existings problems surrounding the current operations of the Call Management Center, and suggest an improved solution in the form of a new information system. The suggested solution will further enable the Call Management Center in its ability to manage customer enquiries and calls, and Relationship Managers in making holiday package sales. Additionally, the new system will allow the travel company to target potential customers or retarget existings customers as a result of the improved information processes.

## Problem Definition
The Call Management Centers current operations are impacted due to the high number of holiday packages and difficulties in effectively converting customers to make a purchase. These problems include; unnacceptable wait times for customers, Relationship Managers lack of information regarding the customer or their interested holiday package, and inefficiency in redirecting customers to Relationship Managers who are able to help. This has resulted in slow call rates, organisational resource wastage and negative customer relationship with the company. Relationship Managers are not able to fully understand customer intentions resulting in customers being redirected multiple times or simply hanging up.

## Stakeholders
1. **Inbound Call Customer:** Customers calling the travel company to purchase or get information about a travel package
2. **Outbound Call Customer:** Potential customers called by the travel company
3. **Relationship Manager (RM):** Employees who talk to to customers over the phone
4. **Call Centre Manager:** Manager of the department within the travel company that handles both inbound and outbound calls
5. **Travel Company:** The major travel company who maintains the call management centre

## Design Thinking
### Empathy Maps
**Inbound Call Customer**
<img src="Empathy Maps/Empathy Map - Inbound Customer.png" width="100%">
**Outbound Call Customer**
<img src="Empathy Maps/Empathy Map - Outbound Customer.png" width="100%">
**Relationship Manager**
<img src="Empathy Maps/Empathy Map - Relationship Manager.png" width="100%">

### POV Statements
1. Relationship Managers need to be routed to potential customers based on skill levels and best match so the number of calls RMs have to take is reduced. (Might need rewording)
2. Outbound customers need to be matched with a Relationship Manager who is best fit to discuss the proposed product for the customer.
3. Inbound customers need to be matched with Relationship Managers according to their inquiry so they can recieve help and purchase a travel package more efficiently.

### Design Approach Reflection
This development project began with reading over the assigned case study and applying to it the first stage of Design Thinking: Empathise. From the disucssion topic we defined the stakeholders involved with and affected by the implementation of a travel company call routing system. 

We created empathy maps for the major stakeholders who we believed would be most affected and have the most perspective on the changed system. Our empathy maps were created for inbound and outbound customers and the call management centre Relationship Managers. Alongisde our empathy maps we created corresponding POV (point of view) statements which defined the stakeholders' needs and perspectives in relation to the call system. 

From the empathy maps and POV statements, we've been able to define the problem as part of stage 2 of the Design Thinkng process. We've determined that for customers, it is important to decrease wait time for calls and for them to be matched with an RM suited to their needs and questions. For RMs, it is important to be well matched with customers to best address their needs.

Following this we developed 'How might we?" (HMW) questions. These questions are shaped from our POV statements and frame our brainstorming and ideation phase:

#### HMW (How Might We) Questions
1. How might we improve customer retention and satisfaction.
2. How might we increase the rate of calls.
3. How might we increase the quality of our Relationship Managers' service.
4. How might we better consolidate our customer profiling tools.

We then listed our assumptions that were not explicitly stated in the case study:

#### Assumptions
* The user profile is created with a Profiler Tool via the travel company website.
* The user provides their profile ID during the call to identify them.
* Outbound Customers are contacted based on RM Skill matrices and product knowledge.
* Outbound Customers have an existing profile with the Travel Company.
* A booking can only include a single holiday package.
* Inbound calls from new customers without a profile will require them to declare the intent of their call via speaking to an AI assistant. Once intent is known, the new customer can be routed to an apprioate RM.
* All inbound calls are filtered by the new system.
* All outbound calls performed by RMs are taken from their target list.
* The Interactive Voice Response unit will redirect the customer once an appropriate Relationship Manager is available.
* The target customer list is generated and used in the backend. RMs simply initiate the outbound call which is dialed automatically by the system according to the target list.
* Relationship Managers will book the holiday package on behalf of the customer.

Applying the initial stages of Design Thinking to this project has allowed us to better understand the project scope, our design objectives and empathise with our stakeholders' needs and wants. Design Thinking stages 1 and 2 have set a foundation for us to proceed with the prototyping and modelling stage of our project. Understanding our objectives has helped us to create and prioritise our backlog, which is managed using *Issues* on GitHub (See Backlog section below).

## Agile Development Methodology
### SCRUM Reflection
* Sprints
* SCRUM cycle
* bi-weekly meets every tuesday and friday
* Incremetally work on tasks in order to copmlete the report
* Kanban board (Sprint Backlog)
* Highlights progression throughout the report
* Assign tasks using github issues

### Backlog
| US | As a                 | I want to                                                             | So that I                                                        | Priority |
|:--:|----------------------|-----------------------------------------------------------------------|-------------------------------------------------------------|:--------:|
|  1 | Inbound Customer     | be able to quickly purchase a holiday package                         | can go on holiday                                           |   High   |
|  2 | Inbound Customer     | receive quick and sound advice/options on travel options              | can make an informed decision on the travel options         |  Medium  |
|  3 | Inbound Customer     | be directed to a employee quickly                                     | spend less time waiting on hold                             |  Medium  |
|  4 | Inbound Customer     | be able to provide my customer ID                                     | can be served based off my previous purchases and interests |   High   |
|  5 | Inbound Customer     | be able to explain why I'm calling                                    | am directed to someone who can help faster                  |    Low   |
|  6 | Outbound Customer    | only receive calls about packages I would be interested in            | don't have my time wasted                                   |  Medium  |
|  7 | Outbound Customer    | be able to opt out of getting calls                                   | don't get spam calls                                        |    Low   |
|  8 | Outbound Customer    | be recommended packages based off my interests                        | find new places to go on holiday                            |   High   |
|  9 | Relationship Manager | be matched with potential customers based on my skills                | can best address their needs and interests                      |   High   |
| 10 | Relationship Manager | be able to view customers details quickly                             | have the necessary information when selling a package       |    Low   |
| 11 | Relationship Manager | be able to contact potential customers according to my knowledge      | can sell holiday packages more efficiently                      |  Medium  |
| 12 | Relationship Manager | have a dialogue script generated per call                             | easily provide the necessary information to the customer    |  Medium  |
| 13 | Relationship Manager | be connected to customers more likely to purchase                     | don't waste time on customers who won't purchase            |   High   |
| 14 | Call Centre Manager  | ensure the system uses AI to interact with customers                  | can more easily manage inbound call performance                 |    Low   |
| 15 | Call Centre Manager  | ensure the rate of calls is manageable                                | ensure RM's aren't over worked                              |  Medium  |
| 16 | Travel Company       | retarget existing customers with new packages                         | make more sales                                             |   High   |
| 17 | Travel Company       | target potential customers with offers that would best appeal to them | can make more sales                                             |   High   |
| 18 | Travel Company       | ensure our most loyal customers to be prioritised and served first    | can uphold a higher customer reputation                     |  Medium  |

## RUP Models
### Use Case Diagram

### Activity Diagram
<img src="Diagrams/Activity Diagram Profiling FINAL.png" width="100%">
<img src="Diagrams/Inbound Activity Diagram FINAL.png" width="100%">
<img src="Diagrams/Outbound Activity Diagram FINAL.png" width="100%">

### Class Diagram
A class diagram was created to illustrate the proposed system's classes including their properties, functionalities and relationships. The class diagram below is a combination of the proposed information system along with the base system which it was built upon. We have colour coded the new aspects of the system blue, making it easy to determine new functionality that was added by the information system.

The class diagram undertook multiple iterations before we were satisfied with the result. This was due to the group being unsure what aspects of the system needed to be modelled. We also weren't sure what should be modelled as a class or as a method. We decided to model the new systems functionality across a combination of new classes and new methods in order to create a model we thought provided excellent depth while maintaining legibility.

<img src="Diagrams/Class Diagram FINAL.png" width="100%">

### Collaborative Diagram
A collaborative diagram is a visual representation to illustrate the interaction between objects within a given use case. The diagram highlights the structure of interactions.

The collaborative diagram was originally a single illustration, however, due to the structure of the Travel Compnany and how calls are distributed between differing customers, the diagram was divided into two diagrams, Inbound and Outbound customers. Each diagram below shows the structure of a given call and transaction that occurs between a Relationship Manager and a Customer.

#### Inbound
<img src="Diagrams/Inbound Collaborative Diagram FINAL.png" width="100%">

#### Outbound
<img src="Diagrams/Outbound Collaborative Diagram FINAL.png" width="100%">

## Project Evaluation
### Competitive Advantage

The new system proposed to the Travel Company will improve the efficiency of the transaction that occurs between a Customer and Relationship Manager. By improving on the automatic rerouting system of inbound custoemrs, the throughput of customers can be maximised and simultaneously relieve company resources and Relationship Managers workloads, uiltimately leading to a greater number of customers and therefore sales and maximise revenue for the Travel Company. By streamlining the process of rerirecting customers, customers experience a shorter wait time with the automatic rerouting system. On a similar note, the automatic rerouting system is self-sufficient and thus is scalable for any number of incoming calls regardless of how many Relationship Managers are available.
  
Moreover, through the Outbound calling system, by targetting customers, there is an improved Customer/Relationship Manager experience, further increasing the potential of the customer purchasing a package.

### Possible Issues

Although there are a many advantages that come with an improved transaction between Customers and Relationship Managers, the Travel Company may suffer from a few short term set backs during implementation of the improved system itself. During any project there will be an increse in financial costs that will hinder wider aspects of the Travel Company. Moreover, as a project progresses, there may be a change in requirements causing delays, inefficient allocation of labour, a shift in resource allocation and a further increase in financial costs. Another issues could be resistance from Relationship Managers, whom may be unwilling for change and therefore require training costs to train the Relationship Managers to effectivly utilise the new system.

A more long term issue could be complete misallocation of resrouces during or after the project could lead to project failure leading to tarnishing of brand reputation or possible future prospects for the business.  
