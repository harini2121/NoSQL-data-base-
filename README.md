# NoSQL-data-base
Learning on NoSQL data base techniqes and implemetation 


SonicLive Case Study 

SonicLive is a UK company that is specialised in hiring out audio equipment to recording artists to be used for the recording, mixing and mastering of music projects such as music tracks and albums. The company is based on 12 recording studios located all over the UK, including 4 in London. SonicLife offers a really wide range of studio equipment to their customers such as analogue and digital recorders, mixing desks, audio interfaces, microphones, studio monitors, digital converters, controllers and other miscellaneous studio accessories.  

 

The members of staff, who work in the SonicLive studios, include studio managers, drivers and sound engineers but some members of staff can be allocated to more than one studio. Every studio is assigned a studio manager. The role of the studio manager is to ensure the smooth day-to-day running of the studio that he/she is responsible for. The job of the drivers is to guarantee the safe transportation of equipment and for this purpose each driver is given a van and these vans are under the responsibility of the drivers they are given to and not shared among drivers. A record of which piece of equipment is transported by which driver needs to be kept. It is to be observed that vans can be out of service for certain periods of time, sometimes for quite a while, and are thus not used by any drivers during these times. The role of the sound engineers is to ensure that customers are provided with the right type of equipment for the music work that they want to do and that they can use it appropriately to get the best value out of it. Each engineer oversees a certain number of customers so that to ensure that all the customers have a first point-of-call in case they have any problems and thus to make sure that they receive the best possible customer service at all times. In addition, each engineer is responsible for a certain number of pieces of equipment which they need to closely look after in order to make sure that they are in pristine condition. To this effect, all pieces of equipment must be maintained regularly. At regular intervals or on specific dates, all pieces of equipments need to be serviced by the sound engineers who know how to fix them or by a whole group of engineers in the case of particularly complex equipment such as, for instance, large mixing desks. Similarly, if a piece of equipment is faulty, it needs to be repaired urgently so that it can be made available to the customers as rapidly as possible. It is also important to note that a piece of equipment is registered under a specific studio???s name so that a record is kept of which studio is ultimately responsible for it.  

 

A distinction is made between two different types of equipment. There is equipment that is fixed, like large mixing desks, digital recorders or audio interfaces, in the way that this equipment cannot leave the studio because of the size and therefore can be used only in the studio under the guidance of a sound engineer. Other pieces of equipment like microphones, converters and other accessories are portable in the sense that they can be taken away by customers to be used anywhere. Because of the highly technical nature of the equipment offered by SonicLive, a customer needs to first place a request for any piece of equipment he/she is willing to hire.  This request needs to specify the start date and the end date of the period of utilisation of a specific piece of equipment, the level of expertise the customer who is going to use it has and a description of the project for which this piece of equipment is going to be used. Once it has been submitted, a SonicLive sound engineer examines the request, finds out about the availability of the required piece of equipment for the required period of utilisation and decides whether to go ahead with hiring out this equipment or not. If the piece of equipment is portable, a Portable Equipment Hiring Agreement is drawn to record when the equipment is to be hired out to the customer, when it is due to be returned, the initial cost of the hiring, whether an additional insurance needs to be subscribed to and the total cost of the hiring including any additional insurance. If the piece of equipment is fixed, i.e. not portable, a Fixed Equipment Hiring Contract is produced to record which piece of equipment is to be used by which customer under the guidance of which engineer, as well as the start and end dates of this utilisation and the cost involved.  


Now, consider following new requirements that will arise as SonicLive plans to expand their business:

??? Expand the studios (outlets) world-wide to provide related equipment to more clients
??? The system that manages the entire operation is to be accessed by a large number of concurrent users
??? The operational system is to be expanded to be accessed by mobile and web-based applications so that anywhere access to the system is given for system  users to update statuses of business

As the business grows, it is expected that the volume of data along with the velocity of data generation will also grow exponentially. Thus, a NoSQL store, will be more appropriate to handle the new requirements.

As a Big Data architect, you are expected to introduce NoSQL storages to address new requirements and enhance the performance of the existing systems.

Question 1 
a. Justify the selection of the proposed NoSQL type(s) and the technology(s). You should specify any assumptions that you have made.
You should consider and include following points when compiling your answer:

??? Critical business requirements/features that will require NoSQL solution
??? Mapping above critical requirements/features with the key characteristics of the proposed NoSQL type/technology
??? Advantages and disadvantages of the proposed architecture based on the features provided by the proposed NoSQL type(s)/technology(s)

b. Analyse the applicability of the CAP theorem considering the important business requirements and proposed NoSQL type(s) and technology(s). You need to discuss how 
the key business requirements are affected based on the proposed solution. State any assumptions you made when constructing the answer.



Question 2 

There are hundreds of ???NoSQL??? technologies and dozens of them are widely used. Pick any NoSQL technology, 
Your work with the selected technology will cover following areas:

??? Study the functionality of the system (objectives, key features, drawbacks, etc.)
??? Download, run and work with the system (practical work with the system).
??? Section 1 (1000 words) : Describe the functionality and the features of the system

o Introduction
??? Technology used, maturity level, commercials, support
o Objectives
o Key features
o Architecture (Master-slave/peer-to-peer, consistency, availability, replication, ???)
o Data model
o Advantages/drawbacks
o Limitation

??? Section 2 : Perform practical operations with system and provide the NoSQL commands you have used and results you have obtained. You may use an appropriate 
dataset that you have created or publicly available online for your practical work.
o Creating/dropping databases/collections
o Storing, modifying and deleting data
o Retrieving data
??? Filtering
??? Aggregations and pipelines
??? Sorting and etc.
o Basic administration tasks
??? Start/stop the instance
??? Tune consistency/availability
??? Replication


Question 3 

Use data provided with books.json file and load it to a MongoDB 
instance. Write the following queries to demonstrate the use of the MongoDB. For each one, write 
the MongoDB command you typed to get the answer and, where requested, give the answer you 
got back.
1. Create a database called ???iitdb??? and a collection called ???books??? and load the given data set 
to the ???books??? collection.
2. List only the title of all the published books
3. Find the books with 400 ??? 450 pages
4. Count the number of books which were authored by ???Steve Loughran??? ??? Report the number 
you get as an answer.
5. Find the books with a title that starts with the word "Mongo". Display only the title and 
authors. 
6. Find the books of category ???Java??? according to the first element in the ???categories??? Array. 
Display only the first author (first element in the ???authors??? Array), and the title. Arrange 
the name of the first author in ascending order and for that same first author, titles should 
be in descending order. 
7. Find the books written by more than four authors. Display only the title and the number of 
authors. 
8. Write an aggregation pipeline to count the number of published books for each category. 
Report number of books in the "Internet" category.





