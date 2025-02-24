---
desc: "Patterns, Code Smells, UX Principles"
lecture_date: 2025-02-24
num: lect12
ready: false
---

# Announcements
* **[Homework assignment h08](https://ucsb-cs148.github.io/w25/hwk/h08/)** on SW Design Patterns and Code Smells still due on **Monday next week**. 
* **Second CATME peer eval results just released**: Please discuss with your teams. Use this to keep the team focused and every team member accountable. 

# Inter-Team Evaluation 

* **REMINDER:** This Wednesday (02/26), we will do an inter-team eval of your app deployment, functionality, UX. In last week's lab, you listed questions you'd like to have the other team answer about your product. **Today, make sure that you prepare the other team to help you as much as possible!**. We will come around to confirm the plan with you. 

*  For Wednesday's session, we currently plan for repositories will be made public to non-team organization members. Any existing hardcoded secrets (API keys, passwords, access tokens, etc.) in your application should be rotated out as soon as possible. In a bad-but-not-worst case scenario, a bad actor with credentials to your infrastructure can [land you a large bill](https://medium.com/flat-pack-tech/hard-coding-secrets-be-aware-of-the-scariest-breach-for-your-organization-3e858ab296f2).

To ensure your API keys are not exposed in a public GitHub repository,
follow these best practices:

1. **Use a .gitignore File**
   - Store your API keys in a separate configuration file (e.g., `.env`, `config.json`).
   - Add that file to `.gitignore` before committing to GitHub.

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
   - [Official GitHub Docs on Secret Scanning](https://docs.github.com/en/code-security/secret-scanning)
   - Other tools to scan for sensitive information before pushing to GitHub:
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


By following these practices, you can safely make your GitHub repo public without exposing sensitive API keys.


# SW Design Patterns, AntiPatterns, Code Smells 
* There is **no** requirement for using/documenting SW patterns, antipatterns, or Code Smells in your design documentation, but they are really helpful SW Engineering concepts.  
* Slides: [Software Patterns](https://sites.cs.ucsb.edu/~holl/CS148/handouts/Slides_Patterns.pdf)
* Code Smells: [Coding Horror Blog](https://blog.codinghorror.com/code-smells/), [refactoring.guru](https://refactoring.guru/refactoring/smells)
* [Software Design Patterns: A Guide](https://airbrake.io/blog/design-patterns/software-design-patterns-guide), supported by the [Pattern Catalog at refactoring.guru](https://refactoring.guru/design-patterns/catalog)
* [AntiPatterns](https://sourcemaking.com/antipatterns)


# UX Design
* [8 Golden Rules of UI Design](https://sites.cs.ucsb.edu/~holl/CS148/handouts/Slides_UIPrinciples.pdf) 
* Slide: [UX metrics](https://sites.cs.ucsb.edu/~holl/CS148/handouts/UXMetrics.pdf)
* Google's current Design Philosophy, Material Design: [Material 3](https://m3.material.io/)

* Tools for Wireframing:  [Figma](https://www.figma.com/), [Canva](https://www.canva.com/), [Wireframe.cc](https://wireframe.cc/), (On Mac:) [sketch.com](https://www.sketch.com/)

# Today: Work in Breakout Groups
* Standup
* Continue [lab07](https://ucsb-cs148.github.io/w25/lab/lab07/) 
    * Review of Leadership Roles 
    * Design Document (including a high-level system diagram)


In general: 
* **Focus on your projects**. Lab work in the coming weeks will continue to focus on documentation (**design document**, **user manual**) in order to get your documents started and to utilize cycles of team members not central to ongoing implementation efforts at any given time. 
** Project documentation will happen in three major documents: 
    * **design document** (started this week in lab07),
    * **user manual** (to be started in lab08),
    * **deployment instructions** (started for MVP peer review) and Github **README.md**, which should explain the code folder hierarchy and guide through the implementation effort. 
* Project presentations (Final exam slot, Mon, March 17th, 4-7pm)