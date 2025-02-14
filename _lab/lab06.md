---
layout: lab
num: lab06
ready: true
desc: "Higher-Level Testing, UX Planning, Second Retrospective"
assigned: 2025-02-14 13:00
due: 2025-02-21 23:59
github_org: "ucsb-cs148-w25"
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


# Lab06 points, overview:   

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-T) (30 pts) You earn these team points if your team integrated a higher-level (not just unit tests) testing framework with your project and implemented and demonstrated successful execution of **at least one** component test **or** other integration **or** end-to-end test (e.g. BDD) in your project. Document your testing approach by extending your `team/TESTING.md` document. In combination with last week's requirements, list there at a minimum: **1)** how you implemented the unit test requirement from the previous lab (which testing library, which part(s) of the code, etc.), **2)** your plans regarding unit tests going forward (it's ok to not go all in with unit tests, but document and reason your decision.), **3)** how you satisfied the component/integration/end-to-end testing requirement from this lab (which testing library, which part(s) of the code, etc.), **4)** your plans regarding higher-level testing going forward (it's again ok to not commit to an integrated testing solution, but document and reason your decision).  

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points if you list in a new `team/evaluation/USER_FEEDBACK_NEEDS.md` document (in priority order) three things about your product that you would love to have user feedback on. Just to give example possibilities: user preference between two designs, an A/B study on the consequences of two designs, user satisfaction with a particular feature, user satisfaction with your overall current product, but there are many more possibilities. 

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points based on the logged attendance/participation in your second retrospective; 20/n points per team member for teams of n participants.

**Graded**: ({{page.num}}-T) (10 pts) You earn these team points when the content in the `team/retrospectives` directory is updated per the instructions.

**Graded**: ({{page.num}}-I) (20 pts) You earn these points for submitting feedback on overall team performance via a second CATME.org form survey that you will get email invitations for.
</div>

# Grading for new Development / Testing 

Over the next week, please focus predominantly on **new/improved functionality/robustness/user experience** for your product, using your momentum and ideas from the MVP effort and discussion. 

Again, every team member should be assigned (and complete at least one) new issue towards this goal. Make sure that your issues have clear acceptance criteria in Github Projects and that you have a process for completing and assigning issues (e.g. feature branches or your own "Continuous Delivery" rules). It should be possible at any point in time to deploy your product with new improvements over time! 

So, while focus should be on your product growing/improving, we want you to experiment more with Test-Driven-Development (TDD). This could be a great week to fully embrace TDD, and we think you would get many benefits from it in the long term. It is, however, more work in the short term, so if you don't think that you are ready to completely switch over to TDD, then at the very least you'll have to select a tool for component testing (a type of integration or end-to-end testing) and implement **at least one** component test **or** other integration **or** end-to-end test in your source code. Use of a Behavior-Driven Development (BDD) framework would also check this box.  

Teams working with React could use the [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/) or [Enzyme](https://enzymejs.github.io/enzyme/) or [Playwright](https://playwright.dev/) or [Storybook](https://ucsb-cs148.github.io/jstopics/react_storybook/). Python backends could for example be tested with [TestProject](https://testproject.io/). Any group could use BDD frameworks [Behave](https://behave.readthedocs.io/) or [Lettuce](http://lettuce.it/). There are many more options! 

Document your testing approach in your `team/TESTING.md` document. List there at a minimum: **1)** how you implemented the unit test requirement from the previous lab (which testing library, which part(s) of the code, etc.), **2)** your plans regarding unit tests going forward (it's ok to not go all in with unit tests, but document and reason your decision.), **3)** how you satisfied the component/integration/end-to-end testing requirement from this lab (which testing library, which part(s) of the code, etc.), **4)** your plans regarding higher-level testing going forward (it's again ok to not commit to an integrated testing solution, but document and reason your decision).

# User Feedback Needs

For our planned **Inter-Team Evaluation** on 02/26/25, please make sure you have a version (or versions) of your product deployable that allows an evaluator team to give you feedback on specific questions you'd like resolved. Towards this end, over the next week: 

List in a new `team/evaluation/USER_FEEDBACK_NEEDS.md` document (in priority order) three things about your product that you would love to have user feedback on. Just to give example possibilities: user preference between two designs, an A/B study on the consequences of two designs, user satisfaction with a particular feature, user satisfaction with your overall current product, but there are many more possibilities. 

The more specific you can be on these items, the better. You get the points just for the ideation, but the idea is that this process facilitate and help you prepare one of the evaluations you list for the inter-team project evaluation exercise on 02/26/25, and the other team will actually try to answer your question while testing your deployment. Basically, you have 7 user study participants, the other team's members, at your disposal for concrete feedback. Presumably, you will prepare your top priority user feedback solicitation, but maybe a different option if the top priority is not feasible to be evaluated by 2/26. 
 

# Second Retrospective

**Schedule your next retrospective!** You can do it today, or next Wednesday in class, or next Friday, or at a time outside of class, but you need to do it before the end of next Friday to get these lab points.  

You already know the goal and procedure for Retrospectives from your previous Retrospective(s). This particular Retrospective allows you to discuss things that emerged from the MVP effort and feedback you received.

* You'll do a quick standup and then either do the retro in team groups or schedule it and work on other lab requirements. 
* When you are finished and still have time, discuss your team's strategy towards the testing requirement in this lab.   
* Staff will be dropping in to observe.

# Retro Deliverable

* In your team's repo, under `team/retrospectives` directory
  Add file `RETRO_02.md` (or whatever number you are at if you did other retros already)

* Add the following content:

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
  &nbsp;


- After the Retro

  **Retro leader**: add Section to `team/retrospectives/RETRO_0?.md` (use the correct number of your Retro)

  ```
  ## Retro Assessment

  * A brief description of what retro outline or process you used.
  * A brief assessment of how it went.
  * What advice would you give to the next person leading a retro
    based on what you learned today?
  ```
  &nbsp;

- Experiment Outcome Documentation 

  The team gets 10 lab points (see above) for documenting the experiment in `team/retrospectives/RETRO_0?.md`. Describe the experiment/change soon after your retro, and fill in the outcome and decision for the future when you have the results (insights) from the experiment: 
  ```
  ## Experiment/Change

  * A brief description of what constitutes your change/experiment
  * A brief assessment of how its results (did it improve things? move the needle at all?)
  * A decision going forward: keep the change, revert to previous procedure, make a new change? 
  ```

