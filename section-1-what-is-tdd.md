# What is TDD?
TDD, which stands for test-driven development is a software development [methodology](https://www.google.com/search?q=methodology&oq=methodology). It views unit tests as the most important artifact of the development process.  It is a companion methodology which can be used alongside various programming paradigms (OOP, Function, etc).


## What are the main concepts?

#### Unit Tests
The 'unit test' is the fundamental concept of TDD.  They are methods that prove that a 'unit under test' returns a particular value and/or creates a certain set of side effects (i.e. setting object properties, throwing expections) when exercised under various conditions (i.e. with different parameter sets, timings).

Unit tests should be small.  The can only be so when the methods that they are testing are themselves small.  If your unit tests are large, it is probably an indication that your methods being tested are doing more than they should.  A good rule of thumb is *a unit test should test one method which does one thing.*

#### Test Suites

#### Test Framework  
Nearly all modern languages have testing frameworks which allow developers 
to easily write unit tests for their code. Not surprisingly, Python has 
a built in framework - called UnitTest, as well as a variety of open-source 
modules available.

Red/Green
Practical TDD
No code without tests.
Testing Private Methods
Test Frameworks
SMALL TESTS

## Resources
[Wikipedia's entry](http://en.wikipedia.org/wiki/Test-driven_development) on TDD.
