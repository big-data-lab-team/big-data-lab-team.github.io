Welcome to the lab! Here are some information, resources and tips to
help you get started.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Technology](#technology)
  - [Core tools](#core-tools)
  - [Coding](#coding)
- [Scientific methodology](#scientific-methodology)
  - [Reading](#reading)
  - [Writing](#writing)
  - [Experimentation](#experimentation)
- [Lab culture](#lab-culture)
  - [Core values](#core-values)
  - [Communication and interactions](#communication-and-interactions)
  - [Code of conduct](#code-of-conduct)
  - [Academic integrity](#academic-integrity)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


# Technology

## Core tools

Get familiar with the following technologies asap:
* [bash](https://www.gnu.org/software/bash) scripting (on Linux or OSX): https://www.shellscript.sh
* [Docker](http://www.docker.io): https://docs.docker.com/get-started
* [Git](https://git-scm.com): 
  * https://try.github.io
  * https://rogerdudler.github.io/git-guide
* [GitHub](http://github.com)
* [Latex](https://www.latex-project.org) and [Bibtex](http://www.bibtex.org)
* [Python](https://www.python.org/about/gettingstarted): https://github.com/neurohackweek/python-for-scientists
* [Reprozip] (https://reprozip.readthedocs.io/en/1.0.x/): https://reprozip.readthedocs.io/en/1.0.x/
* ssh

## Coding

Code is first-class citizen in the lab. It is the primary output of
your research.

Any code 
in the lab is by default:
* In a Git repository.
* On GitHub.
* Hosted under the [/bin](https://github.com/big-data-lab-team) organization.
* Licensed under GPL-3.0 ([Free
Software](https://www.gnu.org) is good) or MIT (for a library).
* Written in Python.

To contribute to a code base (including your own project):
* Fork the repository on GitHub.
* Push commits to your fork.
* Make Pull Requests (PRs) to the base repository.

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

# Scientific methodology

## Reading
Key list of references to be completed:
* Interoperability
* Reproducibility
  *  [Reproducibility of neuroimaging analyses across operating systems](http://journal.frontiersin.org/article/10.3389/fninf.2015.00012/full), T. Glatard, L. B. Lewis, R. Ferreira da Silva, R. Adalat, N. Beck, C. Lepage, P. Rioux, M. Rousseau, T. Sherif, E. Deelman, Najmeh Khalili-Mahani, Alan C. Evans, Frontiers in Neuroinformatics, vol. 9, no. 12, 2015.
  * [Cluster Failure: Why fMRI inferences for spatial extent have inflated false-positive rates](http://www.pnas.org/content/113/28/7900.full) Eklund A, Nichols TE, Knutsson H. Proceedings of the National Academy of Sciences. 2016 Jun 28:201602413.
  * [The Effects of FreeSurfer Version, Workstation Type, and Macintosh Operating System Version on Anatomical Volume and Cortical Thickness Measurements](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3365894), Ed H. B. M. Gronenschild, Petra Habets, Heidi I. L. Jacobs, Ron Mengelers, Nico Rozendaal, Jim van Os, and Machteld Marcelis.
  * [Reprozip: Computational reproducibility with ease.](http://dl.acm.org/citation.cfm?id=2899401), Chirigati, Fernando, et al, Proceedings of the 2016 International Conference on Management of Data. ACM, 2016.
* Infrastructure
  * [Software architectures to integrate workflow engines in science gateways](http://linkinghub.elsevier.com/retrieve/pii/S0167739X17300249), Tristan Glatard, Marc-Étienne Rousseau, Sorina Camarasu-Pop, Reza Adalat, Natacha Beck, Samir Das, Rafael Ferreira da Silva, Najmeh Khalili-Mahani, Vladimir Korkhov, Pierre-Olivier Quirion, Pierre Rioux, Sı́lvia D. Olabarriaga, Pierre Bellec, Alan C. Evans, Future Generation Computer Systems, Volume 75, October 2017, Pages 239-255. 
  * Cloud, Spark.
* Neuroinformatics

## Writing

* Adopt a writing schedule as soon as possible and comply to it. Suggestion to start: 4 hours per week.
* Suggestions on what to write:
   * Write your own summary any time you read a paper.
   * Write a few paragraphs on your current work or ideas.
   * Outline your next paper or thesis.
* Create detailed outlines of important documents (papers, theses) as early as possible.

* Tools
   * Use Latex by default. Use Google Docs when heavy collaboration is expected (e.g., brainstorming document).
   * Create a Git repository for papers and theses, containing:
     * The Latex/Bibtex source.
     * Any script (e.g. [Gnuplot](http://www.gnuplot.info)) and data required to reproduce Figures. You might loose a few hours cleaning up your scripts but it will save you days when you need to update your manuscript.
     * See example [here](https://github.com/big-data-lab-team/paper-sequential-split-merge).
     * Push the Git repository on GitHub and encourage collaborators to fork/PRs (see Code section).

* Useful books and references about writing:
   * [How to Write a Lot](https://www.amazon.ca/How-Write-Lot-Practical-Productive/dp/1591477433), Paul J. Silvia.
   * [The Elements of Style](https://www.amazon.ca/Elements-Style-William-Strunk-Jr/dp/020530902X), Wiliam Strunk Jr and E.B. White.

## Experimentation

Most of your papers will be based on experiments conducted with your
developed software. Be meticulous and patient, it takes time to get a good experimental setup. Make yours this quote by David Donoho et al (2009):
```
the scientific method's central motivation is the ubiquity of error -

the awareness that mistakes and self-delusion can creep in absolutely anywehere

and that the scientits' effort is primarily expended in recognizing and rooting out error. 
```
In other words, think of all possible causes that might corrupt your results: background tasks running on computers, software bugs, data corruption, etc

# Lab culture

## Core values

The lab is committed to the following values:
1. High quality is
preferable to high quantity.
2. Technical quality is a requirement to
scientific quality.
3. Openness leads to better content.

The target lab culture is to promote frequent informal interactions,
flexible work hours, academic integrity, gender equality, cultural
diversity and ... having fun doing research!

## Communication and interactions
* Never hesitate to ask a question to anyone.
* Register to [Slack](https://big-data-lab-team.slack.com) (in the future me might use [Mattermost](https://about.mattermost.com) instead).
* Share information with others in the lab. Including ideas, code snippets, technical tips, etc Your co-workers are not your competitors, you are on the same side.
* Communicate regularly with Tristan. On Slack, by email or by requesting a meeting whenever required. Don't let any issue block your work or bother you for too long without talking about it.
* Attend hackathons, in particular those organized by [BrainHack](http://brainhack.org) in Montreal. Use hackathons to demonstrate your project, collect feedback on it, and stay up-to-date on technology.     

## Code of conduct
This section is largely copied from [Whitaker's lab Code of Conduct](https://github.com/WhitakerLab/Onboarding/blob/master/CODE_OF_CONDUCT.md).
* Harassment by and/or of members of our community in any form will not be tolerated. Harassment includes offensive verbal comments related to gender, sexual orientation, disability, physical appearance, body size, race, religion, sexual images in public spaces, deliberate intimidation, stalking, following, harassing photography or recording, sustained disruption of discussions, inappropriate physical contact, and unwelcome sexual attention.
* Work hours: The hours that members of the lab choose to work is up to them. We are each welcome to send work-related emails, pull requests or Slack messages over the weekend or late at night, but no lab members are required to reply to them outside of their typical work hours. Lab members are welcome to work flexibly for any reason. Ideally, all lab members will have at least a few hours each week to overlap with Tristan in order to stay in touch, but it is the policy of the lab that every member is already self-motivated and doesn't need to work a traditional 9 to 5 day in order to meet their goals.
* If you experience any challenges of any kind related those topics, please contact Tristan. All communication will be treated as confidential.

## Academic integrity
* Data, code and text sharing through Git repositories hosted on GitHub is a good way to protect us against [scientific fraud](https://en.wikipedia.org/wiki/Scientific_misconduct). Having others regularly reviewing your own PRs to your own repositories is even better.
* Reusing text or code from others' work is fine (even encouraged) as long as the source is properly credited. Omitting to cite the source is plagiarism.
* Data fabrication or falsification is evil. Don't even think about it. If your data looks strange, don't delete or omit it. Repeat the experiment and try to understand what is going on, you will learn more. If your graph is missing a point or two and the submission deadline is coming too soon, let the graph be incomplete. You will feel better and it will improve the paper. There is no such thing as a good or a bad result, there are just results.
