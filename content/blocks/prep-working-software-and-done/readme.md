---
title: Prep Working Software and Done
description: This prep is for you to learn about Agile and important concepts.
modules: Databases
week: "1"
skills:
  - Time/Project Management
objectives:
  - Provide an example of a Definition of Done for a user story
  - Provide an example of an Acceptance Criteria for a User Story
time: 80
introduction: Agile software developers focus on delivering valuable working
  products regularly and incrementally to their end customers. You will learn
  about some concepts that developers use to ensure they always deliver
  high-quality, working software.
exercises:
  - name: Definition of "Done"
    time: 30
    goal: To get familiar with why teams completely “Done” software every sprint
    content: >-
      ##
      [](https://www.scrum.org/resources/blog/why-scrum-requires-completely-done-software-every-sprint)"Is
      it done
      done?[](https://www.scrum.org/resources/blog/why-scrum-requires-completely-done-software-every-sprint)"


      **Salesperson**: Have you finished that feature you’re working on?


      > **Developer**: Yes! It’s done.  I just finished 10 minutes ago.


      **Salesperson**: Great - I have a Spanish customer who really needs it.


      > **Developer**: Oh! Well, they can’t see it yet because we haven’t updated the on-screen instructions. And our product owner hasn’t yet agreed that it meets the acceptance tests. And the UI text hasn’t yet been translated into Spanish.  And it’s not even integrated into the development branch let alone the production branch.


      **Salesperson**: So, when you said it was done, what did you mean exactly? When will you be "*done done*"?


      This conversation shows why every software team needs to agree on exactly what they mean by “done” for their software. Whenever more than one person works on a single project, the team members must have a common understanding of what "done" means for them.


      A simple definition of “done” may look something like this:


      > *Our backlog items are "done" when:*

      >

      > * *It passes all our unit tests*

      > * *It passes the acceptance criteria for the User Story*

      > * *Code follows our agreed style guide*

      > * *Code is reviewed by at least one other person*

      > * *Any relevant documentation is updated*

      > * *Code is delivered to the git development branch*

      > * *The product owner accepts it*


      Note that each team will have their own unique definition of "done" that works for them using the particular processes and quality methods they have agreed upon. Have they agreed to minimize any web graphics? Have they agreed to ensure their code works on certain web browsers? If so, these agreements will be reflected in their definition of "done".


      Also, teams often have different rules in their definition of "done" that apply to different types of backlog item. For example, a backlog item that affects UI components will perhaps include "changed components tested for blind users", but a backlog item on server-side changes will need different rules.


      As teams change their quality processes over time, they may well improve and update their definition of "done" to include further quality statements on usability, documentation, performance, metrics, and many other aspects of delivering high-quality software to production.


      ### Acceptance Criteria vs Definition of "Done"


      You've met Acceptance Criteria before. They are a list of tests that help developers know they are delivering the value of a User Story that the Product Owner expects. This sounds very similar to the Definition of "Done", doesn't it?


      The difference is that acceptance criteria are specific tests for *a single* backlog item, whereas the definition of "done" applies to *all* backlog items that a team delivers.


      For example, if you have a User Story to deliver a log-in function, the Product Owner might specify the following acceptance criteria:


      * users go to the home screen when the password is correct

      * error message displayed when user-id and password do not match

      * registered users can reset their password via email 


      However, a definition of "done" might contain (amongst others) rules like these:


      * All web pages can be navigated without using a mouse

      * All web pages tested in both dark and light modes

      * All web pages follow our standard styling 

      * ... 


      In other words, you can use a combination of acceptance criteria and a definition of "done" to help you and your team ensure that you are always delivering high-quality, working software.


      ### Further Reading


      For further information, read this [article](https://www.scrum.org/resources/blog/why-scrum-requires-completely-done-software-every-sprint).
  - name: Understand the roles
    time: 30
    goal: To understand the roles and the work they do you will need the knowledge
      in the class
    content: >-
      Different types of roles will impact a team delivering valuable “working
      software”. Below is a list of roles with different characteristics.
      Research about them using any tool you would like.


      You will use these roles in your exercises in class, so make sure you understand their personalities.


      * Lazy software developer

      * “Hacker” software developer

      * Bean-counter project manager

      * Salesperson

      * Proxy customer who is not the end user

      * Customer’s lawyer, who wants to verify the progress

      * Product Owner trying to maximise “value”.
---
