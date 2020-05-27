# Contributing

When contributing to this repository, you may open a pull request with your proposed changes or bug fix or you may first discuss the change you wish to make via issue,
email, or any other method with the maintainers of this repository.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Building the package

If you are making and testing changes to cliche itself, the following commands
will be useful to know. This repository makes use of [poetry](https://github.com/python-poetry/poetry)
for configuring a virtual environment and so the commands below will reference
it so that they are run inside of that environment. If you want more information
about Poetry, then you can view the documentation [here](https://python-poetry.org/docs/basic-usage/)

### Setting up your environment

This command will create a new virtual environment and install the dependencies
in it.

```
$ poetry install
```

### Testing changes

```
$ poetry run pytest --cov=cliche tests
```

### Building the package

```
$ poetry build
```

### Building the docs

```
$ poetry run sphinx-build -b html docs build/html
```

## Filing Issues

If you find a bug or you have a feature request, you can file an issue using the
GitHub [issues](https://github.com/NetApp/cliche/issues) system. Please be sure to include as much information as possible about the issue you are facing and your configuration or reproduction steps.

## Creating a Pull Request

After you've made changes and tested that they work using the steps above, you may file a pull request to have your changes merged into the code base. If you are unfamiliar with the process, you can find GitHub's documentation about it [here](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at ng-cliche-lib@netapp.com. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
