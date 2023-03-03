---
layout: lab
num: lab08
ready: false
desc: "Start Manual, User Stories and Issues towards Final Release, Retro 3"
assigned: 2023-03-03 12:00
due: 2023-03-10 23:59
github_org: "ucsb-cs148-w23"
---

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

<div class="grade" markdown="1">
**Graded**: ({{page.num}}-T) (40 pts) You earn these team points if you started a user manual document that you link to in your Github ./docs/MANUAL.md and that contains at the very least a description of the product purpose, lists the intended user audience, and has section headings (which are allowed to change later on) with placeholder information (could even be [Lorem Ipsum text](https://www.lipsum.com/) for now) that in the future should document the various features of your product and how to operate them (with plenty of screenshots).  

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points based on the attendance/participation in your third and last retrospective some time over the next week as fits your Sprint cycle; 20/n per team member for teams of n members.

**Graded**: ({{page.num}}-T) (40 pts) You earn these team points for ensuring that each team member was again assigned at least one issue that was moved to the Done column of your Kanban board with tested acceptance criteria over the next week ending on due date. For full credit, you must add a tag reading Lab08 to each issue you move to the Done column. Every team member should also be assigned to at least one issue from your user stories towards final release at all times. 
</div>


# Start User Manual Document
Start a User Manual Document (as a Google Doc or another `living document` format of your choice) and link to it in a new ./docs/MANUAL.md file in your GitHub. 
It should start with a paragraph explaining the purpose and intended user audience for the product (it can share some of this information with your README.MD, but the manual should be entirely oriented towards end users and should make no mention of implementation details that are not relevant to the end user experience).   


# Third (and last) Retrospective 

You will get time on Tue, 03/07, to hold your third and last team Scrum Retrospective, but you can move the time of this meeting to whatever time within this lab period your team prefers, including right this lab session (03/04). Note though that lab09 (03/10) section time may be taken up by some team activity towards UX testing. 
Make sure you have a Retro leader assigned (should be the case since it was part of the Leadership review last lab).

You already know the goal and procedure for Retrospectives from your RETRO_01 and RETRO_02. This Retrospective allows you to discuss things that are relevant on your final stretch to product deployment, documentation, and presentation.


* In your team's repo, under `team/retrospectives` directory, add a file `RETRO_03.md` (or whatever number you are at if you did other retros already) capturing the following:

 ```
  # Retrospective your-nr-goes-here, date-goes-here 

  * Led by: name-goes-here
  * Present: name1, name2, ... , nameN
  * Absent: name1, name2, ...

  ## Action item

  * a goal: identify something the team wants to get better at
  * a change: identify one thing that the team will change about how it works together
  * a measurement: identify at least one way to measure whether the change helped the team acheive the goal, or move closer to it.

  ## Optional

  * Record anything else you think the team might want to remember from this retro

  ```

* After the Retro
  
  Retro leader: add
  
  ```
  # Retro Assessment

  * A brief description of what retro outline or process you used.
  * A brief assessment of how it went.
  * What advice would you give to the next person leading a retro
    based on what you learned today?
  ```
 