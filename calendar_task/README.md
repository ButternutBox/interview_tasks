## Calendar Task

### Introduction

During our signup process, it's important to us that customers are able to select their preferred delivery date so they see how flexible the service we offer is. This step is done on our checkout, and is composed of a pre-selected date (Which is the earliest available delivery), and a prompt to allow them change it. Clicking on this prompt opens up a modal that allows them select a new date for delivery. We'd like you replicate some of this functionality for us.

### Task

We’d love for you to create a simple calendar view outlined in the PDF attached below in React and CSS, similar to the approach we take on checkout. As we've outlined in the image below, the initial state should be a button that opens a modal with a background overlay greying out the background. Once clicked, a modal should animate in, and I should then be able to adjust my delivery date to another 'deliverable' date. Clicking on the 'change date' button, 'cancel, don't change' button, or the background, should close the modal after saving the user option if appropriate.

The dates listed should the current month. You should correctly dynamically handle the start date and end date of the month being any day of the week.

Technical Notes:

1. The modal should only be rendered on the page (added to the DOM) when open. We don't want extra HTML nodes hanging around on the page when it's closed. Think about how this might impact the animation of the item.
2. Further animation beyond the opening and closing of the modal and any other ideas you have to improve the user experience and show off your attention to detail would be a great bonus!
3. You can only select one date at a time in the calendar.
4. You are free to use animation libraries, within reason.
5. The date in the calendar icon in the closed state should be dynamic and reflect the selected date.
6. We've set up a basic Create React App, we've also set up TypeScript and Sass as tools that you can use, but feel free to adjust if you prefer a different setup.

### UI Design

![](task.png)


### Notes on attempting the task

- We've included some assets that you'll need such as SVGs, fonts, and our colours, these can be found in `src/..`
- We’re keen to ensure that it’s a collaborative effort - feel free to check in regularly to discuss any aspect of the project.
- We love clear code that is aided with comments and documentation - talk us through what you are doing and how you approached the problem - that helps us understand how you found the task.
- We expect the task to take roughly 3 hours, and as such ask you to only spend this long on it. We like to time-box tasks so as to ensure fairness between candidates with varying amounts of free time.
- Unfinished tasks will not be looked at negatively, we're more interested in seeing your approach and demonstrations of your skill-set than perfectly finished tasks.
- In the case that it looks like you won't finish in time, please ensure that there is at least a skeleton and a to-do list for all parts of the project, so that we can see what your approach would have been for any unfinished sections.

### Getting started

Use yarn install and yarn start to get your React App started.
