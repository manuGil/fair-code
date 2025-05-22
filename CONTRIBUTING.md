# Contributing guidelines

Any kind of contribution to **Fair Code** is welcome, from a simple comment or a question, to a full fledged [pull request](https://help.github.com/articles/about-pull-requests/). You can reach out the maintainers via [m.g.garciaalvarez@tudelft.nl](mailto:m.g.garciaalvarez@tudelft.nl)

A contribution can be associated with the following cases:

- You have a question.
- You think you may have found a bug, including unexpected behavior.
- You want to make changes to the code base to fix a bug, make improvements, add a new functionality, or to update the documentation.

## A.  You have a question

1. Use the search functionality [here](link-to-issues) to see if someone already filed the same issue.
1. If your issue search did not yield any relevant results, open a new issue.
1. Apply the "Question" label. Additionally, apply other labels when relevant.

## B. You think you may have found a bug

1. Use the search functionality [here](link-to-issues) to see if someone already filed the same issue.
1. If your issue search did not yield any relevant results, open a new issue and provide enough information to understand the cause and the context of the problem. Depending on the issue, you may also want to include:
    - the [SHA hashcode](https://help.github.com/articles/autolinked-references-and-urls/#commit-shas) of the commit that is causing your problem
    - some identifying information (name and version number) for dependencies you're using
    - information about the operating system

## C. You want to make changes to the code base

### Announce your plan

1. (**important**) Announce your plan to the rest of the community *before you start working*. This announcement should be in the form of a (new) issue on the Github repository.
2. (**important**) Wait until a consensus is reached about your idea being a good idea.


### Set up a local development environment to work on your changes

If you are a part of Fair Code team and have write access to Fair Code GitHub repository, skip to the next subsection [Develop your contribution](CONTRIBUTING.md#develop-your-contribution). If you are a first-time contributor, follow the below steps:

1. Go to root of this repository and click on 'Fork'. This will create a copy of Fair Code repository in your GitHub account. 
            
1. Clone the fork to your local computer.
        
    ```bash
    git clone https://github.com/your-username/<repo-name>.git
    ```

1. Change the directory

    ```bash
    cd <repo-name>
    ```

1. Add the upstream repository

    ```bash
    git remote add upstream https://github.com/<account>/<this-repo-name>.git
    ```  

1. Now, `git remote -v` will show two remote repositories named:

    * `upstream`, which refers to Fair Code repository 
    * `origin`, which refers to your personal fork

### Develop your contribution

1. Set up a development environment on your computer by installing [Copier](https://copier.readthedocs.io) to a Python virtual environment:

    ```bash
    # On the root of the repository:
    python3 -m venv ./venv
    source ./venv/bin/activate
    pip install copier
    ```

1. Create a branch of the latest commit on the `main` branch to work on your feature/contribution:

    ```bash
    git checkout -b my-feature
    ```  

1. If you are contributing via a fork, make sure to pull in changes from the 'upstream' repository to stay up to date with the `main` branch while working on your feature branch. Follow the instructions [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/configuring-a-remote-repository-for-a-fork) and [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).

1. Update the user documentation if relevant. Undocumented contributions might not be merged.

### Submitting your contribution

1. Push your feature branch to your fork of Fair Code GitHub repository.

1. Create a pull request, for an example, following the instructions [here](https://help.github.com/articles/creating-a-pull-request/).

In case you feel you've made a valuable contribution, but you don't know how to write code for it, or how to generate the documentation; don't let this discourage you from making the pull request. We can help you! Just go ahead and submit the pull request. But keep in mind that you might be asked to append additional commits to your pull request.