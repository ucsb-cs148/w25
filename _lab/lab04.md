---
layout: lab
num: lab04
ready: true
desc: "MVP Release, MVP Review, Acceptance Tests"
assigned: 2025-01-31 13:00
due: 2025-02-07 23:59
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


# Finalize MVP Materials ([lab03](https://ucsb-cs148.github.io/w24/lab/lab03) requirements) 

## Finalizing your demo (MVP video)

* Plan a five minute presentation video
* Please prepare an up-to 5 minute (likely more around 3 minute) YouTube video (unlisted or public, your choice)
  - See the bottom of the [lab03](https://ucsb-cs148.github.io/w24/lab/lab03/) description for information about creating your MVP video.
  - Links to videos will be made available to the class for peer review, but will not be made public
* Present to an audience of **potential users**
  - Not to an audience of CS148 students, or the instructor or TAs.
  - Explain what problem the app solves, or what need it fulfills, as you demo the features of
    the app.
* Stay focused on user functionality.
  - Do not go into details of implementation, or team process.
  - There will be other presentations for that, most notably the final project presentation. 
* Optionally, you may introduce with (a) powerpoint slide(s), and/or close with one, but the bulk
  of the time, you should be sharing your screen and showing us your app.
* At the end, tell us a bit about upcoming features planned for the next iteration.

At next week's Wednesday class [lect08](https://ucsb-cs148.github.io/w25/lectures/lect08/) you'll be asked to evaluate other teams' presentation(s), so plan to watch at least your partner's presentation in advance, and be ready to do some very brief commenting after each presentation in class. 

Every team is teamed up with one partner team creating the following evaluation pairings: 

| **This team:**   | **evaluates** | ... **this team:** |
| pj09-socialrunning |<----> | pj11-recipegenerator| 
| pj11-recipegenerator |<----> | pj12-closettracker| 
| pj12-closettracker |<----> | pj09-socialrunning| 
| pj01-scheduleconverter |<----> | pj02-lyricgenerator| 
| pj02-lyricgenerator |<----> | pj08-studytimer| 
| pj08-studytimer |<----> | pj01-scheduleconverter| 
| pj03-gauchograduate |<----> | pj05-shelfshare|
| pj05-shelfshare |<----> | pj06-studyconnect| 
| pj06-studyconnect |<----> | pj03-gauchograduate| 
| pj04-restaurantdecider|<----> | pj07-mafia| 
| pj07-mafia|<----> | pj13-sportsbetting| 
| pj13-sportsbetting|<----> | pj04-restaurantdecider| 
| pj10-timebendingpuzzle|<----> | pj14-lootfinder| 
| pj14-lootfinder|<----> | pj10-timebendingpuzzle| 

## Add Installation instructions to your README.md 
*  **by Monday 02/03/25, 23:59 PDT** == Code Freeze Deadline (for details on the README format, see [lab03](https://ucsb-cs148.github.io/w25/lab/lab03/)) 

## Point us to your video 
*  **by Monday 02/03/25, 23:59 PDT** create a file `team/MVP_DEMO.md` containing your MVP video link and any additional information you see fit that you think doesn't belong in the project's README.md. Also enter the link in [the team links spreadsheet](https://docs.google.com/spreadsheets/d/16dpihuLjsv3rjEDqbXLjG7wxP24qtgpuWBBsVncedO8/edit?usp=sharing)


# Lab04 New Deliverables

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-T) (25 pts) You earn these team points if your team has a github tagged release of your MVP timestamped **before 02/03/25, 23:59 PDT** and a video link in `team/MVP_DEMO.md` and in [the team links spreadsheet](https://docs.google.com/spreadsheets/d/16dpihuLjsv3rjEDqbXLjG7wxP24qtgpuWBBsVncedO8/edit?usp=sharing)!

**Graded**: ({{page.num}}-I) (25 pts) You earn these individual points if you participate in the MVP review during [lect08](https://ucsb-cs148.github.io/w25/lectures/lect08/) and submit an evaluation form to briefly review all other groups' MVPs by **Fri, 02/07/2025, 23:59pm PDT**

**Graded**: ({{page.num}}-T) (15 pts) You earn these team points in the MVP review during [lect08](https://ucsb-cs148.github.io/w25/lectures/lect08/)  on **Wed, 02/05/2025** if at least one member of your team (left column above) asks a question after the video of one paired other team (right column above). 

**Graded**: ({{page.num}}-T) (25 pts) You earn these team points for ensuring that each team member was assigned at least one issue that was moved to the Done column of your Kanban board **with tested acceptance criteria** over the next week **ending on Fri, 02/09/23, 23:59 PDT**. When you complete work on the last open issue you were assigned to (yay!) and you move it to the Done column, immediately assign this team member a new issue from the Sprint backlog and move it to the in-progress column. Make sure that all these issues have clear **acceptance tests/criteria** and that you verified these before calling the issue Done.

**Graded**: ({{page.num}}-I) (10 pts) You earn these individual points if your personal github account is enrolled in [Github Education](https://github.com/education) by **Fri, 02/07/2025, 23:59pm PDT**. If you are already part of it, great - nothing more to do. But if not, start the process right away, i.e. **today during lab** or right thereafter. You need to submit proof of enrollment and the vetting process may take up to a week! 
</div>

## MVP Tag/Release in your GitHub repo
By the end of Monday, 02/03/25, tag and release your MVP project in your github. 
[This brief article](https://medium.com/@jameshamann/a-brief-guide-to-semantic-versioning-c6055d87c90e) gives some suggestions on versioning numbering.  

### To create a tag:
#### Option 1: Web UI
* You can use the web UI to create a tag, but it will only create the tag from the current version (most recent commit).
The tag is automatically created when you create a new release in the git UI.
* Skip directly to 'Create a Release'

#### Option 2: command line instructions. 
(Choose this option if you need to create a tag that is earlier than the most recent commit)

`git tag v1.0.0 <commit ID>`

note - v1.0.0 is the tag name, and commitID refers to the last commit in your MVP 

you can find the commit ID using `git log`, or using the history tab in the github web ui

if done correctly, you should see something like this in the git log
![image](https://user-images.githubusercontent.com/10558897/116512519-06006680-a87d-11eb-9ead-d6cbc0d633bd.png)

if you messed up, you can delete the tag using `git tag -d <tag_name>`

Verify that everything looks good, then `git push origin <tag_name>`

Your newly created tag should appear in your tags page on the web UI

### To create a release:

#### Option 1:
* If you want to create a release from the current, most recent commit
* On the right hand column, there should be a section labeled 'Releases'. Click on 'create a new release'
* Put v1.0.0 in the 'Tag Version' box, and fill out the rest of the boxes.
* Click `Publish Release' and the tag will automatically be created for you

#### Option 2:
* If you want to create a release from an existing tag
* On the right hand column, there should be a section labeled 'Releases'. Click on 'create a new release'
* There should be a toggle between Releases and Tabs right above the 'Tag Version' form. Click on Tabs to toggle over.
* Click on the  menu (with 3 dots) on the far right hand side of the tag, and select 'Create Release'
* Fill out the form, and `Publish Release`

