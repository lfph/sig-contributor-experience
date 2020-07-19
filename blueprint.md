_This is work-in-progress by T. E. Shaw._

_Not final._

# Contributor Guide Blueprint

## Purpose

This contributor guide blueprint is a collection of best practices. Its purpose is to inspire contributors when they write the contributor guide for their particular project. The inspiration for this guide came primarily from the [Contributor Guides](https://github.com/cncf/contribute) of the [CNCF](https://www.cncf.io).

### How to Use

Contributors using this blueprint do not need to use everything.

* You are welcome to fork it and delete, change and add at will.
  * THE PROJECT and PROJECT are placeholders for the name of your project
  * to@domain.tld is a placeholder for email address
* The blueprint is kept as one page to ease the overview.
* Some contributors prefer to break their contributor guide into subpages to make them easier to read.

## Table of Contents

This guide is broken up into the following sections.
It is recommended that you follow these steps in order.

- [Welcome](#welcome)
- [First Time Contributors](#first-time-contributors)
  - [Why Contribute?](#why-contribute)
  - [How to Contribute?](#how-to-contribute)
  - [Before You Get Started](#before-you-get-started)
    - [Sign the Contributor License Agreement](#sign-the-contributor-license-agreement)
    - [Code of Conduct](#code-of-conduct)

## Welcome

Have you ever wanted to contribute to a cool open source technology project? Here we will help you understand the organization of the project and direct you to the best places to get started or find the answers you are looking for. You'll be able to pick up issues, write code to fix them, and get your work reviewed and merged.

This document is the single source of truth for how to contribute to the code base.

Feel free to browse the open issues and file new ones, all feedback welcome!

The following section is dedicated to first time contributors to open source. If you are a seasoned open source contributor, you can still skim over it, paying particular attention to the [Sign the Contributor License Agreement](#sign-the-contributor-license-agreement) and [Code of Conduct](#code-of-conduct) sections, which can be specific to this particular project. Project members, skip to section [Contributing](#contributing) below.

## First Time Contributors

The following sections are dedicated to first time contributors to open source.

### Why Contribute?

If you have come here, but are still unsure what are the benefits of contributing to an open source projects, perhaps the [FAQ](/FAQ.md) will help you?

In case you are still unsure, you can come and talk to the LFPH Special Interests Group (SIG) Contribugor Experience (link to it in the FAQ).

### Before You Get Started

#### Sign the Contributor License Agreement

Before you can contribute, you will need to sign the Contributor License Agreement.

The Linux Foundation Public Health (LFPH) defines the legal status of the contributed code in two different types of Contributor License Agreements (CLAs), individual contributors and corporations.

THE PROJECT can only accept original source code from CLA signatories.

This policy does not apply to (third_party) and (vendor).

It is important to read and understand this legal agreement.

##### How do I Sign?

TODO copy from here: https://github.com/kubernetes/community/blob/master/CLA.md

#### Code of Conduct

Please make sure to read and observe our Code of Conduct.

THE PROJECT follows the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md).

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting
the PROJECT Code of Conduct Committee (link) via to@domain.tld.

#### Community Expectations and Roles

PROJECT is a community project.

Consequently, it is wholly dependent on its community to provide a productive, friendly and collaborative environment.

* Read and review the Community Expectations (link, Kn) for an understanding of code and review expectations.
* See Community Membership (link, Kn) for a list the various responsibilities of contributor roles.
  * You are encouraged to move up this contributor ladder as you gain experience.

### How to Contribute?

There are many ways to contribute to an open source project. Simply using it, is the most common and straightforward. Being a user, you can contribute ideas or describe issues, so that they can be fixed. Getting closer, you can help with organisation, design or write for our website and social media, or write code.

#### Your First Contribution

##### Use the Project

Using the Project already consists a contribution!

##### File An Issue

##### Write Code

We reserve specific issues for newcomers.

GitHub has a great feature allowing issues to be marked as "good frist issue".

![Good First Issue](/images/good-first-issue.png)

Look for such issues in order to begin and contact us in case all have been taken.

### What's Next?

Now you are all set, read the following section [Contributing](#contributing), which regulates the actual day-to-day activities.

## Contributing

Should you wish to work on an issue, please claim it first by commenting on the GitHub issue that you want to work on it. This is to prevent duplicated efforts from contributors on the same issue.

### Setting Up Your Development Environment

TODO copy from here: https://github.com/kubernetes/community/blob/master/contributors/devel/README.md#setting-up-your-dev-environment-coding-and-debugging

### Contributor Playground

### Code Review

Pull Request Checklist (from Prometheus)

- Branch from the master branch and, if needed, rebase to the current master branch before submitting your pull request. If it doesn't merge cleanly with master you may be asked to rebase your changes.
- Commits should be as small as possible, while ensuring that each commit is correct independently (i.e., each commit should compile and pass tests).
- If your patch is not getting reviewed or you need a specific person to review it, you can @-reply a reviewer asking for a review in the pull request or a comment, or you can ask for a review on IRC channel #prometheus on irc.freenode.net (for the easiest start, join via Riot).
- Add tests relevant to the fixed bug or new feature.

#### Comments

#### Speed of Code Reviews

Inspiration: https://google.github.io/eng-practices/review/reviewer/speed.html 

### Dependency Management

_Describe how do you do Dependency Management._

## Community

This section describes our community, how we communicate, meet, decide and work together.

### Special Interest Groups (SIGs)

### Communication

### Events

### Mentorships

## Advanced Topics

### Owner Files

(Kubernetes)

(progress: processing Prometheus)

## Thanks
