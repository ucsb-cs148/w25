---
layout: lab
num: lab03
ready: true
desc: "First Retro and MVP Preparation"
assigned: 2023-01-27 12:00
due: 2023-02-03 23:59
due_2_weeks: 2023-02-09 23:59
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


# Grading for First Retro Participation and MVP Preparation

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-I) (5 pts) You earn these individual points if you participated in the first retrospective.

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points based on the attendance/participation in your retrospective; 3.33 per team member for teams of 6, 2.86 per team member for teams of 7,  2.5 points per team member for teams of 8.

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points if by the due date the content in `team/retrospectives/RETRO_01.md` is updated per the instructions below.

**Graded**: ({{page.num}}-T) (10 pts) You earn these team points if by the due date you recorded the outcome of (one of) your Retro experiments in `team/retrospectives/RETRO_01.md`.

**Graded**: ({{page.num}}-I) (20 pts) You earn these points for submitting feedback on overall team performance via a CATME.org form survey that you will get email invitations and reminders for.

**Graded**: ({{page.num}}-T) (15 pts) You earn these team points if your team posted, or commented on already posted, articles or tutorials in at least one of the `..._help` channels. You need at least 3 such interactions (posts or comments) to get full credit. Please document that you (which members of your team?) did these posts or comments in your LEARNING.md file. 

**Graded**: ({{page.num}}-T) (10 pts) You earn these team points if the [team links spreadsheet](https://docs.google.com/spreadsheets/d/1dXhvtRPpwhPkopjN_JF59bV_RtqDguA2QaIEntIMFLk/edit?usp=sharing) is updated with all the requested links to your repo information.  

</div>

# Procedure for First Retro

You may or may not have done an official `Sprint Review` meeting yet. In a way, you are doing those via your check-ins with your mentors and that is sufficient in a pinch, but we encourage you to hold and log official Sprint Review meetings at the end of each of your Sprints. In any case, you should have enough information about what worked and didn't work in your Sprint(s) so far (and from your homeworks) to hold your first Retrospective meeting today! 

# Today: Retrospective

* As always, you group into teamwork. You know from your homework, from [the Retro entry in Topics](https://ucsb-cs148.github.io/topics/retros/) and from page 33 in the [Scrum booklet](https://ucsb-cs148.github.io/w23/hwk/h05/) how to do hold a retrospective meeting. Now do it. You get points for the deliverables listed on this page. 
* When you are finished with the Retrospective, you are free to coordinate further as a group towards your MVP. Help each other with pointers on technologies you are experimenting with!  
* Staff will be dropping in to observe.

# Deliverable  

* Add to your team's repo, under `team` directory a folder called `retrospectives`
* Create a file `team/retrospectives/RETRO_01.md`


* Add the following information:

  ```
  # Date of Retrospective: 01/27/23

  * Led by: name-goes-here
  * Present: name1, name2, ... , nameN
  * Absent: name1, name2, ...

  ## Action item

  * a goal: identify something the team wants to get better at
  * a change: identify one thing that the team will change about how it works together
  * a measurement: identify at least one way to measure whether the change helped the team achieve the goal, or move closer to it.

  ## Optional

  * Record anything else you think the team might want to remember from this retro

  ```

 
* After the Retro
  
  **Retro leader**: add Section to `team/retrospectives/RETRO_01.md`
  
  ```
  ## Retro Assessment

  * A brief description of what retro outline or process you used.
  * A brief assessment of how it went.
  * What advice would you give to the next person leading a retro
    based on what you learned today?
  ```

# Two weeks to MVP Code Freeze and peer review. Please prepare: 
## Planning your demo (MVP video)

* Plan an up-to-five minute presentation video
* Please prepare a max. 5 minute YouTube video (unlisted or public, your choice)
  - See the [bottom of this page](#mvp-demo-due-pagedue_2_weeks) for information about creating your MVP video.
  - Links to videos will be made available to (some of) the class for peer review, but will not be made public
* Present to an audience of **potential users**
  - Not to an audience of CS148 students, or the instructor or TAs.
  - Explain what problem the app solves, or what need it fulfills, as you demo the features of
    the app.
* Stay focused on user functionality.
  - Do not go into details of implementation, or team process.
  - There will be other presentations for that.
* Optionally, you may introduce with a powerpoint slide, and/or close with one, but the bulk
  of the time, you should be sharing your screen and showing us your app.
* At the end, tell us a bit about upcoming features planned for the next iteration.

In lab05 in two weeks' time you'll be asked to evaluate other teams' presentation(s), so plan to watch them and be ready to do some very brief writing after each one.

## Point us to your video
*  create a file `team/MVP_DEMO.md` containing your MVP video link and any additional information you see fit that you think doesn't belong in the project's README.md  

## Add the following information to your README.md: 

> ===================================================================================
>
> ## Installation 
> 
> ### Prerequisites
> 
> TODO: List what a user needs to have installed before running the installation instructions below (e.g., git, which version(s) of your framework(s) of choice)
>
> ### Dependencies
>
> TODO: List which libraries / add-ons you added to the project, and the purpose each of those add-ons serves in your app.
>
> ### Installation Steps
> 
> TODO: Describe the installation process (making sure you give complete instructions to get your project going from scratch).
> Instructions need to be such that a user can just copy/paste the commands to get things set up and running. Note that with the use of GitHub Actions, these instructions can eventually be fully automated (e.g. with [act](https://github.com/nektos/act), you can run GitHub Actions locally). 
> 
> ## Functionality
> 
> TODO: Write usage instructions. Structuring it as a walkthrough can help structure this section,
> and showcase your features.
> 
> ## Known Problems
> 
> TODO: Describe any known issues, bugs, odd behaviors or code smells. 
> Provide steps to reproduce the problem and/or name a file or a function where the problem lives.
> 
> ## Contributing
> 
> TODO: Leave the steps below if you want others outside your team to contribute to your project.
> 
> 1. Fork it!
> 2. Create your feature branch: `git checkout -b my-new-feature`
> 3. Commit your changes: `git commit -am 'Add some feature'`
> 4. Push to the branch: `git push origin my-new-feature`
> 5. Submit a pull request :D
> 
> ## License
> 
> If you haven't already, add a file called `LICENSE.txt` with the text of the appropriate license.
> We recommend using the MIT license: <https://choosealicense.com/licenses/mit/>"
> 

# MVP Demo, due {{page.due_2_weeks}}

The YouTube video <https://youtu.be/k0Je8ASh4jo>
explains how you can create an MVP demo video using Zoom and YouTube:

<iframe width="560" height="315" src="https://www.youtube.com/embed/k0Je8ASh4jo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[This page](https://ucsb-cs148.github.io/w23/exam/mvp_code_freeze_and_release/) tells you how to document and list the link to your demo when it is complete.   The video may be public, or "unlisted", as you see fit.
Links to videos will be shared with the class, but the class is asked not to share links to non-public videos (unlisted videos)
with people other than enrolled students and course staff.

Your video should be no longer than 5 minutes and should follow these instructions:

## Demo of your production app

Your demo should be from your production app (e.g. `prod` on Heroku), not from a version deployed on `localhost`.

Students in the class, as well as Instructors/TAs/LAs should be able to visit your production link and try out the app after watching your video.

So, make every effort to have your production version ready to go with a stable MVP for the deadline lab section.

## Additional notes about the MVP demo

1. **Features beyond MVP are fine**  Note that if you have moved your production version on main "beyond" your MVP, 
   that's fine; as long as it contains all of the MVP functions.   If you are time restricted, you can focus the demo
   just on the MVP features and "save" the rest for later.
   
2. **Broken `main` is a problem.  You can fix with a `temp-prod` branch**.   
   If your `main` branch is currently "broken" in 
   some way that makes it impossible to do a decent demo from your `prod` Heroku app, then here's a quick fix:
   
   - (a) find an earlier commit that isn't broken 
   - (b) give that commit a branch name `temp-prod` for example 
     - use: `git checkout -b temp-prod` 
     - then `git reset --hard a1b2c3d4` where `a1b2c3d4` 
       is the sha of the commit that's good; 
     - then `git push origin temp-prod -f` 
   - (c) redeploy your prod app using `temp-prod` instead of the main branch.
   
   If you do this, please disclose that you are demoing from `temp-prod` and not main in your lab02 submission 
   so that we aren't confused when evaluating your MVP.  
   
   It's not ideal, but it won't be a major deduction.  It's better than demoing a broken `main` branch.
   
3. **A demo from `localhost` is better than nothing, but isn't really an MVP demo**.   If you absolutely 
   *cannot* do a meaningful demo from your production app, then you may demo from `localhost` as a last resort, rather
   than offering no demo at all.   However, that will result in a lower grade; 
   a localhost app isn't really "viable" in the sense that you can't put it in the hands of customers.   
