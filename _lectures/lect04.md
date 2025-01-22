---
desc: "Project Management: README.md, Leadership, Retros, Learning plan"
lecture_date: 2025-01-22
num: lect04
ready: true
---


Announcements:  
* H02 was due today. New [h03](https://ucsb-cs148.github.io/w25/hwk/h03/)(Retrospectives) posted, due on Monday, but go over it before Friday, to get informed about Retros before you do the assigned one. 
* Work on [lab02](https://ucsb-cs148.github.io/w25/lab/lab02/)
* MVP Code Freeze amended again (to Mon. 02/03) 
* Sprint Planning! 
* #lessons-learned channel

# Today

Brief discussion of team leadership roles
- Leading a team MVP, story grooming discussion
- Leading a Retro 
- Giving a class presentation
- etc.

Brief discussion of retros
- Choose *today* who will lead your first retro on Friday
- So, let's discuss just enough so that you know what you are committing to
- <https://ucsb-cs148.github.io/topics/retros/>

# Team Activity #1 in `team/LEADERSHIP.md`

In your project repo, in file `team/LEADERSHIP.md`
- record who led any previous planning meetings
- schedule, and record who has led / will lead your current Sprint planning meeting
- record who will lead the full first team retro (Friday)

You can use a Markdown table to make this easy to read.  It's fine to just record this directly on the `master` branch, even editing directly in the GitHub web interface.

Example:

```
# Leadership roles

| Date      | Name              | Activity                                               |
|-----------|-------------------|--------------------------------------------------------|
| Mon 01/06 | Chris Gaucho      | Led team discussion to define MVP                      | 
| Tue 01/07 | Lauren del Playa  | Led team discussion of Sprint01 and learning plan      | 
| Fri 01/24 | Taylor Chen       | Will lead first Retro                                  | 

```

# Team Activity #2 in `team/LEARNING.md`

* Discussion of learning your technologies
  - You should not be relying on us to "teach you" next.js or Flask or Flutter or Unity
  - In your team, discuss: current level of familiarity with team's chosen tech stack
  - Discuss: how you as a team will learn the necessary skills
* Record in `team/LEARNING.md` a plan for learning the skills
  
# More on the learning plan

The format of the learning plan is up to the team, as long as it includes the following:

* A brief assessment of the team's existing strengths
  - Are there folks on your team that already have skills in one more important areas?
  - Can these folks help to onboard and train some of the other team members?
  - Can you "stategically pair"
* An brief assessment of areas where the team needs to develop it's knowledge
  - What are the most signficant gaps in your team's knowledge?
* A plan that includes specific committments by each team member (by name) as to what they will do over the next 
  week (week 3) and the following week (week 4) to improve their skills

The plan could include things like:

* John commits to working through a tutorial on basic HTML/CSS during week 3, and a tutorial on React and React-Bootstrap during week 4.
* Susan commits to working through a tutorial on MongoDB during week 3, and learning how to work with MongoDB in a Next.js app during week 4.
* Alice and Bob will pair together during the MVP iteration, since Alice has more experience with the tech stack.  Alice and
  Bob will use strong-style pairing with Bob at the keyboard as much as possible, until Bob feels confident. 
  
An ideal plan will incorporate both breadth and depth:
* breadth involves baseline skills: everyone on the team should at least have certain baseline skills in the tech stack
* for depth, use divide-and-conquer: not everyone on the team needs to be a deep expert in everything


# A *Partial* List of important technologies, by Stack

You might use [the technology list we pointed you to](https://docs.google.com/document/d/1zclZUWWnAu6cXh5_b4wvkVKJ6Ch_OAagchXqigEzmZQ/edit?usp=sharing) before and the pointers in our Slack `_help` channels to come up with ideas for your `/team/LEARNING.md` file.

Also, think about any project-specific APIs, data sources, etc. Your project may have specific APIs, data sources, specialized skills etc. that you may need to work with.
It may helpful to identify the ones needed for your project, and be sure that at least one team member is looking into each of those.

Examples:

Spotify API <https://developer.spotify.com/documentation/web-api/>
Low level <canvas> element access for game element graphics, or frameworks that allow it
Pusher (for real-time communication between the server and the client, e.g. for real-time chat, games, etc.) <https://pusher.com/>
Mapping/Routing services such as <https://openrouteservice.org/services/> and OpenStreetMap (Note that Google Maps is awesome, but it may be tough to get free access for web apps. It should be free for Mobile apps, but may require a credit card regardless.)
Reading data files into usable application data
Hard coded data objects for very small tables
Databases (Firebase, SQL, or MongoDB) for larger tables


## Spikes, Skunk-works, Proofs of Concepts

You are not only permitted, but *strongly encouraged* even, to make *additional repos* in addition to your main project
repo that contains extra "proof of concept", and "practice code" for your project.

These are sometimes called *spikes*.

You can name these with private or public repos in the `ucsb-cs148-w25` github org names such as `spike-t1-try-spotify-api` and then give your team access to them.

You may want to make such repos part of your learning plan.

# If you have extra time

* Kanban board column (if not *fully* done)
  - If the Kanban board column for [lab02](https://ucsb-cs148.github.io/w25/lab/lab02/) is not complete (i.e all stories groomed with clear acceptance criteria), work on that.   
  - This should be finished by Thursday if possible, Friday midnight *at the latest* so your team is making progress! Note that Friday's Section will be all taken up by the First Retrospective
* Finish anything you were "in the middle of" when time ran out last meeting.
* If that's done, choose either:
  - Get started on the learning plan
  - Futher definition on iterations towards your MVP
  
