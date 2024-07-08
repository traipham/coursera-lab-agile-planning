---
name: User Story
about: 'Coursera: Introduction to Agile Development and Scrum'
title: ''
labels: ''
assignees: ''

---

+
-
Play


00:00
02:58
Mute

Settings
Hands-On Lab: Create an issue template in GitHub
Estimated time needed: 10 minutes

In this lab, you will create an issue template in GitHub that will help you to write well-formatted user stories in Kanban board.

Note:

If you chose to use GitHub Projects for your Kanban board, continue using it for all the labs. Alternatively, you can use Zenhub for creating a Kanban board for your labs.
The process of creating an issue template will be the same whether we use GitHub Kanban or Zenhub Kanban, since the issue template will be created in the GitHub Repository only.
After completing this lab, you will be able to:

Create an issue template in GitHub that contains the information required for writing good user stories.
Exercise 1 : Create an issue template in GitHub
In this exercise, you will create an issue template in GitHub. This only needs to be done once for each new repository that you create.

Go to GitHub.com and select the lab-agile-planning repository that you created in Lab 1.
github home.

From the repository page, select Settings.
select settings

Scroll down to the Features section and select Set up templates.
select setup templates

From the dropdown list labeled Add template (1), select Custom template (2).
select custom template

Next to the Custom issue template entry, press the Preview and edit button.
select preview and edit

Press the pencil icon to edit the template.
select pencil

Copy the following markdown for the story template content:

1
2
3
4
5
6
7
8
9
10
11
12
13
14
 **As a** [role]  
 **I need** [function]  
 **So that** [benefit]  
   
 ### Details and Assumptions
 * [document what you know]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [some context]
 When [certain action is taken]
 Then [the outcome of action is observed]
 ```
Copied!
Edit the Template name to be: User Story, give it an appropriate description, and paste the contents of the above markdown into the Template content
template contents

Scroll to the top of the page and press the Propose changes button.
propose changes

Press the Commit changes button to commit the change to your repository.
commit template changes.

You should now have a new folder in your repository called .github/ISSUE_TEMPLATES, which will contain your new user story template.
template created.

Summary
You now have an issue template that you can use for all of your GitHub repositories that you need to write stories for to use in Kanban board. When we create issues in future labs, this template will guide you through what information is needed to create your user story.

Author(s)
Zehra Afzal
