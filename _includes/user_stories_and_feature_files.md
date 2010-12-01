### User Stories and Feature Files {#user_stories_and_feature_files}

Domain7 manages requirements and tasks using user stories and sometimes feature files.
Instead of a big requirements document in which small details can get lost,
each requirement or task has its own user story and sometimes an associated feature file

A user story has:
* A name
* Details (including acceptance criteria),
* Priority
* Estimate
* Other information.

We use a tool called [Pivotal Tracker](http://pivotaltracker.com) to manage user stories and view them in various ways and a slideout panel embedded in the actual application on our staging server to allow customers to approve stories in the shortest amount of time possible.

User Stories have many advantages.
User Stories push us toward very small granularity requirements, which improves estimates.
It's also easy to see what's been done and what's left if you track via cards.

Feature files are a way of capturing exact acceptance criteria for the application's behaviour.

Feature files use an emerging new language, gherkin. Gherkin is a Business Readable, Domain Specific Language that let's business analysts and Domain7 describe the software’s behaviour without detailing how that behaviour is implemented. 

The bonus of feature files, is that they double as a test suite. This way, once the behaviour is captured in language that all stakeholders can understand and agree upon, the very documentation about that behaviour (feature file) will ensure that the behaviour remains in the application permanently.

Each story has a *status*, and moves through a lifecycle:

* Recorded and stored in an "Icebox" for later
* Ready for Development in the "Backlog"
* In Development
* Delivered 
* Accepted and complete

The product owner is responsible for two of those transitions.
The product owner must decide if the requirements are correct and move the card to
"Ready for Development".
Then, when the card is in the "Delivered" state,
the client is responsible for final testing and either marking the
card as "Accepted" or commenting on why it has not been rejected and moving it back
into "In Development".
