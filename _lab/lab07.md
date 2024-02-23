---
layout: lab
num: lab07
ready: true
desc: "Review and Plan Leadership Roles / Start Design Document / Prepare UX Eval"
assigned: 2024-02-23 12:00
due: 2024-03-01 23:59
github_org: "ucsb-cs148-w24"
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

**Graded**: ({{page.num}}-T) (15 pts) You earn these team points if you have planned future team leadership roles and logged them in your GitHub `team/LEADERSHIP.md` as per instructions below 

**Graded**: ({{page.num}}-T) You earn these team points if you started a design document that you link to in your Github ./docs/DESIGN.md and that contains at least:
* (20 pts) an overview system architecture diagram and associated explanation.  
* (20 pts) a Section summarizing important team decisions since the start of the project, referring to meetings logged in your GitHub repo
* (25 pts) the beginnings of a Section talking about your User Experience (UX) considerations. A high-level task/user flow (see below) might be the first thing to document there, and it will also be helpful for determining the structure of your manual (next week's lab).

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points if you list in a new `team/evaluation/USER_FEEDBACK_NEEDS.md` document (in priority order) three things about your product that you would love to have user feedback on. Just to give example possibilities: user preference between two designs, an A/B study on the consequences of two designs, user satisfaction with a particular feature, user satisfaction with your overall current product, but there are many more possibilities. 
</div>


# Review and Plan Leadership Roles
 Visiting your `team/LEADERSHIP.md` file, remind yourselves who took on previous leadership roles for your team, and log anything that may have fallen by the wayside.  

For example (if applicable): 
    * Initial Product Owner 
    * First Retro Leader 
    * Second Retro Leader 
    * MVP Peer Eval Leader                

Then, discuss the list of roles below and assign one team member to each of the roles.

Several people will clearly be assigned to more than one role. That's fine, but follow these rules:

    * The product owner and the scrum master *may not* be the same person at any time, and
    * The retro leaders for each of at least three retros in the quarter should be different people.
    * No one should take on three roles unless/until each team member has already taken on two.

&nbsp;
If you have a situation where it is impossible to satisfy all of these rules, check with your mentor;
they are permitted to authorize exceptions where there is a legitimate need to do so.

Also, whoever is chosen below as the "Design Document Coordinator" will be responsible for copying these roles from your discussion into `team/LEADERSHIP.md`.

**Roles to assign**

* **Product Owner**.  Together with Scrum Master, leads the Sprint Planning meeting(s) to come
      Responsible for making sure that the team comes up with a set of **user stories**
      for the "final" product that your team will deliver, and marking those stories with a label "final" (just
      like the label `MVP` that you used previously).  
* **Scrum Master**.   Together with Product Owner, leads the sprint planing meeting(s) still to come.
      Responsible for making sure that the team comes up with a set of **issues**
      for the "final" product that your team will deliver, each tied to one of the user stories.
      and marking those stories with a label "final" (just like the label `MVP` that you used previously).
      Also responsible for holding the team accountable for keeping the issues moving through the Kanban board.
* **Testing/QA Coordinator**. 
      Ultimately, responsible for making sure that user stories and issues have acceptance criteria, and that
      these are met before pull requests are accepted into master. If you are doing any sort of TDD or BDD, this person will also mainly coordinate that effort. 
* **Retro 3 leader**.  This person will lead the third required retro during week 9.
* **UX Coordinator**.  Responsible for the look and feel of the product, and the way that the user interacts with the
      product. By next week, will have a set of pointers and recommendations for the UI/UX of your products...
* **Design Document Coordinator**.  This person is responsible for the design process documentation started in this lab, chiefly the document pointed to by `./docs/DESIGN.md`.
      By next week (lab08), they should ensure that there is a first version, and will be responsible for updating it throughout the rest of the quarter.
* **Deployment Document Coordinator**.  This person is responsible for the deployment documentation refactored in this lab, chiefly the document pointed to by `./docs/DEPLOY.md`.
      By next week (lab08), they should ensure that there is a first version, and will be responsible for updating it throughout the rest of the quarter.
* **User Manual Coordinator**.  This person is responsible for the user manual part of the documentation. More detail will be given in lab08, and the person in charge will be responsible for updating it
      throughout the rest of the quarter.
* **Final presentation leader (week 9/10)**.  This person will be in charge coordinating the final class presentation on Thu, 03/23. The presentation itself will likely have multiple presenters, but the leader ensures everyone is prepared and everything goes smoothly with demos and setup.
  

# Start Design Document
Start a Design Document (as a Google Doc or another `living document` format of your choice) and link to it in a new ./docs/DESIGN.md file in your GitHub. 
It should contain, for starters, a high-level system architecture overview diagram for your project, with associated explanations of all parts in some text paragraphs accompanying it.   

For examples that might stir your creativity, you can check out, e.g., the Requirement Documents in [UCSB Capstone projects](https://capstone.cs.ucsb.edu/past22.html)   

You can use any diagramming tool of your choice. Please post in Slack #help_diagrams if you like a tool beyond the ones in the list below, but here are some options:   
   * Google Slides
   * LibreOffice (Impress, Draw)
   * Microsoft Powerpoint or Visio (if you have access to MS Office) 

Or some web-based solutions: 
   * [Figma/FigJam](https://figma.com) 
   * [diagrams.net](https://www.diagrams.net)
   * [Gliffy](https://www.gliffy.com/)
   * [graphviz](https://graphviz.org)

Multi-Platform: 
   * [drawio - see also diagrams.net above](https://github.com/jgraph/drawio-desktop/releases)
   
Or on Mac/IOS:     
   * [Flowchart Designer 3](https://apps.apple.com/app/flowchart-designer-3/id1512570906) 
   
The exact structure of the Design Document is left to your team to determine, but to get you started, we recommend at least the following set of sections in some form and order: 
* Opening/Overview section with high-level system architecture overview diagram for your project, with associated explanations of all parts in some text paragraphs accompanying it.
* More Detailed SW Architecture Design: Describe the main modules in your SW Design in more detail
* Design Process Documentation Section: This is where you can earn the 30 points from the second grading bullet above: Document your design process by summarizing important team decisions referring to specific meetings logged in your GitHub repo.
* User Interface and User Experience (UX) considerations. A high-level task/user flow might be the first thing to document here.

# User Flow 
A high-level overview (diagram and associated explanation) of your product's 
[Task/User Flow](https://careerfoundry.com/en/blog/ux-design/what-are-user-flows/) can be used as the starting point for the UX section in your Design Document and also for planning/structuring your user manual.

# User Feedback Needs

List in a new `team/evaluation/USER_FEEDBACK_NEEDS.md` document (in priority order) three things about your product that you would love to have user feedback on. Just to give example possibilities: user preference between two designs, an A/B study on the consequences of two designs, user satisfaction with a particular feature, user satisfaction with your overall current product, but there are many more possibilities. 

The more specific you can be on these items, the better. You get the points just for the ideation, but the idea is that this process facilitate and help you prepare one of the evaluations you list for the Monday March 4th inter-team project evaluation exercise and the other team will actually try to answer your question. Basically, you have 8 user study participants, the other team members, at your disposal for concrete feedback. Presumably, you will prepare your top priority user feedback solicitation, but maybe a different option if the top priority is not feasible to be evaluated by March 4th. 
