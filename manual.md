# Team manual

This team manual outlines our principles, expectations, guidelines, on-boarding process, and general information about how we operate as a research team.

## About

This document is designed to be a reference for new interns. It’s part of the on-boarding process when people join the team. The manual is a living document. Team members are encouraged to submit fixes and improvements to it.

## On-boarding

When you first join the team, you will have a meeting with your supervisor to get you set up (notebook et al), set expectations, add you to communication channels, etc. 

### Supervisors’s to-do list

* Ensure notebook and accounts are ready
* Add to the relevant GitLab organization/repo
* Send welcome message in Teams chat

### First meeting with supervisor

* Get introduced to your new work environment & colleagues
* Go over key information, incl. team manual, expectations, practices, code repos
* Pick up your notebook from IT

### Getting started

* Read the safety and security guidelines provided by your supervisor
* Set up Teams and send your supervisor a message there to confirm the communication chanel
* Set up your computer as outlined in the [Computer setup](#Computer-setup) section
* Study the [Software Carpentry](https://software-carpentry.org/lessons/) lessons on Version Control with Git and Python
* Go and start making something brilliant!

## Expectations

* We intend to foster a collegial atmosphere, with opportunities for spontaneous discussions and creative opportunities
* Keep track of your time and take your vacation days. Working extended periods of overtime without interruption can lead to burnout, exhaustion, and overall impedes the type of atmosphere we are trying to develop
* All team members should endeavor to participate in team meetings and share updates about their work (be ready to show preliminary results in team meetings)
* Share your work:
   * Strive to write [good code](#Coding-standards) that can be understood and reused by others
   * Compile a visual summary of your work and results at the end of your internship that help others understand what you have been working on 

## Communication

* **Chat:** We use Teams as the primary mode of communication for quick messages, announcements, reminders, and organizing meetings. Messages can be ephemeral so you cannot count of being able to read messages forever. Use email if you need a record of the conversation.
* **GitLab:** Each project is assigned a repository on our GitLab. Reviews of code, text, etc., will be done through the repository. We'll also use to set goals and tasks.
* **Individual meetings:** We aim to have short weekly or bi-weekly individual meetings to discuss project status, personal and professional goals, work through problems, and to build a good supervisor-student relationship.
* Group members are also encouraged to have meetings and messages with each other. **Don’t wait until problems build up to seek guidance.**

## Computer setup

* Set up Teams chat and Outlook for email
* Download and install [Git](https://gitforwindows.org) version control system
* Download and install [Miniforge](https://github.com/conda-forge/miniforge) as a Python package manager with conda/mamba 
* Download and install [Windows Terminal](https://apps.microsoft.com/detail/9N0DX20HK701?hl=en-US&gl=US) for a better command line experience
   * Configure a conda profile so you can use conda/mamba from Terminal 
* Download and install [VSCode](https://code.visualstudio.com) as a development environment that integrates with Git, conda, Jupyter, et al. 
   * Install the Python and Jupyter extensions
* Download and install [QGIS](https://qgis.org/de/site/forusers/download.html) as a user-friendly GUI for spatial data visualization and analysis
* Check out the GitLab repository your supervisor invited you to
* Set up the Python environment specified in your GitLab repo (if available)

## Coding standards

* Code should avoid being "too clever", for example clever abuses of languages and algorithms that cut corners in the interest of marginal time savings.
* Clarity and maintainability take precedence over performance to ensure that the code can remain useful beyond the original scope of the project.
* Tests should be considered mandatory for new functionality and bug fixes. These tests should be part of automated testing suites.
* Use [black](https://github.com/psf/black) to automatically format Python code.
* Documentation must be added with any new code and should be accessible to newcomers. Include examples whenever possible.
* Comments (not including markdown cells in notebooks) are encouraged but not necessary. Code should be as self-describing as possible. Where complexity is inevitable, comments should allow anyone to understand the shortcuts and reasoning.
* Include citations to algorithms whenever possible, including links to online resources.
* Docstrings should be added to all functions and classes in Python code.

## Learning resources

A curated list of software tools, services, and learning resources that could be handy for the work we do in the lab. Feel free to add new things that you've found useful!

* [Software Carpentry](https://software-carpentry.org/lessons/) has community driven lessons on how to use the Unix shell, Version Control with Git, and Python.
* [Learn LaTex in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
* [mamba](https://mamba.readthedocs.io/): Python package manager
* [Zotero](https://www.zotero.org/): collect and organize scientific articles
* [How to Write a Git Commit Message](https://cbea.ms/git-commit/): a comprehensive guide to learn how to write meaningful git commie messages. Read it sooner than later!

## License

This manual is based on the excellent [Computer-oriented Geoscience Lab manual](https://www.compgeolab.org/manual/), with materials adapted from  [Lab Carpentry](https://github.com/lab-carpentry) blueprints, the [Data Intensive Biology Lab](http://ivory.idyll.org/lab/) and the [Data Exploration Lab](https://data-exp-lab.github.io/). The manual contents are available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.
