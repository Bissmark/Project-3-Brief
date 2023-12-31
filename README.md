<img src="https://i.imgur.com/NQXEQci.png">
<img = src="https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png"> 

# Project #3: Your Group Project

## Overview

You’ve already worked in small groups to accomplish various labs and exercises, but this time **we’re going to challenge you to work in a small team on a project.**

You and your teammates together will architect, design, and collaboratively build a full-stack web app.

**This project will push you both technically and collaboratively!**

You'll likely be working as part of a team in the workplace and **this project will provide you with that important team development experience.**

However, **working on a project as part of a team can be more challenging** due to logistical reasons, differing opinions, etc.

During this project, **your instructors are going to be evaluating your ability to**:

-  Listen to and respect other opinions
-  Share and contribute your ideas with the team
-  Form a consensus and compromise when opinions differ

### In fact, **your ability to work in a team during this project is more important than the project itself!**

**Before you start working** on the planning for your project, be sure to review your idea with an instructor to ensure that it both:

- **Meets the minimum requirements**, and
- **Is reasonably scoped**

## Project Requirements

### Planning Requirements - Due Friday 24th November

As you've discovered, a project consists of more than just code.

This project requires **planning** organized within a **Trello board** with the following **lists**:

☐ **Icebox**: Holds user stories that have yet to be moved to the _Current/MVP_ list. All user stories are originally put into the _Icebox_, including both MVP and wish list stories. 

☐ **Current/MVP**: Holds user stories that must be completed to meet the minimum project requirements (MVP). Once the MVP has been met, additional user stories may be moved to this list from the _Icebox_.

☐ **Completed**: Holds completed user stories. 

> Important: User stories need to be formed properly using this template:<br>`As a <role>, I want <feature> so that <reason>`.<br>The _reason_ is optional if it's patently obvious.

☐ **Wireframes**: Sketches of each screens's user interface for the major functionality of the application.

☐ **Entity-Relationship-Diagram (ERD)**: A diagram of the app's models (one per data entity) and the relationships between them.

> Please reach out to your instructional team if you have questions regarding user stories, the data model, etc.

### Presentation Requirements - Due Friday 1st December

You will have 10 minutes to present and demonstrate the following:

1. Introduce your project by paraphrasing its README.

2. Click the link in the README to open the deployed app on Heroku (if deployed)

3. Demonstrate the application's authentication features by signing up a new user, logging out that user, then logging in with your preferred user.

4. Demonstrate your app's main features.

5. Share/discuss the following code:

	- The "main" Mongoose model
	- Your "favorite" Express controller method
	- Your "favorite" React component
	- The client-side routing

6. Share the experience by answering the following:

	- What was your biggest challenge?
	- What are your key learnings/takeaways?

Following your presentation, there may be a brief Q & A period and optional instructor feedback.

### Version Control Requirements

☐ The project's source code must be hosted on a personal **GitHub repository**.

☐ The repo is to contain **frequent commits** (**at least** 1 per day) dated from the beginning of the project through its completion. **Do not** "start over" by replacing the repository with a different one.

### README Requirements

Don't underestimate the value of a well crafted `README.md`.

The `README.md` introduces your project to prospective employers and forms their first impression of your work!

> Note: Do not include project planning (user stories, wireframes or ERDs) in the `README.md`.

Include the following sections within the **`README.md`**:

☐ **App Title:** Contains a description of what the app does and optional background info.
  
☐ **Screenshot(s):** A screenshot of your app's landing page and any other screenshots of interest.
  
☐ **Technologies Used**: List of the technologies used.
    
☐ **Getting Started**: That Includes:
  	
- A link to the **deployed app** (if deployed)
- A link to the **Trello board** used for the project's planning that includes user stories, wireframes & an ERD.
  
☐ **Next Steps**: Planned future enhancements (icebox items).
  
### Technical Requirements

☐ A **working** full-stack, single-page application.

☐ Incorporate the technologies of the **MERN-stack**:

- MongoDB/Mongoose
- Express
- React
- Node

☐ **Have a well-styled interactive front-end**.

☐ Communicates with the **Express** backend via AJAX.

☐ Implement token-based **authentication**.  Including the ability of a user to sign-up, log in & log out.

☐ Implement **authorization** by restricting CUD data functionality to authenticated users. Also, navigation should respond to the login status of the user.

☐ **Have a well-scoped feature-set**. Full-CRUD data operations are not required if one or more other features are included, for example:
	
- Consume data from a third-party API.
- Implement additional functionality if the user is an admin.
- Implementation of a highly dynamic UI or data visualization.
- Other, instructor approved, complexity/features.

## Self-Sufficiency / Project Assistance

- At this stage of SEI, being able to find the the answers to development issues is of paramount importance. 

- Use all resources available to solve the issue on your own before seeking assistance.

- If you do seek assistance in Slack, use the support channel and explain the issue as clearly and detailed as you can, include screenshots when possible, and be prepared to explain what you've done to solve the issue on your own.

## Suggestions to Get Started

- Don’t get too caught up in too many awesome features – simple is better. Favor fewer features that look/feel impressive over numerous clunky/sloppy features.

- Because it takes longer to code user interfaces using React than with EJS & DTL, be sure to prioritize user stories to meet the MVP and ice box the others.

- Begin by cloning the `mern-infrastructure` repo, create a new repo on your **personal** GitHub account, change the `origin` remote to that of the new repo with `git remote set-url origin <new_remote_url>`.

- Update the project name in the package.json file and make other name changes, e.g., update the `<title>` in index.html, etc.

- Implement the "As a visitor, when I browse to the app, I want..." user story first.

- Follow the steps we've done in class to implement features, beginning with the user's interaction and code the flow from client -> server -> client. 

- Read the docs for whatever technologies / frameworks / API’s you use.

## Best Practices

- **Make AJAX calls** from "API" modules, not components. Export application/business logic from "service" modules.

- **Be consistent** with your code style.

- **Clearly name variables and functions** - remember, variables are usually named as **nouns** and functions as **verbs**.

- **Write well-formatted JS & CSS.** Properly formatting your code makes it more readable. Improperly formatted code infers sloppiness.

- **Comment your code where it makes sense to do so**. Most code is self-documenting (don't comment the obvious), however, use comments to explain complicated code.


