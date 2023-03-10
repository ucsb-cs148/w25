---
layout: lab
num: lab09
ready: true
desc: "Final Stretch, Final Code Release"
assigned: 2023-03-10 12:00
due: 2023-03-17 23:59
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

The following points will be awarded for participation in UX evaluation activities on **Tue, 3/14, 3:30-4:45pm**:
**Graded**: ({{page.num}}-I) (15 pts) You earn these points for performing UX evaluations (of other projects) the teaching team has lined up for you during class on 3/14.   

The following graded items will be due on **Fri, 03/17, 23:59:59**: 

**Graded**: ({{page.num}}-T) (20 pts) Final Github Code Release and Deployment (tagged release of binaries in repo) by **Fri, 03/17, 23:59:59**.


The following graded items will be due on **Tue, 03/21, 23:59:59**: 

**Graded**: ({{page.num}}-I) (20 pts) Team (coordinating on one response or by submitting individual commentary) documents team roles and github contributions.

**Graded** : ({{page.num}}-I) (20 pts) You earn these points for submitting feedback on overall team performance via a third and last CATME.org form survey that you will get email invitations for. The submission deadline is **Mon, 03/20, 11:59pm**.

**Graded**: ({{page.num}}-I) (15 pts) Every student lists at least one insight in `#lessons_learned` Slack channel.

The following graded items will be due on **Thu, 03/23, 23:59:59**: 

**Graded**: ({{page.num}}-I) (10 pts) Every student submits their favorite 3 projects in the audience choice awards voting (will be announced on Friday, 03/24 via Slack). 

</div>



# Final Code Release and Deployment

Look back on [Lab04 MVP Tag/Release instructions](https://ucsb-cs148.github.io/w23/lab/lab04/) to remind yourselves on how to do a tag and release and do a "Project Demo" Tag and numbered Release for your Code Freeze by **Fri, 03/17, 23:59:59**.

By the same deadline, add a `#Deployment` section at the bottom of your README.md, which points to a live testable version of your project, either on your deployment platform of choice, or to platform binaries (e.g. hosted on Google Drive). 

The deadline for your Manual and for the Design Document remains the coming **Fri 03/24, 23:59:59**, a day after the live project demonstration.

# Team Roles and Github Contributions

We ask every team to comment on the code contributions that every team member made. You already documented leadership roles within the team management (in team/LEADERSHIP.md), and now we ask you to document the roles the team members played in the code development effort. You can comment on team contributions otther than coding as well. In your github team folder, please create a `contributions` subfolder. 

By **Wed, 12/08 23:59:59**: finalize brief commentary on team member code (and/or other) contributions in `team/contributions/CONTRIBS.md`: 
*each team member* should initially write their own section.    
  - Suggestion: each team member should initially create a draft of their part in `team/contributions/contrib_Alice.md`, `team/contributions/contrib_Bob.md`, `team/contributions/contrib_Carol.md`, `team/contributions/contrib_Danny.md`...
  - Then: the person asseembling the overall CONTRIBS.md report can copy/paste those separate files into one unified CONTRIBS.md file.
* Today: Review and discuss the `/graphs/contributors` report for your project repo.    
  - You can find it by clicking "insights" then "contributors".
  
## Is the `Contributors` graph accurate?

Note that there can be disparities between the contributors graph and ground truth code contributions by teeam members. Some groups may have chosen to follow a pair programming approach, and consistently only one member may have done the commits. Or a team member may have used different github accounts when interacting with the code base. Whatever the situation, it is too late to fix the commits, but it's NOT too late to offer an explanation in your team/contributions/CONTRIBS.md commentary.
* We are going to look at the data on the `/graphs/contributors` for your repo, but
* We are going to look *more* at your explanation of that data.

If the data and the explanation match, it's all good.

If you have a team member that you suspect has made lots of commits that are not being attributed to them, 
scroll through your commit log and see if you can find a few examples.

If the commits look ok, but don't tell the full story (e.g. a team member may have just contributed very few, but very important commits), you can bring that out in your commentary, too. 

Even distribution of the coding effort among all team members is definitely not expected, but highly uneven contributions, especially when paired with potential team dissatisfaction expressed through the catme.org surveys may be grounds for individual weighting of the project grade component among team members.   

# All Team members: Fill out third and final CATME.org peer eval survey (by **Mon, 03/20, 11:59pm**)

You earn 25 individual points for submitting feedback on your team mates' and overall team performance via a third and last CATME.org form survey that you got email invitations for. 


# Lessons Learned 

Every student will post at least one "I wish I had known it when I started" lesson learned in our #lessons_learned Slack channel. 
Examples: 
* During a rebase, *just rebase*.  Don't make changes (i.e. fix bugs, add features) during a rebase. Only focus on fixing merge conflicts. Make your changes to fix bugs or add features before the rebase, or after the rebase, but *not during*.
* Making sure to listen to your team mates and give everyone a chance to feel like they are a part of the team, because the internal team work and how everyone contributes is crucial to the team's effectiveness and success. 
* The `git bisect` tool [can help you figure out](https://git-scm.com/docs/git-bisect) with what commit you introduced a crucial change in your repository. 


# Participation in Audience Choice Award

On **Thu, 03/23, 4pm-7pm**, you will follow all project demonstrations and interactive Q&A during our final slot project presentation session and submit the Google Form after that.  In order to receive the last individual 10 lab points, your vote needs to be submitted by **Thu, 03/23, 23:59:59**.  