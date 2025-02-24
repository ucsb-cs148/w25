---
layout: lab
num: lab08
ready: false
desc: "Inter-Team Eval Response, Start Manual, User Stories and Issues towards Final Release, Retro 3"
assigned: 2025-02-28 13:00
due: 2025-03-07 23:59
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

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-T) (20 pts) For joint team review of all received comments and compiling a team response report to the [team eval last Wednesday](https://ucsb-cs148.github.io/w25/lectures/lect14/) in a `team/EVAL_RESPONSE.md` file in your team repo. The report should be created in response to the peer feedback you received and should contain all items indicated on the [lect14 notes](https://ucsb-cs148.github.io/w25/lectures/lect14/).

**Graded**: ({{page.num}}-T) (20 pts) You earn these team points if you started a user manual document that you link to in your Github `docs/MANUAL.md` and that contains at the very least a description of the product purpose, lists the intended user audience, and has section headings (which are allowed to change until the final material submission deadline) with placeholder information (could even be [Lorem Ipsum text](https://www.lipsum.com/) for now) that document (or in the future will document) the various features of your product and how to operate them (with the final version using plenty of screenshots - for now, you can just put placeholders as is most convenient for you).  

**Graded**: ({{page.num}}-I) (20 pts) Team starts documenting (coordinating on one response or by submitting individual commentary) team roles and github contributions in `team/contributions/CONTRIBS.md`(see below). 

**Graded**: ({{page.num}}-T) (10 pts) You earn these team points based on the attendance/participation in your third and last retrospective some time over the next week as fits your Sprint cycle; 20/n per team member for teams of n members.
   
</div>


# Start User Manual Document
Start a User Manual Document (as a Google Doc or another `living document` format of your choice) and link to it in a new ./docs/MANUAL.md file in your GitHub. 
It should start with a paragraph explaining the purpose and intended user audience for the product (it can share some of this information with your README.MD, but the manual should be entirely oriented towards end users and should make no mention of implementation details that are not relevant to the end user experience).   

# Team Roles and Github Contributions

We ask every team to comment on the code contributions that every team member made. You already documented leadership roles within the team management (in team/LEADERSHIP.md), and now we ask you to document the roles the team members played in the code development effort. You can comment on team contributions other than coding as well. In your github team folder, please create a `contributions` subfolder. 

This lab just requires you to start the document in `team/contributions/CONTRIBS.md`, but you have until the final materials submissions deadline to update and edit it:  
Document and write commentary on team member code (and/or other) contributions in `team/contributions/CONTRIBS.md`: 
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

If you have a team member that you know or suspect has made lots of commits that are not being attributed to them, 
scroll through your commit log and see if you can find a few examples.

If the commits look ok, but don't tell the full story (e.g. a team member may have just contributed very few, but very important commits), you can bring that out in your commentary, too. 

Even distribution of the coding effort among all team members is definitely not expected, but highly uneven contributions, especially when paired with potential team dissatisfaction expressed through the catme.org surveys is grounds for individual weighting of the project grade component among team members.   


# Third (and last) Retrospective 

You will get time on Wed, 03/06, to hold your third and last team Scrum Retrospective, but you can move the time of this meeting to whatever time within this lab period your team prefers, including right this lab session (03/01). Note though that Monday lecture (03/04) will be taken up entirely by team activity towards inter-team product testing. 
Make sure you have a Retro leader assigned (should be the case since it was part of the Leadership review last lab).

You already know the goal and procedure for Retrospectives from your RETRO_01 and RETRO_02. This Retrospective allows you to discuss things that are relevant on your final stretch to product deployment, documentation, and presentation. Instead of designing an experiment this time, review what worked and what didn't from previous meetings, and make strong commitments towards the final stretch of product development towards launch! 


* In your team's repo, under `team/retrospectives` directory, add a file `RETRO_03.md` (or whatever number you are at if you did other retros already) capturing the following:

 ```
  # Retrospective your-nr-goes-here, date-goes-here 

  * Led by: name-goes-here
  * Present: name1, name2, ... , nameN
  * Absent: name1, name2, ...

  ## Action item

  * a goal: identify something the team wants to get better at
  * a commitment: identify one thing that the team pledges to do to maximize productivity towards launch
  * a measurement: identify at least one way to assess and ensure that the commitment(s) is/are kept

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
 
# Rotate Exposed Secrets

For this lab, repositories will be made public to non-team members. Any existing hardcoded secrets (API keys, passwords, access tokens, etc.) in your application should be rotated out as soon as possible. In a bad-but-not-worst case scenario, a bad actor with credentials to your infrastructure can [land you a large bill](https://medium.com/flat-pack-tech/hard-coding-secrets-be-aware-of-the-scariest-breach-for-your-organization-3e858ab296f2).

To ensure your API keys are not exposed in a public GitHub repository,
follow these best practices:

1. **Use a .gitignore File**
   - Store your API keys in a separate configuration file (e.g., `.env`, `config.json`).
   - Add that file to `.gitignore` before committing to GitHub.
   - **Example `.gitignore`:**
     ```bash
     .env
     config.json
     secrets.yaml
     ```

2. **Use Environment Variables**
   - Store API keys in environment variables instead of hardcoding them in your code.
   - Access them in your code like this:

     **Python:**
     ```python
     import os

     api_key = os.getenv("API_KEY")
     ```

     **Node.js (JavaScript/TypeScript):**
     ```javascript
     const apiKey = process.env.API_KEY;
     ```

3. **Use GitHub Secrets for Actions**
   - If you're using GitHub Actions, store API keys as [GitHub Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets) and access them within workflows.

4. **Scan for Secrets Before Committing**
   - Use tools to scan for sensitive information before pushing to GitHub:
     - [git-secrets](https://github.com/awslabs/git-secrets)
     - [truffleHog](https://github.com/trufflesecurity/trufflehog)
     - [gitleaks](https://github.com/gitleaks/gitleaks)

5. **Remove Secrets from Git History**
   - If you've already committed a secret, **do not just delete it** — it remains in the Git history. Instead:
     - Use [git filter-repo](https://github.com/newren/git-filter-repo) (recommended over `git rebase`) to remove it from history:
       ```bash
       git filter-repo --path <file-with-secret> --invert-paths
       ```
     - Force-push to overwrite history (**be cautious**):
       ```bash
       git push origin --force --all
       ```
     - If the secret is compromised, **revoke and regenerate it** immediately.

6. **Use a Secret Management Service**
   - Most major cloud services offer dedicated solutions for securely managing secrets, so the appropriate place for your app depends on your chosen service. Some examples are:
     - [AWS Secrets Manager](https://aws.amazon.com/secrets-manager)
     - [Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault)
     - [Google Cloud Secret Manager (GCP)](https://cloud.google.com/security/products/secret-manager)
     - [Heroku Config Vars](https://devcenter.heroku.com/articles/config-vars)
     - [GitHub Actions Secrets](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions)
     - Vault solutions like [HashiCorp Vault](https://www.vaultproject.io/)

7. **Official GitHub Docs on Secret Scanning**
	- [About Secret Scanning](https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning)
	  *	Explains what secret scanning is, which types of secrets are detected by default, and how it works for public vs. private repositories.
	  *	Clarifies that for public repos, secret scanning is free. For private repos, it’s part of GitHub Advanced Security (paid).
	- [Configuring Secret Scanning](https://docs.github.com/en/code-security/secret-scanning/configuring-secret-scanning)
	  *	Explains how to enable or disable secret scanning, manage alerts, and handle custom patterns.
	- [Managing Secret Scanning Alerts](https://docs.github.com/en/code-security/secret-scanning/managing-secret-scanning-alerts)
	  *	Walks you through viewing, triaging, and resolving discovered secrets.
	  *	Shows how to revoke and rotate credentials if needed.

By following these practices, you can safely make your GitHub repo public without exposing sensitive API keys.