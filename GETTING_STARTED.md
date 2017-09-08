# Getting Started

Welcome to the lab, it's great that you're here! Here are some
resources to help you get started.

## Preliminaries

You should get familiar with the following technologies asap. Here are
a few links to help you:
* [bash](https://www.gnu.org/software/bash) scripting (on Linux or OSX): https://www.shellscript.sh
* [Docker](http://www.docker.io): https://docs.docker.com/get-started
* [Git](https://git-scm.com): https://rogerdudler.github.io/git-guide/
* [Latex](https://www.latex-project.org) and [Bibtex](http://www.bibtex.org)
* ssh

## Coding

Any code 
in the lab is by default:
* In a Git repository.
* On Github (perhaps on GitLab in the future since [GitHub is a proprietary service](https://mikegerwitz.com/about/githubbub).)
* Hosted under the [/bin](https://github.com/big-data-lab-team) organization.
* Licensed under GPL-3.0 ([Free
Software](https://www.gnu.org) is good) or MIT (for a library).
* Written in Python.

To contribute to a code base (including your own project):
* Fork the repository on GitHub.
* Push commits to your fork.
* Make Pull Requests (PRs) to the base repostory.

Before releasing a repository, make it usable:
* Add a demo (data + expected answer) to demonstrate the main functionality.
* Write a README.md file.
* Make a 1-line installation procedure using pip, gem, cmake or autotools.
* Document all the user-facing functions.
* Write tests using pytest.
* Configure continuous integration in the repository.
* Push a container image to DockerHub (only if relevant).
* Add badges to README.md (if relevant).

Once a release is ready:
* Tag it in the Git repository.
* Write release notes on GitHub.
* Create a `develop` branch. After the first release, the `master` branch will always contain the latest release; `develop` will contain non-released commits.

See examples in [/bin](https://github.com/big-data-lab-team).

## Reading

		+ Interoperability
		+ Reproducibility
		+ Infrastructure
		Cloud, Spark.
		+ Neuroinformatics

## Writing

* Write every day, even if it's only a few lines. Suggestions:
   * Write your own summary any time you read a paper.
   * Write a few paragraphs on your current work or ideas.
* Create detailed outlines of important documents (papers, theses) as early as possible.
* Write with Latex by default, possibly with Google Docs in case heavy collaboration is expected (e.g., brainstorming document).
* Create a Git repository for papers, containing:
   * The Latex/Bibtex source.
   * Any script (e.g. [Gnuplot](http://www.gnuplot.info)) and data required to reproduce Figures.
* Push the Git repository on GitHub and encourage collaborators to fork/PRs (see Code section).

## Communicating
* Never hesitate to ask a question to anyone.
* Register to [Slack](https://big-data-lab-team.slack.com) (in the future me might use [Mattermost](https://about.mattermost.com) instead).
* 