## Lab 5

# Pros and Cons of Test Driven Development

I believe there are many pros of test driven development, as mentioned in the tutorial video for this lab. The first of which is that it consolidates the expected functionality of the project before implementation. This in turn, forces you to automate your testing setup and to make time for testing so that it is not an afterthought at the very end of development. Cumulatively, this creates a higher sense of confidence at the time of deployment and hopefully a better-defined development process..

I believe that a con of test driven development is that it delays the development process as tests must be developed first before starting implementation which may cause frustration if deadlines are tight. I believe another con is that if the tests are not derived carefully and collaboratively, it can scope down the project to only providing functionality that matches one developer’s view of the project, and may not consider any edge cases that singular developers did not consider. In essence, since the tests directly inform the development of the project, having suboptimal tests will directly lead to a suboptimal project.

# My contribution to my team's unit tests

For my contribution to my project's unit test, I have added a unit test for our project's database connection and gleaning of information.
I added this as I was working on the "For You" recommended page functionality for our site, which relies on connecting to our
relational database. It checks first if we can access the database and then if we can pull the events from the database. 
It is available in our our repo under the tests folder in betula_test.py under the Sean comment. It is currently available 
[here](https://github.com/ECE444-2023Fall/project-1-web-application-design-group19-webcrafters/blob/Unit-Tests-(Lab-5)/tests/betula_test.py#L150-L193).