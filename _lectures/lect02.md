---
desc: "Meeting Logs, Initial README, Team Agreements"
lecture_date: 2025-01-13
num: lect02
ready: true
---

# Current Homework still open until Wednesday: 

* <https://ucsb-cs148.github.io/w25/hwk/h01/>


# Teams are Assigned

You should have been:
- active on a team channel on the [Slack](https://ucsb-cs148-w25.slack.com)
- added to one of the [teams](https://github.com/orgs/ucsb-cs148-w25/teams) on the [ucsb-cs148-w25 Github org](https://github.com/ucsb-cs148-w25).
- given admin access to a project repo for your team

Today, you'll also again be working in groups with your team during the class time.    

# Topics: 
* Overview: Where are you wrt to the project idea and technology possibilities?  
* User Analysis / Task Analysis - the first two steps of any design process. 
* User Stories, Personas, Scenarios: the common language of shareholders 
* Scrum Process 
* Scrum Standup and Github Project Kanban Board 
* Project group Standups and other Scrum coordination. Preparing Sprint00.

# Electronic Handouts:
* Scrum – A Breathtakingly Brief and Agile Introduction: <https://sites.cs.ucsb.edu/~holl/CS148/handouts/Scrum.pdf>
* [Scenario-based Design](<https://sites.cs.ucsb.edu/~holl/CS148/handouts/Slides_ScenarioBasedDesign.pdf>). 
	
# Background Information: Team Norms 
* Here is some background information and some examples of Teams Norms:
* * <https://www.thebalancecareers.com/team-norms-sample-1919230>
* * <https://www.techwell.com/2012/10/how-team-norms-can-boost-team-effectiveness> 

# Background Information: User Story Mapping
* Part 1 (12:12) (Planning): <https://youtu.be/IsuIZaqnIuU>
* Part 2 (10:15) (Using a Github Project Kanban Board): <https://youtu.be/8U0FezxxMGU>
* Part 3 (16:28) (More User Stories and Issues): <https://youtu.be/lIB0WJzgSs8>

If you want to reference the slides from the videos, they are here: 
* [From User Story Mapping to Kanban in Github](https://docs.google.com/presentation/d/1UD5qIm5njZFF2s8OvCJdJPnsR_VvnavcZRP9cXRqRNw/edit?usp=sharing), a presentation by Phill Conrad and John Cutler

We did not discuss all of the items below in detail, but we mentioned some of them, and will go into more detail
in the weeks ahead.

* Forming teams
* Establishing team norms/procedures 
* Defining user stories / issues
* Defining a minimum viable product
* Setting up a Kanban board
* Assigning user stories to individuals for an iteration
* Completing issues, and doing pull requests
* Code reviews
* Retrospectives



# The Slack: `*_help` channels

On the Slack, we will make available several channels that have the endings `_help`, for example:
* [`#git_help`]()
* [`#js_help`]()
* [`#mobile_help`]()
* [`#unity_help`]()
* etc.

* *If your team would like to see additional help channels on specific topics*, make a suggestion in the new #questions-to-teachingteam Slack channel (you need to browse channels and join this one.)
* *If you want to share a useful article, tip, blog post, video, etc.* about the topic,  post in the `_help` channel for the topic.
* *If you need help* with the topic, i.e. you want to ask a question, post in the channel corresponding with the topic.   You are also encouraged to provide help in the `_help` channel if you think you know the answer to someone's question.

# The `#js_*` channel is for everything JavaScript related

Note that the [`#js_articles`]() and [`#js_help`]() channels will be used for all technologies that relate to JavaScript-based technology stacks, including:
* JavaScript
* node.js
* express
* React
* Cypress testing
* etc.
  
# The `#mobile_*` channels are for everything related to mobile ecosystems and app development
* Android
* IOS
* Kotlin
* Swift 
* ReactNative
* Flutter
* etc.
  
We'll be happy to create more specific channels for more focused help!   

# If you aren't sure, you can always use [`#questions-to-teachingteam`](https://ucsb-cs148-w25.slack.com/archives/C0870BKLUBZ)

A few more special purpose channels:

* Always monitor the channel for your team
* Always monitor the `#announcements` channel, especially *during lecture or section breakouts*

# Absences

If you need to miss class for an unavoidable reason, please notify:
* *FIRST*, your team, on your team channel
* *SECOND*, DM the instructor.

Please send these notifications:
* in advance where possible. 
* as soon as possible after the fact, when advance notification isn't possible.

This is a matter of showing respect for your team.

Then, as soon as possible after the class, *check with your team* to see what you missed. It should be a team responsibility to help one another with unavoidable absences.

Unavoidable reasons might include:
* Being too ill to participate in class
* Family emergency
* Internet outage
* An online job interview that could not be scheduled at another time.

Of course, unavoidable absences should be rare if you are going to remain in good standing with your fellow team members, folks that are depending on you to do your part for the team.

# Breakout work today

Today, during your breakout sessions, you should accomplish the following tasks:

1. Add an initial `README.md` to your github repository (details below)
2. Hold a quick standup meeting and log it on GitHub! 
3. Plan to meet for a Sprint planning meeting (if not done yet) and finish the discussion of your team agreements / team norms and record whatever agreements you are able to reach in `team/AGREEMENTS.md` (details below)

 
# Initial README.md

One member of the group should go to the page for their main project repo, e.g.

* <https://github.com/ucsb-cs148-f21/project-t01-sbrideshare>


On *your own team repo*, click on the web interface link `Add a README`, or, if you see no such buttton, create a README.md file in one of your branches, add, commit, and push it to origin, and create a pull request! 

In your README.md, put the following:

* The name of your project
* A one sentence description of your project
* A list of the full names and github ids of the members of your project team

# Holding and capturing a Scrum Meeting on GitHub: Start documenting your team's work

* Elect / designate a `Scribe` for the meeting, a team member who will capture the content of the meeting. 
* Create a `team` directory in your repo (if you haven't already done so)
* In that directory, create a subdirectory `sprint01` 
* Create a file in the `sprint01` directory entitled `lect02.md` (.md stands for mardown language, a simple notation to produce formatted text in ASCII). This is where the meeting notes should go that the scribe takes down:  `./team/sprint01/lect02.md`. For future meetings, you will replace 'lect02' with the respective meeting time denominator (e.g. lab01, lect05 or 04-17-2pm). The notes should state if this meeting was a special Scrum meeting (Sprint Planning, Story Time, Retrospective, or a simple daily Scrum/Standup).

In the meeting notes, write the name of your project, your mentor, and the names of the people on your team (recording who is present, and noting those that are absent.)

Example:

<div style="width: 50em; height: 46em; border: 4px solid #ccc; padding: 1em;" markdown="1" >

# Project: Teaching CS148

Mentor: Self-Mentored ;) 

Meeting Time: lect02 

Type of meeting: <one or several of [sprint planning, daily scrum, sprint review, retrospective, story time]>

Team:  Jamie Lai [ ], Yunhao Luo [x], Yilin Wang [x], Will (Zifeng) Zhang [x], Leo Guo [ ], Anderson Lee [ ], Samuel Zhu [ ], Rachel Jiang [ ], Tobias Höllerer [ ]

*Scribed Discussion:*

  Tobias updated lect02 agenda. Next tasks: h02 is in discussion by the teaching team on Gradescope, prepare Lab02, settle OHs. No current roadblocks

  Rachel Jiang has a conflict for Monday' class. No current roadblocks. 

  Jamie... 

  Yunhao...

  Yilin...

  Will...

  Anderson...

  Samuel...

  Leo...

</div>


Taking attendance for today's lab, and making sure your name is on your log with a [x] or an [ ]  is a portion of your group's grade for this week's lab. 

**NOTE 1**: The first team member listed should be the 'lead' for this meeting, i.e. a team member who is responsible for recording meeting information this time (also called a 'scribe'). In the future, this person likely called/coordinated the meeting. Meeting leads are different from project owner and Scrum master and we expect/require that this responsibility rotates among your team members!

**NOTE 2**: Having a group member (or two) absent will not cause your group's grade to be reduced.  However you are require to *record* attendance
in order for the group to get full credit for the lab. In the future, team members that cannot make it to a meeting should message their information to the meeting lead beforehand.

**NOTE 3** In the future, meeting time can also be something like lect04 (for Lecture 4), or 01-14-2pm for an out-of-class-time meeting.

In your github repository, you will structure the documentation of your meetings into 'sprints' (your team will decide on the Sprint length / interval. Typically, for this class a Sprint is one or two weeks). 

From now on, please document all your meetings in the github repository in this way.

# `team/AGREEMENTS.md`

In addition to the NORMS.md file that is part of the current lab session, please create, in your `team` folder, a file called `AGREEMENTS.md`.

In this file, you'll first put the names of the members of your team.

Then, you'll enter a list of agreements.   These are things that you all agree are good practices for creating a harmonious productive team.

As a suggestion, the first few team agreements, might be these:

1. When one of us is absent for an unavoidable reason, we will let the other team members know on the team slack channel, in advance when possible, as soon as possible afterwards when not.
2. We will each try to keep such absences to a minimum.
3. Those of us that are present will do our best to share with the absent team member(s) what they missed and help them get back up to speed.
4. We will all do our best to contribute to the teams success.

You then might add a few more.    

Consult this article for ideas:

* <https://ucsb-cs148.github.io/topics/teamwork/>


# If you run out of time

If you run out of time, the agreement discussion can be continued outside of class over the slack, and during the next lab and/or lecture.

# If you finish early

If you finish all of the above, start on a discussion of the following things.  These are discussions that will carry over into Wednesday and Friday Section, but you can start them now if you've finished the items above.

Add to your README.md:

* Which tech stack(s) your group plans to evaluate/use
* Planning about what what you want your app to do for the user.


# Which tech stack

We've provided some information for you already, and mentors may have discussed stack possibilities a bit already.  Also, you are using the Hello World requirement of lab01 to get more experience with different platforms! So in some groups, there may be already some consensus on which tech stack to use, others may need a bit more time. In any case, you should still discuss the pros/cons of each, and share your preferences with one another.

If you have questions, or need guidance, ask your mentors and teaching team. 

# Planning your app 

For the second item, focus on writing *a single paragraph* in which you go into a bit more detail about what you plan for your project.

* This is NOT intended to be a full specification of what you are going to build.  It is just an opportunity to *briefly* 
  add a bit more detail that wouldn't fit into the one-sentence description.
* Later this week, we'll be going through some "user-story mapping" exercises to do a more detailed design, 
  so don't get bogged down trying to make this paragraph comprehensive or perfect.  It's just a first step.

Some things to consider:

How many different kinds of users are there, and what are their roles?

Examples: 
* A ride share app mvp has two kinds of users: those looking for rides, and those offering rides.  
  * A third kind of user role you might need is site admins, users that can have the power to delete anyone's posting.
* A game app might have only one kind of user: game player
* A Recipe sharer app might have two kinds:
  * Users that look up recipes, but can't add new data to the system
  * Admins that can upload new data to the system
  * Later, you might also allow user contributed content; in that case, you might want admins to have the ability to delete inappropriate content.

Think about the fact that your app will be available on the public internet.  If your app allows user contributed content of any kind, there is the potential for inappropriate content (spam, or worse) to be added.   One option is restrict your user base to folks with an `@ucsb.edu` login; we can provide example code for both Spring Boot and next.js that you can build on to add this feature to your app.

What will each different kind of user be able to do in your app?
* What are their goals in using their app?
* How does your app allow them to accomplish their goal?

# Future steps: `.gitignore` and `LICENSE.md`

Two future steps will be to also add `.gitignore` and a `LICENSE.md`


The `.gitignore` will depend on your tech stack choice.
* Create a file called `.gitignore` in the root of your repo
* A list of good starting gitignore files is found here: <https://github.com/github/gitignore>
There are also various gitgnore generators out there! 

For the `LICENSE.md`:
* Consult <https://choosealicense.com/>.
* The [MIT license](https://choosealicense.com/licenses/mit/) is a reasonable choice if you don't want to spend too much time troubling over this.
* Create a file called `LICENSE.md` in the root of your repo, and copy the license terms into that file.
