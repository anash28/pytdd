
###### Overview: Notes taken while reading TDD Python by Harry Percival
###### Author: Alfredzo Nash
###### Date: 24.MAR.16



###### CH. 1 Getting Django Set Up Using a Functional Test

###### CH. 2  Extend Our Functional Test using the unitest Module

###### CH. 3 Testing an Simple Home Page with Unit Tests
Lulz, Harry references Zed Shaw (p.21)
> Step back and think and have a think about what we're trying to achieve at this
point in the book.
> I'll reckon you'll learn more about TDD from these stop and think moments than
you do from all of the bits where the following instructions and copy-pasting
goes smoothly.
> Or it may be a real bug. Be tenacious, read the error message carefully (see my
aside on reading tracebacks a little later on in the chapter), and you'll
get to the bottom of it. It's probably just missing a comma, or trailing-slash,
or maybe a missing "s" in once of the Selenium find methods.
> But, as ``` Zed Shaw ``` put it so well, this kind of debugging is also
an absolute vital part of learning, so do stick it out!

[TDD Google Group](http://groups.google.com/forum#!forum/obey-the-testing-goat-book)

> The line between unit tests and functional tests can become a little blurry at times.
> The basic distinction, though, is that functional tests  ``` test the application
from the outside, from the point of the user. ```  Unit tests  ``` test the
application from the inside, from the point of view of the programmer.```

> The TDD approach I'm following wants our application to be covered by both types
of test. Our workflow will look a bit like this:

1. We start by writing a _functional_ _test_, describing the new functionality from
the user's point of view

2. Once we have a functional test that fails, we start to think about how to
write code that can get it to pass (or at least to get past its current failure).
We now use one or more _unit_ _tests_ to define how we want our code to behave -
the idea is that each line of production code we write should be tested by
(at least) one of our unit tests.

3. Once we have a failing unit test, we write the smallest amount of _application_
_code_ we can, just enough to get the unit test to pass. We may iterate between
steps 2 and 3 a few times, until we think the functional test will get a little
further.

4. Now we can rerun our functional test and see if they pass, or get a little
further. That may prompt us to write some new unit tests, and some new code, and
so on.

```
Functional tests should help you build an application with the right functionality,
and guarantee you never accidentally break it. Unit tests should help you to write
code that's clean and bug free.
```
> Django is broadly structured along a classic Model-View-Controller(MVC) pattern.
If you are interested, you can look up the finer points of the discussion in the

[Django FAQ](https://docs.djangoproject.com/en/1.8/faq/general)

###### CH. 4 What Are We Doing with All These Tests?

###### CH. 5  Saving User Input.

###### CH. 6

###### CH. 7
