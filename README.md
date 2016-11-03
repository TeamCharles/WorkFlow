# Work Flow
Official Team Charles™ Work Flow 💪

Version 1.0

## Table of Contents

* [Starting a New Project](https://github.com/TeamCharles/WorkFlow#starting-a-new-project)
* [Resolving a Ticket](https://github.com/TeamCharles/WorkFlow#resolving-a-ticket)
* [Style Guide](https://github.com/TeamCharles/WorkFlow#style-guide)
* [Employee Handbook](https://github.com/TeamCharles/WorkFlow#employee-handbook)

## Starting a New Project

1. Create a new Github repo
2. Clarify project requirements with Manager, Product Owner, and Team.
3. Create tickets that correspond with project requirements.
4. Product Owner priotizes project tickets.
5. All tickets should be tagged with `Low`, `Medium`, or `High` priority.

## Resolving a Ticket

1. Choose a High Priority ticket to work on.
2. Resolve the ticket locally on your machine.
3. Create only one Pull Request per ticket (E.g. branch name `issue#-feature`).
4. When the Pull Request is ready to be reviewed, the owner of the PR should tag each organization member in a comment with `@team`.
5. Team members must clone the PR and make sure it works on his/her machine.
6. Team members must comment on the PR giving their approval or suggest appropriate changes.
7. The creator of the PR must be the only person contributing code to the PR.
8. The creator of the PR is solely responsible for merging the PR into `master` when given group approval.

## Style Guide

[Official Team Charles Style Guide](https://github.com/TeamCharles/WorkFlow/blob/master/STYLE_GUIDE.md)

## Employee Handbook

[The Bangazon Employee Handbook](https://github.com/TeamCharles/bangazon-inc/blob/master/EMPLOYEE_HANDBOOK.md)

## Project Order

[Draw IO File](https://github.com/TeamCharles/WorkFlow/blob/master/ProjectOrder.png)

## Installing Visual Studio Code Snippets

Download this repo to your `TeamCharles` directory or download `classDocSnippet.snippet` and `methodDocSnippet.snippet` to your machine.

In Visual Studio, click `Tools` -> `Code Snippets Manager`. 

Select `CSharp` as the language.

Select the `My Code Snippets` directory as the location (or choose your preferred folder for custom code snippets).

Click `Import` and navigate to the `classDocSnippet.snippet` file. Repeat this and import the `methodDocSnippet.snippet` file as well.

When you select `OK` after importing the snippets, you are now able to use the following commands to run the snippets:

`cdoc` and press `TAB` twice to use the Class Documentation snippet.

`mdoc` and press `TAB` twice to use the Method Documentation snippet.