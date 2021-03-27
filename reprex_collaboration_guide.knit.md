--- 
title: "Open Collaboration Guide"
author: ["Daniel Antal"]
date: "2021-03-27"
site: bookdown::bookdown_site
output: 
  documentclass: book
  bookdown::gitbook: default
  bookdown::pdf_book:
    language: english
    template: null
    toc: true
    tof: true
    includes:
      keep_tex: true
  bookdown::word_document2:
    toc: false
    reference_docx: docx/recoverytemplate.docx
    language: english
classoption: openany, a4paper, oneside
lang: en
papersize: a4
fontsize: "fontsize=13pt"
linestretch: 1.1
urlcolor: blue
linkcolor: blue
geometry: "left=3cm, right=3cm, top=2.5cm, bottom=2.5cm"
bibliography: [book.bib, packages.bib, antal.bib, ccipolicy.bib]
biblio-style: apalike
link-citations: yes
github-repo: rstudio/bookdown-demo
description: "This is a collaboration guide for Reprex open-source projects."
---

# Welcome

Placeholder



<!--chapter:end:index.Rmd-->

# Introduction {#intro}

## Code of Conduct

We as members, contributors, and leaders pledge to make participation in our
community a harassment-free experience for everyone, regardless of age, body
size, visible or invisible disability, ethnicity, sex characteristics, gender
identity and expression, level of experience, education, socio-economic status,
nationality, personal appearance, race, caste, color, religion, or sexual identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming,
diverse, inclusive, and healthy community. 

*If you work with us, you must adhere to the [Contributor Covenant Code of Conduct](#covenant)

## IDE

Our recommended IDE for documentation purposes is RStudio.  You must install R, RStudio at least to make it work.  For PDF outputs, you need to add a pdf compiler (recommended: tinytex, a lightweight tex compiler.) If you want to run Python code within RStudio, you need to have Pyhton installed on your computer, too.

## Simple Introduction

> This part is intendend for collaborators who do not write regularly code, and do not use markdown, LaTeX in their work.


<!--chapter:end:01-intro.Rmd-->

# Data Curation

We are constantly looking for new data sources that may be interesting to our partners or for our own R&D activities.

<!--chapter:end:02-data-curation.Rmd-->

# Data Acquistion {#acquisition}

Whatever is the source of the data we use it, we never trust it fully. We need check its strength and weaknesses, and bring it to a complete, documented and tidy form.


## Eurostat



## Harmonized Survey Programs

## Music APIs

### Spotify API

### Bandcamp


<!--chapter:end:03-acquisition.Rmd-->


# Data Storage & Databases

Placeholder


## Raw data assets {#dta-raw}
## Processed, individual data
## Indicators - statistically processed data
## Periodic data releases
## Interactive data releases
## Continous data releases in API

<!--chapter:end:04-data-storage.Rmd-->


# Applications {#applications}

Placeholder


## File, Variable Names, Value Labels
### Path
#### R language
### Variable nameing styles
### Character coding
## Statistical Processing & Indicators {#statistical-software}
### retroharmonize
### regions
### iotables
## Machine Learning Applications
### Listen Local app
### Bandcamp Librarian app

<!--chapter:end:05-applications.Rmd-->

# Contributor Covenant Code of Conduct {#covenant}

## Our Pledge

We as members, contributors, and leaders pledge to make participation in our
community a harassment-free experience for everyone, regardless of age, body
size, visible or invisible disability, ethnicity, sex characteristics, gender
identity and expression, level of experience, education, socio-economic status,
nationality, personal appearance, race, caste, color, religion, or sexual identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming,
diverse, inclusive, and healthy community.

## Our Standards

Examples of behavior that contributes to a positive environment for our
community include:

* Demonstrating empathy and kindness toward other people
* Being respectful of differing opinions, viewpoints, and experiences
* Giving and gracefully accepting constructive feedback
* Accepting responsibility and apologizing to those affected by our mistakes,
  and learning from the experience
* Focusing on what is best not just for us as individuals, but for the
  overall community

Examples of unacceptable behavior include:

* The use of sexualized language or imagery, and sexual attention or
  advances of any kind
* Trolling, insulting or derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or email
  address, without their explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

## Enforcement Responsibilities

Community leaders are responsible for clarifying and enforcing our standards of
acceptable behavior and will take appropriate and fair corrective action in
response to any behavior that they deem inappropriate, threatening, offensive,
or harmful.

Community leaders have the right and responsibility to remove, edit, or reject
comments, commits, code, wiki edits, issues, and other contributions that are
not aligned to this Code of Conduct, and will communicate reasons for moderation
decisions when appropriate.

## Scope

This Code of Conduct applies within all community spaces, and also applies when
an individual is officially representing the community in public spaces.
Examples of representing our community include using an official e-mail address,
posting via an official social media account, or acting as an appointed
representative at an online or offline event.

## Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported to the community leaders responsible for enforcement at
[INSERT CONTACT METHOD].
All complaints will be reviewed and investigated promptly and fairly.

All community leaders are obligated to respect the privacy and security of the
reporter of any incident.

## Enforcement Guidelines

Community leaders will follow these Community Impact Guidelines in determining
the consequences for any action they deem in violation of this Code of Conduct:

### 1. Correction

**Community Impact**: Use of inappropriate language or other behavior deemed
unprofessional or unwelcome in the community.

**Consequence**: A private, written warning from community leaders, providing
clarity around the nature of the violation and an explanation of why the
behavior was inappropriate. A public apology may be requested.

### 2. Warning

**Community Impact**: A violation through a single incident or series
of actions.

**Consequence**: A warning with consequences for continued behavior. No
interaction with the people involved, including unsolicited interaction with
those enforcing the Code of Conduct, for a specified period of time. This
includes avoiding interactions in community spaces as well as external channels
like social media. Violating these terms may lead to a temporary or
permanent ban.

### 3. Temporary Ban

**Community Impact**: A serious violation of community standards, including
sustained inappropriate behavior.

**Consequence**: A temporary ban from any sort of interaction or public
communication with the community for a specified period of time. No public or
private interaction with the people involved, including unsolicited interaction
with those enforcing the Code of Conduct, is allowed during this period.
Violating these terms may lead to a permanent ban.

### 4. Permanent Ban

**Community Impact**: Demonstrating a pattern of violation of community
standards, including sustained inappropriate behavior,  harassment of an
individual, or aggression toward or disparagement of classes of individuals.

**Consequence**: A permanent ban from any sort of public interaction within
the community.

## Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage],
version 2.0, available at
[https://www.contributor-covenant.org/version/2/0/code_of_conduct.html][v2.0].

Community Impact Guidelines were inspired by 
[Mozilla's code of conduct enforcement ladder][Mozilla CoC].

For answers to common questions about this code of conduct, see the FAQ at
[https://www.contributor-covenant.org/faq][FAQ]. Translations are available 
at [https://www.contributor-covenant.org/translations][translations].

[homepage]: https://www.contributor-covenant.org
[v2.0]: https://www.contributor-covenant.org/version/2/0/code_of_conduct.html
[Mozilla CoC]: https://github.com/mozilla/diversity
[FAQ]: https://www.contributor-covenant.org/faq
[translations]: https://www.contributor-covenant.org/translations

<!--chapter:end:06-covenant.Rmd-->


# Documentation

Placeholder


## Citations, Bibliography
## Software Releases
## Data releases
### Dataverse 
### Zenodo 
## Publications

<!--chapter:end:06-documentation.Rmd-->



<!--chapter:end:07-references.Rmd-->


# Appendix

Placeholder


## Markdown
## Bookdown
## Tinytex 

<!--chapter:end:09-appendix.Rmd-->

