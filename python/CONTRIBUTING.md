# Contributing Guidelines

[In this document shall describe how you would like others to contribute to your code and what code of conduct shall they follow to avoid conflicts and misunderstandings during the collaboration process.]

## Installation for Developers
[Describe the steps  that *developer* should follow to install the source code and set up a development environment for each of the intended platforms (e.g. Windows 10, macOS, etc.).]

**Requirements** 
- [List the software and/or technologies on which the code depends, and add hyperlinks to the sources whenever possible.]
- [State any relevant hardware requirements.]

#### [For Patform A]

[List and describe each step required to set up a development environment and install the source code. Use a description/example format.] [For example:]

[1. Create and activate a virtual environment using `virtualenv`]

```bash
[$ virtualenv ./myvenv]
[$ source ./myvenv/bin/activate]
```

[2. Install dependencies ]
```bash
[$ pip install -r requirements.txt]
```

## Types of Contributions

A contribution can be one of the following cases:

[List all ways you want others to contribute with the code. Below is a list of typical cases as examples:]
    
1. [you have a question;]
2. [you think you may have found a bug (including unexpected behaviour);]
3. [you want to make some changes to the code base (e.g. to fix a bug, to add a new feature, to update 4. documentation).]

[The sections below outline the steps in each case.]

## Questions
    
[Edit the section accordingly, though the text below is generic and a common practice]
1. use the search functionality `[here](<link-to-issues-page>)` to see if someone already filed the same issue;
2. if your issue search did not yield any relevant results, make a new issue;
3. apply the "Question" label; apply other labels when relevant.

## Find Bugs

If you think you may have found a bug:

1. use the search functionality `[here](<link-to-issues-page>)` to see if someone already filed the same issue;
2. if your issue search did not yield any relevant results, make a new issue, making sure to provide enough information to the rest of the community to understand the cause and context of the problem. Depending on the issue, you may want to include:
    - the [SHA hashcode](https://help.github.com/articles/autolinked-references-and-urls/#commit-shas) of the commit that is causing your problem;
    - some identifying information (name and version number) for dependencies you're using;
    - information about the operating system;
    - detailed steps to reproduce the bug.
3. apply relevant labels to the newly created issue.

## Changes to Source Code: fix bugs and add features

1. (important) announce your plan to the rest of the community before you start working. This announcement should be in the form of a (new) issue;
2. (important) wait until some consensus is reached about your idea is a good idea;
3. if needed, fork the repository to your own Github profile and create your feature branch out of the latest master commit. While working on your feature branch, make sure to stay up to date with the master branch by pulling in changes;
4. make sure the existing tests still work;
5. add your tests (if applicable);
6. update or expand the documentation;
7. push your feature branch to (your fork of) this repository on GitHub;
8. create the pull request, e.g. following the instructions [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

> If you feel like you have a valuable contribution to make, but you don't know how to write or run tests for it or create the documentation: don't let this discourage you from making the pull request; we can help you! Just go ahead and submit the pull request, but keep in mind that you might be asked to append additional commits to your pull request.
