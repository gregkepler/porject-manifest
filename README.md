# project-manifest
Methodologies and checklists to use for every project

## PreProduction

* Know your timelime
	* Production start date
	* Next check in
	* Final launch date
* Know your team
	* Who is the producer?
	* Who is the Tech Lead?
	* Who is the designer?
	* Who is the UX designer?
* What issue tracking software are we using? Pivotal Tracker, Github, Jira?
* Get a staging environment set up
* Make sure you are added to all project communication channels
	* Email groups
	* Slack channel
	* box folder
	* git repo
	* issue tracking software

### Joining a project that already has been started
* Is there a preexisting git repo?
* What is the deployment process?
	* Do I have access to it? If not, can I get access?

### Starting a project from scratch
* Create a new Github repo

## Before committing code
* `git status`, `git diff` to view changed files
* Only commit files relevant to specific update when possible. Split up commits if it makes sense.
* comment your code
* remove irrelevant/temporary logging

## Before each release
* You know that one thing that you know you should do, but don't want to, but really should? Just do it.
* Check your work on all relevant browsers / OSes (yes, that includes mobile too)

## Final Release Checklist
* Git tag your release
* Is tracking included and working?
* Remove all debug logs that shouldn't be in there

## Post Mortem
* Write up a Lessons Learned document
* Take screenshots and/or video screen recordings
* Make sure README is updated before you forget everything