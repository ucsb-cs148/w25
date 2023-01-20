---
assigned: 2023-01-20 12:00
desc: Kanban Boards towards MVP Demo Video
due: 2023-01-27 23:59
due_2_weeks: 2023-02-03 23:59
layout: lab
num: lab02
ready: false
github_org: ucsb-cs148-w23
---

<div style="display:none">
https://ucsb-cs148.github.io/w23/lab/lab02/
</div>

<style>
div.grade { margin: 2em; padding: 1em; border: 2px solid #0c0; background-color: #efe; }   
</style>

<div style="float:right; width: auto;">

<table style="margin-top:1em;">
<tr>
   <th>Points</th>
</tr>
<tr>
   <td class="pointCount"></td>
</tr>
</table>

</div>
<br>



lab02 is a team-based grade for several check points towards the MVP demo.

 * Make sure your README.md contains a paragraph about the tech stack you are planning to use, as well as mention user roles (see [this description](https://ucsb-cs148.github.io/w23/lab/lab02-addendum))
 * Kanban board: 
    * There should be a Kanban board (a Github Project associated with your repo) for your team
    * That Kanban board should have a complete set of user stories on it, that, when complete, results in a minium viable product for
   your app; one that clearly delivers value to the user.   User stories should be plain old "cards" on the Kanban board.
    *  There should be a complete set of issues for each of those user stories; a set of issues that are specific TODO's that a individual, pair, or 
   sub-group of your project team can pick up and start coding from.  Each of those issues should have a clear set of criteria for
   what it means to be "done" with that issue.
    * As a team, you've settled on the work you are going to do after the Hello World phase to move towards your minimum viable product (MVP), and you've put user stories and issues in your In-Progress column for each team member.


<div class="grade" markdown="1">
 
**Graded: ({{page.num}}-T)** (10 pts) When at least one Sprint Planning meeting took place and was documented in a team/sprint0?/ folder in your main repo (question mark for number of your current sprint, which may vary from team to team). For the purpose and mechanisms of a Sprint Planning meeting see, e.g., pages 25-27 of [our Scrum booklet](https://sites.cs.ucsb.edu/~holl/CS148/handouts/Scrum.pdf).

**Graded: ({{page.num}}-I)**: (10 pts) You earn these points if/when you, within one week from the start of this assignment (i.e. by {{page.due |  date: "%a, %b %d at %l:%M%p"}}):

* are assigned to an issue that has been moved from To-Do to In-Progress to Done on the Kanban board, tracking the progress of your issue from start to finish.

Note that each time an issue is moved or assigned, the date/time is tracked; so for full credit, this should be done "in real time" as you work on the issue, not "after the fact".   We'll assess this to encourage you to get in the habit of doing it in real time as you work; doing it that way has benefit to the team.   When you do it in real time, the Kanban board reflects the state of the project, and gives the team a way to visualize the status of what's going on.

But doing it "after the fact" is better than not doing it at all; if nothing else, it helps you learn the mechanics to that you can know better how to do it next time.  So if you forget to do it as you work, go back and do it, going through the motions.  This will earn you partial credit, which is better than getting a zero for this part.

**Graded (lab02-T)**: is your Team grade for {{page.num}}.  As part of this grade:

* (20 pts) Your README.md file is updated with information about your technology stack and approach, as well as listing user roles (see [this description](https://ucsb-cs148.github.io/w23/lab/lab02-addendum))  
* (10 pts) There should be at least one user story in the In-Progress or Done column for your team. If there is more than one in the In-Progress column at any given time, it is because the issues for the first one are insufficient to keep the team making progress, and it was necessary to bring over a second one to have enough issues to work on.
* (10 pts) There should be at least one issue under each user story that supports implementing that user story.
* (20 pts) Each user on the team should have been assigned to at least one issue in the in-progress column.   
   For teams of 6, this part of your grade is 3.3 points per team member.  For teams of 7, it is 2.9 points per team member, for teams of 8 it is 2.5 points. 

This component of your team grade is designed to encourage each team member to reach out to all the other members of the team, and be aware of the progress they are making towards the goal of having every team member be making a contribution to the project.  The most important learning goal of the course is to learn to work as a team, supporting one another.

</div>

# About assigning issues to team members

It is possible to assign multiple users to an issue.

You may work on issues either:
* as an individual
* as a pair
* as a "mob" (like pair programming, but with more than one person)

However, if you are working as a pair or a mob, you should *really* be
working as a pair or a mob.  That is, you should plan times to get
together, ideally in person, but at least via screen sharing, and work
together on the code.

What we don't encourage is for Alice and Bob to be assigned to the
issue, and then Alice and Bob take turns "solo programming" on the
issue.  That's a way of working but not the one we are encouraging you
to pursue.

# About limiting work in progress

Throughout the rest of the course, up until we wrap things up with the final project delivery, you are encouraged to:
* ensure that each team member, at all times, is assigned to at least one in-progress issue
* limit the number of in-progress issues.  

Being assigned to more than one in-progress issue is occasionally unavoidable, but typically not ideal.  An example of a case where you may be tempted to do it is when you are blocked on an issue (e.g. waiting for someone else to finish something you need). In that case, you might decide to start another issue so that you are assigned to two in-progress issues at a time.  

But the experience of most teams is that it's best to try not to do this too often.  

Context switching among issues has a cost, and having lots of work in progress can slow a team down further and complicate the delivery of working software that adds value for the user.

# Finally: Choose a leader for next week's retrospective

Choose a leader for next week's sprint retrospective.  That sprint retrospective will take the entire lab period next week.  Attendance at that 
lab is therefore particularly important.  

* Put the name of that leader in a card in the "TODO" column of your Kanban board, e.g. "Chris will lead team in first Retro"

Note, for full course credit, each of you needs to take a turn taking a leadership role in some activity.  
   * If you don't lead a retro, you can be product owner, scrum master, or make a class presentation at some point.
   * So you are encouraged to volunteer.  
   * Once you've led one retro, you'll have fulfilled your duty to exercise leadership at least once. You will likely be able to hold 3, or perhaps 4 retrospectives in total. 
   
<div class="grade" markdown="1">
**Graded ({{page.num}}-T)**: towards the team part of your grade for {{page.num}}.  

This part of the team grade is for the mechanics of:
* (10 pts) naming a retro leader for the [lect05](https://ucsb-cs148.github.io/w23/lectures/lect05/)) retro and record their name in your new LEADERSHIP.md file (described in [lect04](https://ucsb-cs148.github.io/w23/lectures/lect04/)). Also list there the leaders for previous and scheduled Sprint planning meetings, and other major coordination meetings. 
* (10 pts) your LEARNING.md file (described in [lect04](https://ucsb-cs148.github.io/w23/lectures/lect04/)) is filled with information about your tech stack background and learning trajectory.  
</div>
