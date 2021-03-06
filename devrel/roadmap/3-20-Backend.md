# Backend Roadmap Sync

**Lead**
Kevin Vuong (Head of Developer Relations) 

**Attendees**

* Bryan Wong (Head of Engineering) 
* Daniel Kim (President) 
* *Jason Livinghouse (Engineering)* 
* Jefferson Chhen (Developer Relations Manager) 
* *Owen Gao (Developer Relations Manager)* 
* *Sarah Gerard (Developer Relations Manager)* 
* *Mohammad Ismail Daud (Developer Relations Manager)*

*Italics* just indicate who should be assigned a back-end road-map role. 

Recording Link

* Held at Saturday March 21st, 10am PST
* [insert YouTube link to recording after meeting]

## Agenda

**3 days before the meeting**

- [x] Create Zoom link for the meeting
- [x] Create Google Calendar Invite for all attendees
- [x] Ask everyone to put their items that they've been working on the past two weeks in markdown file
- [x] Ask everyone to contribute to the agenda items and [meeting plan below](https://github.com/shreyagupta98/people/blob/master/meeting_template.md#updates)

**1 day before the meeting**

- [x] Send reminders to Slack channel tagging appropriate folks. 
- [x] Ask for last minute agenda items

**During Meeting**

- [ ] Start recording
- [ ] Announce:
  “This meeting is being video and audio recorded and the recording will be published publicly for transparency. If you are uncomfortable with the recording, please let your supervisor know and leave the meeting when necessary.”
- [ ] Assign note-taker
- [ ] Take attendance

**Start Meeting**

* Updates: what has been completed and can be checked off
* Discussion: ideas, feedback, concerns, plans
* Action Plan: where to go next, dependencies, all deadlines
* Deliverables: within the next (timeframe)

## Updates:

* Reminder on why road map is necessary
  * Plan to on-board other schools
* Outlining expectations
  * We are planning *modules* 
    * A module covers a specific subject in curriculum
    * Each module should be finished in a week

## Discussion points:

* Share Lucidchart with everyone
* Start on road-map
  * Using this as a guide https://roadmap.sh/backend
* Each module in road-map needs to have set of learning objectives and a (preliminary) list of activities and labs
* Discuss which "areas" to include in our road-map from the above guide
  * "Area" = more general topic like Relational Databases, Web Sockets, etc.
  * We need to then set up modules in each area
* Preliminary idea of what to cover in the road-map: 
  * Topic: Internet
    * HTTP, Browsers, DNS, Domain Name, Hosting, How Internet Works
  * Topic: Version Control
    * GitHub
    * Markdown
  * Topic: Intro to Python 
  * Topic: Node.js
  * Topic: Relational Databases
    * ORMs (Express.js and SQLAlchemy)
    * Database Theory
    * PostgreSQL
  * Topic: Authentication
    * Cookie-based, OAuth, Basic Auth, Token Auth, JWT  
  * Topic: NoSQL
    * MongoDB
  * Topic: *APIs*
    * Concept of APIs
      * CRUD Operations
      * HTTP Methods
      * Using a Simple API (Weather)
      * REST (w/ Postman!) and JSON (pick either one)
    * Using APIs w/ Postman 
    * Setting up an API
      * Flask + SQLAlchemy
      * Node.js + Express.js + MongoDB
    * Communication between Front-End and Back-End (lab idea?)
  * Topic: *Web Security*
    * HTTPS, CORS, SSL, OWASP, Content Security Policy, Hashing Algos
    * Sanitizing Input
  * Topic: Containerization and Virtualization
    * Intro to Docker
  * Topic: Web Sockets/Web Servers
  * Topic: Deployment
* Outline expectations for each module on road-map from each manager
  * Learning objectives, activity names, lab names, all in GitBooks

## Action Plan:

*Where to go next, dependencies, all deadlines*

* Split up different parts of back-end programming road-map to be done by **Monday**, **3/23**
* Example of what a module breakdown should look like:
  * Module: Intermediate Python
    * Learning Objectives
      * Students will continue applying their fundamental Python skills learned from the previous module.
      * Students will begin learning about how to integrate basic data structures like lists and dictionaries to add complexity to their Python code.
      * Students will learn how they can use for/while loops and if statements to control the flow of their code.
      * Students will learn how to represent strings in Python using F-strings.
    * Activities
      * Bookkeeper
      * Creating a Menu
      * Message Cipher
    * Labs
      * Word Translation Calculator
      * Basic Calculator
      * Tic-Tac-Toe
  * **Note that for this example, Intro to Python is a topic and there can (and should) be multiple topics for a module. The above example was just for one module of Python: Intermediate Python.**
  * Module breakdowns will be placed on our Wiki and represented on our road-map!
* Modules should also be in **Lucidchart**

## Deliverables:

*Within the next three days*

**NOTE:** for all modules, there should be **3-4 learning objectives**, **4-5 sample activities ** and **2-3 sample labs**

- Note that labs can technically have same content but different premises
- Activities and labs should have a one-sentence description

| Name                                                       | Assigned To | Deadline       | Notes                                                        |
| ---------------------------------------------------------- | ----------- | -------------- | ------------------------------------------------------------ |
| All modules on *Version Control Systems + Basic Front-end* | Owen        | 3/23/20 (Mon)  | we already have a "Programming Practices" module made on Airtable - all of the GitHub content should be included here); also HTML/CSS/JS activities are on Airtable for inspiration |
| All modules on *Intro to Python*                           | Kevin       | 3/23/20 (Mon)  | This module just needs learning objectives, activities and labs are done |
| All modules on *Flask + SQL/SQLAlchemy*                    | Jason       | 3/23/20 (Mon)  |                                                              |
| All modules on *Node.js + Express.js + NoSQL/MongoDB*      | Ismail      | 3/23/20 (Mon)  | we have already made some Node/Express/MongoDB activities on Airtable, also MongoDB Workshop should be helpful |
| All modules on *API Concepts + Testing with Postman*       | Sarah       | 3/23/20 (Mon)  | Please utilize the Postman activities as inspiration!        |
| Finalize above modules' Lucidchart                         | Kevin       | 3/24/20 (Tues) |                                                              |


Note that these modules are "less essential" but ultimately should be covered:

| Name                                                 | Assigned To | Deadline | Notes                                                        |
| ---------------------------------------------------- | ----------- | -------- | ------------------------------------------------------------ |
| All modules on *relational databases*                |             |          | Database theory should be included - please DM me for slides from my ECS 165A class (in HK but slides are very detailed)<br />Also practical applications of PostgreSQL |
| All modules on *authentication*                      |             |          | Cookie-based, OAuth, Basic Auth, Token Auth, JWT             |
| All modules on *web security*                        |             |          | HTTPS, CORS, SSL, OWASP, Content Security Policy, Hashing Algos |
| All modules on *Containerization and Virtualization* |             |          | Docker                                                       |
| All modules on *web sockets/web servers*             |             |          |                                                              |
| All modules on *deployment*                          |             |          |                                                              |

## Meeting Notes:
* Roadmap used to organize our objectives for newcomers.
* Circles in roadmaps (modules) are the main ideas and prerequisites for the topics branching off from them.
* Modules have learning objectives (analogous to syllabus), set of activities and labs w/ descriptions. Found at https://about.bitproject.org/teams/developer-relations/development-roadmap
* Today's purpose is to start the roadmap, and other schools will eventually build on it.
* We edit Lucidchart roadmap once our modules are approved.
* Issues will be assigned to us after the meeting.
* Issues are held in the bitprj/bitproject repo.
* We then discussed which modules we want to include.
