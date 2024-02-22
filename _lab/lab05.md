---
layout: lab
num: lab05
desc: "MVP Demos, Unit Testing, Coding with AI"
assigned: 2024-02-09 13:00
due: 2024-02-16 23:59
github_org: "ucsb-cs148-w24"
ready: true
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


# Announcements
* Today (part of lab04): 
  * MVP video demonstrations with peer eval 
  * Voting for favorite MVPs from your Section
  * Celebration of our progress
  * You get points from today's activities to finish up the [lab04 deliverables](https://ucsb-cs148.github.io/w24/lab/lab04/) 
  
* Lab05: Over the following week you will practice Continuous Integration and Continuous Delivery, considering your MVP peer evaluation feedback, work on continued functionality development, practice some unit testing towards test-based design, and experiment with AI-supported development! 
* Don't forget Sprint Review and Sprint Planning Meetings 

* Next week (Lab06), we'll hold the Second Retrospective (the MVP release is a great opportunity to review the next steps)


# Procedure for Today's MVP Review

We will play your MVP videos in the order below. After each video is played, we will have Q&A, and during and after the presentation you will collect feedback on a Google Form we posted on the new Slack mvp-presentation channel.  

**1pm Section:** 
```
PJ01 - universityclothing (PJ02 asks a question)
PJ02 - travelplanner (PJ03 asks a question)
PJ03 - intelligrocery (PJ11 asks a question)
PJ11 - songrater (PJ12 asks a question)
PJ12 - appblocker (PJ14 asks a question)
PJ14 - ucsbcoral (PJ01 asks a question)
``` 

**2pm Section:** 
```
PJ04 - courserecs (PJ06 asks a question)
PJ06 - foundit (PJ10 asks a question)
PJ10 - spotifai (PJ13 asks a question)
PJ13 - researchhelper (PJ04 asks a question)
``` 

**3pm Section:** 
```
PJ05 - codegrow (PJ07 asks a question) 
PJ07 - datingalgorithm (PJ08 asks a question)
PJ08 - reccen (PJ09 asks a question) 
PJ09 - liveordie (T09 asks a question) 
``` 

&nbsp;

* Everyone will **take notes and submit a quick peer-feedback form** on each other presentation in your section while watching the presentations during class. 
    * Please fill in the review form announced on Slack during your session during the video presentations. Submission of this form will count towards your lab04 points. If you cannot attend today's lecture, you can watch the [prepared videos](https://docs.google.com/spreadsheets/d/16dpihuLjsv3rjEDqbXLjG7wxP24qtgpuWBBsVncedO8/edit) and fill the form in before the end of this lab. 

<br />   
*After each video presentation, a representative from *the group listed above as being teamed with you* will **ask a question** to the team whose video was just shown. That question should be typed in a special Slack Channel @mvp-presentation (so that we capture it) and read out by the representative for the team asking the question. 
    * The question can be of any type, e.g. a follow-up on something that was not entirely clear, a low-level implementation question, a question about possible future functionality, or a high-level question about the product landscape connected to the project. 

<br />
* After the peer team asked their question, there will be an opportunity for **anyone to ask a question** to the team whose video was shown, but if there are many questions, we may have to cut it short. We ask that any questions that are asked be captured in the Slack channel! We also may chime in with questions and comments from the teaching team. 

* After all project videos have been shown, everyone will be asked to **vote for their favorite MVPs**. You will receive the link to that review form in the Slack channel.  We will announce the audience choice award winner for best MVP in your Section next week, as well as on Slack (which gives you bragging rights, but no influence on your grades. Grades will solely be based on final product presentations and quality).  

# Celebrate

We want to **celebrate** with you on how far you have already come - We are really proud and excited about every single team's progress since the start of the quarter. It's a journey, and we should enjoy it! 

# Points for Lab05

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-T) (35 pts) Review, assess, and summarize the feedback you received on your MVP evaluation and formulate an action plan going forward. More details in [Lecture 09](https://ucsb-cs148.github.io/w24/lectures/lect09/) (now, 02/12/24, also copied below)

**Graded**: ({{page.num}}-T) (35 pts) You earn these team points for identifying at least one testing library to experiment with for your coding needs, and for implementing and documenting at least one unit test in your code base by next week, {{page.due}} (see instructions below).

**Graded**: ({{page.num}}-I) (30 pts) You earn these individual points by doing and documenting at least one "Coding with AI" experiment over the coming week. This can take multiple forms: Using AI to prototype UI possibilities (e.g. using ChatGPT or v0.dev for React-based web pages), help with writing testing code (see previous bullet, e.g. using Github Copilot or Codeium), generating documentation (e.g. using Github Copilot, Codeium, or similar plugins), researching scalability suggestions for your app, etc. More details in [Lecture 09](https://ucsb-cs148.github.io/w24/lectures/lect09/) (now, 02/12/24, also copied below).

</div>

**(35 pts) Review, assess, and summarize the feedback you received on your MVP evaluation and formulate an action plan going forward.**
    * Feedback has been posted in your project Slack channel. Please review and organize (group). Then discuss action items and user stories in response and prioritize them.  
    * Please create a `team/MVP_FOLLOWUP.md` file, where you document this process (e.g., with subheadings such as):  
        * Feedback Grouped and Sorted 
        * Response Actions 
        * Next Steps    

* **(35 pts) You earn these team points for identifying at least one testing library to experiment with for your coding needs, and for implementing and documenting at least one unit test in your code base by Friday, EOD.**
    * Please create a `team/TESTING.md` file, where you document the testing library/ies and approach/es you experiemnted with and the unit test(s) that you implemented in your codebase. 

* **(30 pts) You earn these individual points by doing and documenting at least one "Coding with AI" experiment by Friday, EOD.**
    * This can take multiple forms: Using AI to prototype UI possibilities (e.g. using [ChatGPT](https://chat.openai.com/), [Google Gemini](https://one.google.com/explore-plan/gemini-advanced?utm_source=gemini&utm_medium=web&utm_campaign=gemini_advanced_announce), or [Vercel v0.dev](http://v0.dev/) for React-based web pages), help with writing testing code (e.g. using [Github Copilot](https://github.com/features/copilot) or [Codeium](https://codeium.com), generating documentation (e.g. using [Github Copilot](https://github.com/features/copilot), [Codeium](https://codeium.com), or similar plugins), designing UI art/elements using [Dall-e](https://openai.com/dall-e-3), [Gemini](https://one.google.com/explore-plan/gemini-advanced?utm_source=gemini&utm_medium=web&utm_campaign=gemini_advanced_announce), or [Adobe Firefly](https://firefly.adobe.com/?ff_channel=adobe_com&ff_campaign=ffly_homepage&ff_source=firefly_seo), researching scalability suggestions for your app, etc.
    * Please create a `team/AI_CODING.md` file, where each of the team members documents their individual AI coding experiments. List the AI tool you utilized, the outcomes you produced, **and, importantly, reflections on** 
        * how useful this tool was / potentially could be for your coding effort going forward
        * what steps you needed to (or couldn't) take to ensure that the AI output was correct, understandable, and fair use  

* A new Slack channel `help_ai` was created to provide pointers to useful AI coding tools. In addition to documenting your efforts in your own team-internal `team/AI_CODING.md` file, please share pointers to the tools you were most excited about in there.  
