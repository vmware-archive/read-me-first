# Forking in the pivotal github org

Among all the changes, we know that the change in past forking workflows will be one of the bigger ones for users moving to the new org.  And, while it was necessary based on business and administrative requirements, we sympathize with the trouble this may bring to you and your team and have done a lot of investigation to try and find an alternative that will work for most individuals while improving how we write and, more importantly, how we share code across Pivotal.

## Recommended Workflow

In place of using forks, we recommend using [protected branches](https://help.github.com/articles/about-protected-branches/) under the repo itself - with set permissions on each branch.   To read more on how this done, please see: [Enabling Branch Restrictions](https://help.github.com/articles/enabling-branch-restrictions/)

An example workflow : 

1. **Team B** sees **Team A** has some code they would like to work with and/or contribute to.
1. **Team B** reaches out to **Team A** for write access.
1. *If not previously done*, **Team A** creates rules around master branch from the repo settings. 
1. **Team A** grants **Team B** write access
1. **Team B** creates branch from master branch
1. Repeat as needed

If multiple teams are added and creating branches, it may become important for certain branches to also have rules set like in the case of the master branch.

**What if I don’t want/need to contribute to master branch of code in that repository?** 

There are a couple routes that you could go from here: 

**Team B** could still work within a protected branch of **Team A’s** repo.
**Team B** could request read access from **Team A** and clone that repo into a new repository within the org.



