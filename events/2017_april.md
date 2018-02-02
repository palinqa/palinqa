## CRAFT 2017 Edition

### Deliberate Testing in an Agile World
__Dan North (Principal @ Dan North & Associates)__

In the decade since agile has gone mainstream, testing has received more emphasis—and in many organizations an automated test suite is now a prerequisite for delivery. For the first time, testing is a core activity within an integrated dev team rather than a downstream activity to be commoditized or outsourced. However, when you scratch the surface of agile testing, it seems we have lulled ourselves into a false sense of security. In an era of “automate all tests,” testing on agile projects broadly falls into two categories: automated deterministic testing provided by TDD, BDD, ATDD, and friends; and manual exploratory testing, carried out by expert testers.
However rigorously we apply these methods, entire classes of tests aren't being considered, and entire groups of stakeholders are falling through the testing net. Not all automated testing should be deterministic; not all testing should be automated. Dan North helps identify the gaps in your testing approach. By considering testing as a risk management exercise viewed through the eyes of multiple stakeholders, Dan hopes you will share his mild panic about how much testing we aren't doing.

### Need for Speed: Accelerate automation tests from three hours to three minutes
__Emanuil Slavov (Head of QA @ Komfo)__
All automated tests (other than unit) are too slow and unreliable for the fast development pace every company craves, and there are many external dependencies and factors outside of your control, so when these tests fail, it’s hard to pinpoint the exact reason why.
Komfo had automated tests running for more than three hours every night. The execution time just kept growing unrestricted, and the tests were getting more unstable and unusable due to a feedback loop. At one point, the continuous integration build for the tests was red for more than 20 days in a row. Regression bugs started to appear undetected in production. The Komfo team decided to put an end to this madness—after considerable effort and dedication, the same tests currently run for only three minutes.
Emanuil Slavov tells the story of how Komfo achieved 60x faster tests. Along the way, Emanuil touches on topics such as test automation framework design, hermetic servers, optimizing test environments for speed, architecture for testability, DevOps collaboration, virtual containers, reliable tests when depending on services outside of your control, and the joys and pitfalls of parallel execution.
Having automated tests run that fast completely changes the software development game. There is no need to wait for the nightly tests to complete, and there are no more smoke tests. You can run all tests, get fast feedback, and release instantly without falling behind. In the near future, this will be standard practice, much like infrastructure as code or continuous integration are today. In order for a company to stay competitive, all existing automated tests—static code analysis, unit tests, API, and UI—should complete in less than five minutes after every code, database, or infrastructure change.

### Slides & Notes
#### [Slides for Deliberate Testing](/palinqa/docs/Deliberate_Testing.pdf)
#### [Slides for Need for Speed](/palinqa/docs/VelocityConf_AMS_2016_Need_For_Speed.pdf)
The tool Emanuil mentioned which is used to simulate external dependencies: https://github.com/emanuil/nagual
