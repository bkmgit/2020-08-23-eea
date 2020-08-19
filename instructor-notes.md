---
layout: page
---
## Setup
I recommend using a portrait layout for screen sharing so that students have space on their screen to open their own shell/Stata. We will encourage dual screens, but not all will be able to do it. In Zoom, click on "Share screen," "Advanced," and "Portion of screen." This way you can select a fixed rectangle on your screen to share. Make sure to move applications around your screen *before* you begin the class.

Use dark font on white background and at least 18p-sized font. Set this in advance for both Bash and for Stata.

Zoom host can make others host or co-host. Even if host's network breaks down, meeting stays online. There are polling buttons under "Participants", which can be used to substitute for green and red stickies. Zoom aggregates poll results there, that is, you can see how many participants have voted "Yes" vs "No."

## Shell
Before the lesson, unzip the [data file](http://swcarpentry.github.io/shell-novice/data/data-shell.zip) in the Downloads folder in your home directory.

The key objective of this lesson is to make learners comfortable navigating the folders on their computer and accessing files from *different* folders using relative paths. It is also important that they can look into .csv files without messing them up in Excel or other spreadsheet editor. 

## Git
We are using command line git to reinforce the concepts. At the end, you may show a GUI client to learners, but not before, so as not to confuse them.

The lesson is following a GitHub-based workflow. Make sure everyone has a GitHub account *before* starting this lesson.

We are skipping Episode 5, "Labeling Things." In practice, it is quite rare that we need to check out an old commit. We are only teaching students how to make this possible with using proper version control.

Pushing and pulling (Episode 6) are importants parts of the GitHub-based workflow. If you finish early, Episode 10 about sharing repositories with others could be a good next step. 

## Data Wrangling with Stata
We are using Stata 16, but some learners may have earlier versions, so the lesson does not yet include data frames.

The current working directory is am important concept to solidify in Stata, too, so make sure your screen share included this bottom line of the Stata window.

Proper Stata style is important, so write out commands in full (yes, even when live coding) and use relative paths with full filename extensions. We want learners feel like they are coding, not poking around in an app.

We seem to spend an inordinate amount of time on import delimited options. This is because reading data from "standard" formats is an important part of the workflow if you are to think of Stata as a tool in your tool chain, not as an interactive application. 

## Coding with Stata
The key mental model to share with learners: Stata is a tool that you can use most effectively like an interpreted programming language. In particular,

1. Save every data manipulation step in a .do file
2. Use .do files as scripts creating (preferably one) output from inputs
3. So much so that these scripts may even be called from the command line (optional, if time permits)

Getting this mental model across is the most important, everything else, like particular commands, are secondary. 

## Helping learners
Learners will ask for help in the topical Slack channels. Zoom audio and hand signals may also signal that a learner is stuck, but discourage the use of Zoom chat so that all written discussion is in the same place for everyone to learn from.

If you find it helpful, ask the learner to share a screenshot of their problem.
