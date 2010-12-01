## Behaviour-Driven Development {#bdd}

At Domain7, we write most of our code in a "behaviour-driven" style.

The tools we use for BDD mean that, in many cases, specs and examples can be read and understood
by customer representatives, including domain experts (perhaps with a little help from us).
That's really valuable, especially when the requirements are tricky, because it helps us to
be clear and precise, and to know that we're really building what our customers want.

BDD adds tremendous value to the delivered product:

* The product is robust. It can withstand a large and small refactorings without the huge risk of breaking previous features
* The product is audit-able. Feature files are readable by non-technologists. 
* The product is documented. Feature files ensure that product documentation is up-to-the-moment.
* The product is well-designed. Code that's really well designed is also very testable.
  In fact, one of the best ways to ensure that your code is well designed is to require that
  it be testable.
  (And the best way to do that is to build it through testing!)
  BDD helps us deliver code that has high cohesion and loose coupling, and a lot of other
  qualities that may seem like just so much programmery jargon, but which do make the
  systems less costly to maintain and enhance over time.

BDD is incredibly valuable to the process, for numerous reasons:

* As one of our employees has pointed out, it's possible to
  fail even if your test suite seems thorough
  BDD is the best way we know to ensure that our tests actually cover all the *requirements*,
  not just all the *code*.
* BDD helps us focus on what the code needs to do, so we avoid the trap of building "nice to have"
  features that the customer doesn't value.
* BDD radically shortens the feedback loop between making a coding error and *discovering* that error.
  Debugging time is slashed by a huge amount.
  (Even if all of the other benefits did not exist, this alone would pay for the time spent writing tests.)
* The tests---especially if they're written in a very expressive style.
  This documentation is very useful to future developers who might take up maintenance or further
  development on the project.
  With continuous integration, the whole process ensure that these tests always reflect
  the actual state of the system, which makes them far superior to a prose design document.
  (We've never seen one of those that wasn't very outdated.)
* BDD ensures conversations about minute details make it into documentation to be shared amongst product owners, project managers, designer and developers. 

