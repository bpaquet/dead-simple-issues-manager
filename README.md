dead-simple-issues-manager
=========================

Dead Simple Issues Manage : a simple issue manager which stores issues directly in your git repo

Why ?
---

Standard issues manager (like [Jira](https://www.atlassian.com/fr/software/jira) or [redmine](http://www.redmine.org/)) are standalone application.
They have plugins to talk to your Source Control, but integration is not perfect.

For example :
* how to specify on which branch this issue is fixed ? how to be sure this issue is fixed on this branch ?
* how to get all issues concerned by a version ?
* how to get issue history ?
* how to change issue status when merging ?

It's very easy to answer to theses questions for code, but not for issues.

Another point is issues manager tools are complicated. Too complicated. Too many constraints.

How it's works ?
---

Warning, it's very simple !

* Create an ``issues`` folder into your git project.
* Add a text file for each issue :)

To help you, ``dead-simple-issues-manager`` will provide
* a standard text file format for storing issues
* a web interface
* * to make this folder "browsable" : listing issues, sorting issues by branches
* * to create issues by filling a form
* * to change issues statuses, add comments, and much more

Roadmap
---

* Proof of concept deployable on heroku
** List issues
** Creating issues
** Add comments
** Change issue state
* Feature : a git code browser
* Feature : a markdown wiki




