## Camilo Riviere
## 01/11/2017
## CEN4010-U01 Software Engineering I
## Chapter 1 Exercises
<br>

1. <strong> What is the purpose of modeling?</strong>  

  a.

  <strong>Modeling</strong>

  Modeling is one of the most efficient activities in software development that provides an efficient way to analyze the existing business processes and help in designing new software systems. It reduces the complexity of the problem by removing the irrelevant details from problem and at a time focus only on the relevant details of the question.

  <strong>Purpose of modeling:</strong> There are various purposes of modeling some of them are as follows:

  1. <strong>Better understanding</strong>: The main purpose behind modeling is to understand the complex system in a very easier and efficient way. Complex systems like artificial system that is related with space shuttle, railway ticket reservation system can easily understand with the help of graphical representation.

  2. <strong>Modification in System:</strong> If any modification is required in any system then it becomes very easy and convenient to make any changes in the system.

  3. <strong>Reduce risk:</strong> Modeling reduces the risk in experimenting with models as compared with real scenario. In other words it can be said that it also reduce the cost of modification.

  4. <strong>Decompose:</strong> It decomposes the large complex system into small subsystems. Each of these subsystems can be design and implemented independent of each other. So in this way all the subsystems are developed at the same time in parallel, which speed up the development process.

  5. <strong>Less number of defects:</strong> Modeling helps in evaluation of the system before starting the actual implementation of the system. Hence the final code has the least number of defects.

2. <strong>A programming language is a notation for representing algorithms and data structures. List two advantages and two disadvantages of using a programming language as the sole notation throughout the development process</strong>

  a. <strong>Advantages:</strong> Advantages of using a programming language notation as sole notation for development process are as follows:

  1. <strong>Single notation for all activities:</strong> There is no need to learn different notation technique because only one notation that is programming language notation is used during the whole development process. So it will reduce the burden of learning different notation techniques.

  2. <strong>Traceability:</strong> Same notation is used in all of the development process so it is easier to compare two models. It also helps in predicting the estimate time required to complete the development process.

  b. <strong>Disadvantages:</strong> Disadvantages of using programming language notation as sole notation for development process are as follow:

  1. <strong>Difficulty in representation:</strong> Programming languages have a very poor quality of notation. As a result, it becomes very difficult to represent all of the user requirements by utilizing the programming language notation. If the requirements of the user are not properly represented then there is a possibility that the final manufactured system will differ from the requested system.

  2. <strong>Implementation starts earlier:</strong> Due to the programming language notation, programmers starts their implementation at the early state before analyzing the whole model. It also raises the problem where after completing three or four modules a developer may get stuck which may require a lot of modification. If developer starts implementation of the system are analyzing the whole model then their will be less of a chance that the developer will be stuck in implementation.

3. <strong>Consider a task you are not familiar with, such as designing a zero-emissions car. How would you attack the problem?</strong>

    a. Divide the problem into smaller problems as much as possible. After breaking down the main problem into smaller problems your main problem will be defined precisely.

    b. Using the information already collected, determine the boundaries of the solution space.

    c. Collect data from domain experts as well as non-experts.

    d. Using all the collected data, design a prototype. Prototype manufacturing does not require more investment but can be used to verify if the developer is headed in the right direction or not.

4. <strong>What is meant by "knowledge acquisition is not sequential?" Provide a concrete example of knowledge acquisition that illustrates this:</strong>

  a. It means that learning a new knowledge can provide that prior knowledge is wrong. In other words, new knowledge can invalidate your old knowledge.

  <strong>Example:</strong> In 1897 JJ. Thompson stated the Plum pudding model of an atom. According to Thompson his atom is made up of an electron which is surrounded by a small positive charge, like negative charge plums is surrounded by the positive charge pudding. In 1911 Rutherford contradicted this theory by stating that each atom has a small nucleus which is composed of positive charge protons and neutrally charged neutrons. The electrons move around this nucleus.

5. <strong>Hypothesize a rationale for the following design decisions:</strong>


* "The <code>TicketDistributor</code> will be at most one and a half meters tall."

  * The justification for the first statement "The TicketDistributor will be at most one and a half meters tall." is as follow: If the height of the TicketDistributor is greater than one and a half meter then the small children, dwarves and a person sitting on a wheelchair may not be able to purchase the ticket of its own. They always depend on the other person for buying a ticket. So it is better for everyone if the TicketDistributor is one and a half meter tall.


* "The <code>TicketDistributor</code> will include two redundant computer systems."

 * The justification for the second statement "The TicketDistributor will include two redundant computer systems." is as follow: If TicketDistributor has two redundant computer systems then that will increase the ticket distributions speed. If by any chance one computer system falls then we will not suffer setbacks because we will still have one system left for ticket distribution.


  *  "The <code>TicketDistributor</code> interface will consist of a touch screen for displaying instructions and accessing commands and a single button for aborting transactions."

    * The main motive behind using the touch screen for displaying instructions and accessing commands is to make TicketDistributor is to make the interface more user friendly. Also, a touch screen will also remove the need for extra hardware (such as: mouse, keyboard, etc) which is needed for inputting any command. The cancel button is used as an alternative for cancelling any transactions when the touchscreen stops functioning properly.


** 6. Specify which of these statements are functional requirements and which are nonfunctional requirements:

* "The <code>TicketDistributor</code> must enable a traveler to buy weekly passes."
  * Functional Requirement


* "The <code>TicketDistributor</code> must be written in Java."
  * Non-functional Requirement


* "The <code>TicketDistributor</code> must be easy to use."
  * Non-functional Requirement


* "The <code>TicketDistributor</code> must always be available."
  * Non-functional Requirement


* "The <code>TicketDistributor</code> must provide a phone number to call when it fails."
  * Functional Requirement


** 7. Specify which of these decisions were made during requirements or system design:

* "The <code>TicketDistributor</code> is composed of a user interface subsystem, a subsystem for computing tariff, and a network subsystem for managing communication with the central computer"
  * System design


* "The <code>TicketDistributor</code> hardware uses PowerPC processor chips"
  * System design


* "The <code>TicketDistributor</code> provides the traveler with online help."
  * Functional Requirement

** 8. In the following description, explain when the term <code>account</code> is used as an application domain concept and when as a solution domain concept:

  <i>"Assume you are developing an online system for managing bank accounts for mobile customers. A major design issue is how to provide access to the accounts when the customer cannot establish an online connection. One proposal is that accounts are made available on the mobile computer, even if the server is not up. In this case, the accounts show the amounts from the last connected session."</i>

- The first and second occurence of "Account" word in statement is used for application domain concepts because the phrases in which these words are used tell the requirement of the system. It also tells the use case, the sequence of event and various users' problem.

- The third and fourth occurrence of "Account" word in statement is used for solution domain concept because it gives the implementation details about the system and user's problem. It gives solutions to the developer, how to show user that he can access his bank account on mobile computer.

** 9. What is the difference between a task and an activity?

 S. No | Task | Activity
  ---  | ---  | ---
1      |   A task means atomic part of work.   |  An activitiy is a sequence of events that has a specific purporse.
2      | Represents the work but cannot be divided further.      | Also represents the work but can be further divided.
3      | A task is an element of activity      | Activity is a collection of various tasks.
4      | The task signifies that the activity is completed      | Activity signifies that the work is under process and has not yet been completed.
5      | Example: Risk analysis, code implementation are the task of the project development which are assigned by the project head to the team members.     | Example: Consider a project management activity which includes risk analysis, monitoring and code implementation.

** 10. A passenger aircraft is composed of several millions of parts and requires thousands of persons to assemble. A four-lane highway bridge is another example of complexity. The first version of Word for Windows, a word processor released by Microsoft in 1989, required 55 person-years, resulted into 249,000 lines of source code, and was delivered 4 years late. Aircraft and highway bridges are usually delivered on time and within budget, whereas software is often not. Discuss what are, in your opinion, the differences between developing an aircraft, a bridge, and a word processor that would cause this situation.

  1. From the statements in the questions it is concluded that the software systems are not only the complex system but there are lots of other complex systems like aircraft manufacturing, bridge manufacturing. The following point states that why the manufacturer or developers are able to deliver the complex system like aircraft and bridge on time but in case word development for windows, an innovative approach is required which is not yet developed.

  2. Aircraft and bridge developer take reference from the previous manufacture aircraft and bridge that is why they are able to give more accurate budget and completion date of the project which is not possible in the case of software development.

  3. Penalties associated with the completion of aircraft and bridge manufacturing are more severe than software development that's why there are delivered on time.

  4. Most new developed aircraft and bridges are similar to previous builds. They are simply refining the previous product. This is not always the case in software development.
