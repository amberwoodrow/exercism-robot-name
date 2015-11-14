# Robot Name

Write a program that manages *robot* factory settings.

When robots come off the factory floor, they have no name. // consturctor robot with name property null

The first time you boot them up, a random name is generated, such as
RX837 or BC811. // random name method - reset()

Every once in a while we need to reset a robot to its factory settings,
which means that their name gets wiped. The next time you ask, it will
respond with a new name. // call reset()

Random names means a risk of collisions. In some exercism language
tracks there are tests to ensure that the same name is never used twice. // make sure name is unique in reset()



// the robot has a prototype and the prototype has many methods
// the methods I want to add are attached to the prototype of the robot

## Setup

Go through the setup instructions for JavaScript to
install the necessary dependencies:

http://help.exercism.io/getting-started-with-javascript.html

## Making the Test Suite Pass

Execute the tests with:

```bash
$ jasmine-node .
```

In many test suites all but the first test have been skipped.

Once you get a test passing, you can unskip the next one by
changing `xit` to `it`.


## Source

A debugging session with Paul Blackwell at gSchool. [view source](http://gschool.it)
