## Interpreting the Agile Manifesto {#agile_manifesto}

The Agile Manifesto provides very broad guidelines:

> We are uncovering better ways of developing
> software by doing it and helping others do it.
> Through this work we have come to value:
> 
> * Individuals and interactions over processes and tools
> * Working software over comprehensive documentation
> * Customer collaboration over contract negotiation
> * Responding to change over following a plan  
> 
> That is, while there is value in the items on
> the right, we value the items on the left more.
> 
> --[Agile Manifesto](http://agilemanifesto.org/)
> {: .attribution}

First of all, _don't stop reading after the list!_
The things on the right do have value.
The manifesto is about what gets _priority_, not what gets _done_.

That said, here's how we put these guidelines into practice:

### Individuals and Interactions {#individuals_and_interactions}

The first principle of the Agile Manifesto is to value individuals and interactions over processes and tools.

As software developers, we are actually passionate about tools.
And we love our processes as well.
Both processes and tools help us get things done.

But tools and processes can get in the way of people and relationships.
This principle guides us in choosing tools.
We choose tools that amplify the individual's effectiveness, rather than tools that the person has to steer and control.
And we choose tools that facilitate collaboration and communication.
Here is a short list of examples:

* Ruby, our preferred programming languages, has a lot of power and allow programmers to be expressive and clear, without a lot of ceremony that must be observed.
* Rails, our preferred web development platform, solves the most common and well-understood problems of web development for us, but gets out of our way when we need to do something unusual.
* The Git source control system (along with GitHub, the Git-based central repository we use) is designed to facilitate collaboration and experimentation.
  It also makes switching between tasks very fast and cheap.
* RSpec (including our own variant of it, Micronaut) allows us to write clean, expressive executable tests that serve as documentation of how the code should work.
* Our office workspace is geared towards allowing different team members to gather and pair program. This allows two programmers to work together easily on the same problem.

In addition to tools, we choose processes that emphasize people and communication.
Pair programming is a part of that, and so is the daily standup meeting.
We have retrospectives to talk about what went well and what could be improved
(and usually people, not tools, are at the core of both of those topics).

### Working Software {#working_software}

The second principle of the Agile Manifesto is to value working software over comprehensive documentation.

At Relevance, we keep software working and ready to ship throughout the development lifecycle by:

* pair programming
