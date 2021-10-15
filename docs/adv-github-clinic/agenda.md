# Agenda

* GitHub workflow 101 -- Connecting your computer to GitHub and pushing/pulling your changes up (30 min)
* Working with project boards in GitHub (30 min)

Resources

* https://rverse-tutorials.github.io/ My collection of R-Workflow material from NMFS workshops.
* https://rverse-tutorials.github.io/RWorkflow-NWFSC-2021/ The 2001 workshop. Has video of all sessions, lecture notes and post lecture discussion notes.
* https://happygitwithr.com/
* https://github.com/eeholmes Check out my repos and orgs for ideas.
* https://github.com/Openscapes/2021-noaa-nmfs/wiki Poke around our wiki for ideas.

# GitHub workflow 101

![](git-intro.png)

## Key Skills

1. Clone a repo to your computer
2. Tell RStudio where that repo is
3. Commit and pull/push changes into your repo

[lecture on these key skills](https://rverse-tutorials.github.io/RWorkflow-NWFSC-2021/week2-moregit.html)

## Set-up

* Option 1. GitHub Desktop. Install (or have IT install), [GitHub Desktop](https://desktop.github.com/)
* Option 2. RStudio [read this](https://rverse-tutorials.github.io/RWorkflow-NWFSC-2021/set-up.html#Git_from_RStudio). PC users, you will need to install Git (or have IT install it). GitHub Desktop will install Git for you but it is in an odd location.

## Skills

### Skill 1. Clone a repo to your computer

1. Create the repo in your GitHub account or organization
2. Pull onto your computer

**Let's see it done! I'll show RStudio and GitHub Desktop**

Interacting via RStudio versus GitHub Desktop.

* In my personal work, I clone with RStudio and mostly pushes/pulls with GitHub Desktop. Why? Faster and GH Desktop allows me to interact faster with my 50+ repos that I manage. Also GitHub Desktop makes it super easy to deal with merge conflicts. Easy peasy. I could waste half a day and trash my repo if I deal with those in RStudio.
* In teaching or helping colleagues, I **only** use GitHub Desktop. Why? The amount of futzing (5 nasty steps) to get RStudio connected is an unsustainable time-suck when I multiply that by the many people I help. GitHub Desktop works immediately. 

### Skill 2. Tell RStudio about your repo (if using GitHub Desktop)

If you are using RStudio for cloning, then you don't need this step.

**Let's see it done!**

### Skill 3. Commit local changes and push GitHub

This is 2 steps.

1. "Commit" Add a note about the change and add it to the history of changes.
2. "Push" Push those changes (and notes) up to GitHub. **pro-tip** you can link to a particular issue with `#` in your note.

**Let's see it done!**

### Skill 4. Pulling changes from GitHub

Pretty much just a button click, unless there are merge conflicts.

**Let's see it done! I'll show RStudio and GitHub Desktop**

### Going further

Lot of tips on how to work with Git and GitHub here [Week 2 More Git]
(https://rverse-tutorials.github.io/RWorkflow-NWFSC-2021/week2-moregit.html)

# GitHub Project Boards and Organizations

During week 1, many of you expressed the desire to learn how to do project boards in GitHub to help with your project planning. Here is how I do it.

## Organizations

I set up organizations for each of my projects. A cross-organization project board is not possible (as far as I know) so I track on my personal GitHub `Readme.md` file. It's all automatic. Look at the [Readme.md](https://github.com/eeholmes/eeholmes/blob/main/README.md) file.

## Project Boards

1. Skill 1 Setting up a project board and adding columns
2. Skill 2 Manually add and moving cards

That's all you need. For those who like automation.

3. Skill 3 Creating an automated board with tracking
4. Skill 4 Customizing automation with **project-bot**

### Examples

* Basic project board 1: [To Do and Done](https://github.com/nwfsc-timeseries/MARSS/projects/1)
* Org project board: [repo status](https://github.com/orgs/nwfsc-timeseries/projects/1)
* Basic project board 2: [Months/Milestones](https://github.com/nwfsc-timeseries/MARSS/projects/8)

### Automation (or semi-automation)

This is for those who use **issues**. This IMO works best if you are using labels and milestones on your issues.

* GitHub's basic Kanban automation
* [**project-bot**](https://github.com/philschatz/project-bot) [Let's see it in action](https://github.com/nwfsc-timeseries/MARSS/projects/8) 
* Setting up **project-bot**. You do this at the personal or organization level not repo level and you need admin rights at that level. [Go here to install](https://github.com/apps/project-bot)
















