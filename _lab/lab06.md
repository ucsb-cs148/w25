---
layout: lab
num: lab06
ready: false
desc: "Second Retrospective, Product Improvement, Additional Testing"
assigned: 2023-02-17 12:00
due: 2023-02-24 23:59
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


# Grading for Second Retro

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-I) (20 pts) You earn these points for submitting feedback on overall team performance via a second CATME.org form survey that you will get email invitations for.

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points based on the logged attendance/participation in your second retrospective; 20/n points per team member for teams of n participants.

**Graded**: ({{page.num}}-T) (10 pts) You earn these team points when the content in `team/RETROS.md` is updated per the instructions.

**Graded**: ({{page.num}}-T) (10 pts) You earn these team points for ensuring that each team member was again assigned at least one issue that was moved to the Done column of your Kanban board with tested acceptance criteria over the next week **ending on 02/14/21, 14:00:00 PDT**.

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points if your team integrated a higher-level (not just unit tests) testing framework with your project

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points if your team implemented and demonstrated successful execution of **at least one** component test **or** other integration **or** end-to-end test (e.g. BDD) in your project. 

</div>


# Second Retrospective

Either today, or at a time you schedule by you as a team, you will hold your second retrospective 

You already know the goal and procedure for Retrospectives from your RETRO_01. This Retrospective allows you to discuss things that emerged from the MVP effort and feedback you received.

* You'll do a quick standup and then either do the retro in team groups or schedule it and work on other lab requirements. 
* When you are finished and still have time, discuss your team's strategy towards the testing requirement in this lab.   
* Staff will be dropping in to observe.

# Retro Deliverable

* In your team's repo, under `team/retrospective` directory
  Add file `RETRO_02.md` (or whatever number you are at if you did other retros already)

* Add a section:

  ```
  # Retro #2 10/29/21 

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
  ## Retro Assessment

  * A brief description of what retro outline or process you used.
  * A brief assessment of how it went.
  * What advice would you give to the next person leading a retro
    based on what you learned today?
  ```

# Grading for new Development / Testing 

Over the next week, please focus predominantly on **new/improved functionality/robustness/user experience** for your product, using your momentum and ideas from the MVP effort and discussion. 

Again, every team member should be assigned (and complete at least one) new issue towards this goal. Make sure that your issues have clear acceptance criteria in Github Projects and that you have a process for completing and assigning issues (e.g. feature branches or your own "Continuous Delivery" rules). It should be possible at any point in time to deploy your product with new improvements over time! 

So, while focus should be on your product growing/improving, we want you to experiment more with Test-Driven-Development (TDD). This could be a great week to fully embrace TDD, and we think you would get many benefits from it in the long term. It is, however, an investment in the short term, so if you don't think that you are ready to completely switch over to TDD, then at the very least you'lll have to select a tool for component testing (a type of integration or end-to-end testing) and implement **at least one** component test **or** other integration **or** end-to-end test in your source code. Use of a Behavior-Driven Development (BDD) framework would also check this box.  

Teams working with React could use the [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/) or [Enzyme](https://enzymejs.github.io/enzyme/) or [Storybook](https://ucsb-cs148.github.io/jstopics/react_storybook/). Python backends could for example be tested with [TestProject](https://testproject.io/) or the BDD frameworks [Behave](https://behave.readthedocs.io/) or [Lettuce](http://lettuce.it/).

 