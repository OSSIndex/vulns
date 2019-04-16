# OSS Index Vulnerability Reporting

This repository is intended for reports of:

* Advisories missing from OSS Index
* Issues with vulnerabilities reported by OSS Index

To report on Zero Day vulnerabilities which do not currently have advisories against them, please see the [Central Security Project](https://www.sonatype.com/central-security-project)

Thank you for the help!

##What is an advisory, and how do I submit one?

An advisory is a vulnerability which is reported *somewhere* on the internet. It might be reported as:

* A vulnerability on a vulnerability list somewhere
* A security advisory published by a product owner
* A note in a readme
* A GitHub, Bugzilla, JIRA, or other issue against a project

To submit an advisory, create an issue which contains the following information. Note that the more fields you provide, the faster we will be able to add the advisory to our catelog. At a minimum the URL field is required:

Issue Title:
```
Advisory: <A brief description of the advisory>
```

Issue body:
```
  URL: <Advisory URL>
  format: <Ecosystem name, eg. maven, npm, nuget, pypi, rubygem, etc.>
  namespace: <maven groupid, npm scope, etc.>
  name: <package name>
  versions: <Version range affected by the vulnerability>
```

##How do I report other problems in OSS Index data?

Sometimes OSS Index has false positives, or reported vulnerabilities are incomplete.

Issue Title:
```
Bug: <OSS Index vulnerability URL>
```

Issue body. Provide a description of the problem:
```
  <description of problem>
```
