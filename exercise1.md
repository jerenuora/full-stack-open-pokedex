The language i chose for the “project” is python.

For python, commonly we have pylint for linting, and we have pytest for 
testing.  Building is not neccessary or even possible in python, as it is 
an interpreted language, that is, it is run straight from the file the 
code is written in, without doing a build-step before. 

Some most popular CI tools seem to be:
Buddy, meant for web developers.
Gitlab CI, 
Bamboo, which is created by Atlassian, who also delivers Jira and Trello, 
much used in Scrum etc teams that often use CI pipelines too. 
But in the end, jenkins seems to remain at the top spot, with github 
actions growing in popularity as such a large number of people use github 
anyway to store their code. 


For a project of this size, with six developers, i would assume the size 
and scale of the app to be small enough for the ci-solution to be hosted 
at some easy cloud environment. On the other hand, this would greatly 
depend on the organization the developing team is working in. 
If the house is big enough, they might already have the means to host the 
pipe themselves, or even a dedicated team to build and maintain the whole 
ci-pipe, not needing a cloud based setup.
