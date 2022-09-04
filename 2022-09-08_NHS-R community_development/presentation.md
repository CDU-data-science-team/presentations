% NHS-R community: Supporting users and publishing open source in UK health and social care.
% Chris Beeley, Nottinghamshire Healthcare NHS Trust
% 8th September 2022

## What is NHS-R?

* Analysts and data scientists in health and social care
* Using open source tools (mainly R!)
* We share code (everything defaults to OPEN)
* Cooperate across organisational boundaries
* We cooperate across international boundaries
* We love beginners
* We make mistakes and learn together

## Why does NHS-R exist?

* Training
* Community
* Policy/ good practice
* Building tools for everyone to use- WAGOLL
* Lead by example- share, be inclusive, and be attractive to beginners

## Open source

* Natural to assume that the NHS is a collaborative enterprise
* Until recently there were no mechanisms to help us cooperate at all
* Everything is done over and over again, duplicatively, on proprietary DBs
* In the recent past:
    * No incentive to share
    * Many barriers to sharing

## Who does share? 

* [Facebook](https://engineering.fb.com/2020/01/13/open-source/open-source-2019/)
* [Microsoft](https://opensource.microsoft.com/projects/)
* [IBM](https://www.ibm.com/opensource/)
* [Samsung](https://opensource.samsung.com/main)

## Let's talk about Prophet

* What is Prophet?
* Why did Facebook give away Prophet (MIT licence)?
* I really have no idea, but let’s speculate anyway
    * Developers like to work in the open so it helps with recruitment and retention
    * They want people to use it so they can get better suggestions about how to improve it
    * They want people to improve it by submitting pull requests (several at the time of writing)
    * They don’t want the hassle of selling it!

## Why would we share?

* The four freedoms
    * Use
    * Study
    * Share
    * Improve

## How are we doing?

* Some orgs are still fighting about use!
* Many fighting tooth and nail over learning and transparency
    * Why?
* Building? Largely a pipe dream
    * Why?
* Contributing? Imagine the headlines!
    * Why?

## What can NHS-R do about this?

* Permission
* Visibility and community
* Skills
    * Basic- git, GitHub, issues, pull requests...
    * Advanced- building reusable stuff is hard
    * Advanced advanced- building reusable stuff *together* is really hard!

## Building tools

* Two tools today
* One for every provider trust in the country- simple, RAP compliant, useful
* One to show the potential for open source data science

## NHSRplotthedots



<!---
Please note the following rather convoluted terminal command to render this talk to Beamer pdf

pandoc "2022-09-08_NHS-R community_development/presentation.md" -o "2022-09-08_NHS-R community_development/presentation.pdf" -w beamer --pdf-engine=xelatex -V mainfont="DejaVu Sans"

Abstract:

The NHS-R community exists to help and support users of open source data science tools in UK health and care organisations, as well as to encourage the production, spread, and adoption of tools built with those methods. This talk will describe two projects which were supported by NHS-R, an open source text mining algorithm which allows users of patient experience data to rapidly classify thousands of comments according to their theme and positivity/ negativity, and a project which developed the first RAP compliant implementation of NHS England's statistical process control (SPC) methodology which is a key part of reporting at many NHS provider trusts. This talk will summarise the methodology and technology behind each as well as showing the specific ways in which they were supported by the community. The text mining work is productionised within a Shiny Golem dashboard and runs Python code through reticulate- further work was carried out to produce an R wrapper of the Python code to make it easy for R programmers to use the model themselves.

-->