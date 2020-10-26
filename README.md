![Image description](https://i1.faceprep.in/ProGrad/prograd-logo.png)

# ProGrad Lab | REACT HOOKS - PROHOOKS

## Learning Goals

In this exercise, the goal is to learn routing,hooks and OKTA authentication in react:

- Axios,
- React Hooks
- OKTA Authentication

## Getting started

1. Fork this repo
2. Clone this repo

Whenever you create a first significant change, you should make your first commit.

3. Follow these [guidelines to add, commit and push changes](https://github.com/FACEPrep-ProGrad/general-guidelines-labs-project-builders.git).

In the end of this document, you will find guidelines on how to submit the exercise.

## Instructions
In this lab we will try to work with hooks in react. The main idea of this lab is to understand react hooks in detail and also fetch data from external API, process it and display it. We will also try to integrate `OKTA` authetication in our code. 
We have three components.

**Remember you cannot use hooks in class component**. All which are mentioned below are functional components.
- App Component
- HomeComponent
- Search Component

```API DETAILS
const baseUrl = 'http://openlibrary.org';
```

Kindly see the output:
![Image description](https://i1.faceprep.in/ProGrad/hooks-1.png)
![Image description](https://i1.faceprep.in/ProGrad/hooks-2.png)
![Image description](https://i1.faceprep.in/ProGrad/hooks-3.png)
![Image description](https://i1.faceprep.in/ProGrad/hooks-4.png)
![Image description](https://i1.faceprep.in/ProGrad/hooks-5.png)
![Image description](https://i1.faceprep.in/ProGrad/hooks-6.png)
### PROGRESSION 1 | JOB COMPONENT

Fetch the data from the above api in job component, pass the data to home component using props and display it in homeComponent. 

Check the output for your reference.
![Image description](https://i1.faceprep.in/ProGrad/job_1.gif)
### PROGRESSION 2 | JOB DETAIL
In this progression, your task is to display the complete job description. Keep a button called as `View Details`. This a toggle button which should toggle between hide and show details.

Check the output for your reference.
![Image description](https://i1.faceprep.in/ProGrad/job_2-2.gif)

### PROGRESSION 3 | PAGES
In this progression, your task it to set the page number. Each page consists of twenty job posts. When the post exceeds more than twenty it should go to the next page.

Check the output for your reference.
![Image description](https://i1.faceprep.in/ProGrad/job_3.png)


### PROGRESSION 4 | SEARCH FORM
Search form is a separate component. Your task is to include the search form at the top of the HomeComponent. Based on the search filter, fetch the details and display it for the user.

![Image description](https://i1.faceprep.in/ProGrad/job_4.png)

### PROGRESSION 5 | HOMECOMPONENT
The home component is the parent component which embeds all other component. Please check the screenshots for your reference.



## Submission

If you didn't add, commit and push the changes you made, this is the last call. :smile:

please share your github links with your Mentors. Your Mentor's will check up your work and provide feedback. 

## Summary

If you managed to do it, good job! :trophy:

We are proud of you!

Happy Coding ProGrad ❤️!

