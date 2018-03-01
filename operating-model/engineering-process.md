## Engineering Process

Our goal is to deploy things with very little overhead.  To that end, we follow a systematic process for our work.

Github and Code Checkouts

* Checkout your branch with your initials, and a summary of what you're doing \(i.e. wf\_\__fix_\_channels\)
* Always pull master daily, and before you issue a pull request, so it can be easily merged
* Issue a pull request stating that the change is
* Always start your 'next task' from master

Continuous Integration

* Your code should be green for the entire suite
* We use DroneCI for this

Check ins and code commits

* Someone else should review your code and give you approval to merge it
* Once it has been reviewed, merge your code into master
* At the end of the day, or when it's convenient, spend 10 - 30 minutes reviewing other code that has been committed, and give feedback
* When code is deployed to production, take a few minutes and verify that it's actually operational
* Keep your code changes/pull requests small. Do the smallest thing you can on each code commit



