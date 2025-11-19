# Milestone 5

This document should be completed and submitted during **Unit 9** of this course. You **must** check off all completed tasks in this document in order to receive credit for your work.

## Checklist

This unit, be sure to complete all tasks listed below. To complete a task, place an `x` between the brackets.

- [x] Deploy your project on Render
  - [x] In `readme.md`, add the link to your deployed project
- [x] Update the status of issues in your project board as you complete them
- [x] In `readme.md`, check off the features you have completed in this unit by adding a ✅ emoji in front of their title
  - [x] Under each feature you have completed, **include a GIF** showing feature functionality
- [x] In this document, complete the **Reflection** section below
- [x] 🚩🚩🚩**Complete the Final Project Feature Checklist section below**, detailing each feature you completed in the project (ONLY include features you implemented, not features you planned)
- [x] 🚩🚩🚩**Record a GIF showing a complete run-through of your app** that displays all the components included in the **Final Project Feature Checklist** below
  - [x] Include this GIF in the **Final Demo GIF** section below

## Final Project Feature Checklist

Complete the checklist below detailing each baseline, custom, and stretch feature you completed in your project. This checklist will help graders look for each feature in the GIF you submit.

### Baseline Features

👉🏾👉🏾👉🏾 Check off each completed feature below.

- [x] The project includes an Express backend app and a React frontend app
- [x] The project includes these backend-specific features:
  - [x] At least one of each of the following database relationships in Postgres
    - [x] one-to-many
    - [x] many-to-many with a join table
  - [x] A well-designed RESTful API that:
    - [x] supports all four main request types for a single entity (ex. tasks in a to-do list app): GET, POST, PATCH, and DELETE
      - [x] the user can **view** items, such as tasks
      - [x] the user can **create** a new item, such as a task
      - [x] the user can **update** an existing item by changing some or all of its values, such as changing the title of task
      - [x] the user can **delete** an existing item, such as a task
    - [x] Routes follow proper naming conventions
  - [x] The web app includes the ability to reset the database to its default state
- [x] The project includes these frontend-specific features:
  - [x] At least one redirection, where users are able to navigate to a new page with a new URL within the app
  - [x] At least one interaction that the user can initiate and complete on the same page without navigating to a new page
  - [x] Dynamic frontend routes created with React Router
  - [x] Hierarchically designed React components
    - [x] Components broken down into categories, including Page and Component types
    - [x] Corresponding container components and presenter components as appropriate
- [x] The project includes dynamic routes for both frontend and backend apps
- [x] The project is deployed on Render with all pages and features that are visible to the user are working as intended

### Custom Features

👉🏾👉🏾👉🏾 Check off each completed feature below.

- [x] The project gracefully handles errors
- [x] The project includes a one-to-one database relationship
- [x] The project includes a slide-out pane or modal as appropriate for your use case that pops up and covers the page content without navigating away from the current page
- [x] The project includes a unique field within the join table
- [x] The project includes a custom non-RESTful route with corresponding controller actions
- [x] The user can filter or sort items based on particular criteria as appropriate for your use case
- [x] Data is automatically generated in response to a certain event or user action. Examples include generating a default inventory for a new user starting a game or creating a starter set of tasks for a user creating a new task app account
- [x] Data submitted via a POST or PATCH request is validated before the database is updated (e.g. validating that an event is in the future before allowing a new event to be created)
  - [x] *To receive full credit, please be sure to demonstrate in your walkthrough that for certain inputs, the item will NOT be successfully created or updated.*

### Stretch Features

👉🏾👉🏾👉🏾 Check off each completed feature below.

- [x] A subset of pages require the user to log in before accessing the content
  - [x] Users can log in and log out via GitHub OAuth with Passport.js
- [x] Restrict available user options dynamically, such as restricting available purchases based on a user's currency
- [x] Show a spinner while a page or page element is loading
- [x] Disable buttons and inputs during the form submission process
- [x] Disable buttons after they have been clicked
  - *At least 75% of buttons in your app must exhibit this behavior to receive full credit*
- [x] Users can upload images to the app and have them be stored on a cloud service
  - *A user profile picture does **NOT** count for this rubric item **only if** the app also includes "Login via GitHub" functionality.*
  - *Adding a photo via a URL does **NOT** count for this rubric item (for example, if the user provides a URL with an image to attach it to the post).*
  - *Selecting a photo from a list of provided photos does **NOT** count for this rubric item.*
- [x] 🍞 [Toast messages](https://www.patternfly.org/v3/pattern-library/communication/toast-notifications/index.html) deliver simple feedback in response to user events

## Final Demo GIF

🔗 [Here's a GIF walkthrough of the final project](👉🏾👉🏾👉🏾 your link here)

## Reflection

### 1. What went well during this unit?

One of the biggest wins was how quickly our group formed a clear idea and turned it into an actual product. We combined concepts from previous labs, projects, and new features we wanted to experiment with, and it genuinely felt like building a real startup-style prototype. Our collaboration on Slack worked well for our main communciations, sharing updates, dividing tasks, and keeping everyone aligned. The idea and implementation phase was exciting because we weren’t just completing an assignment; we were creating something we believed could exist in the real world.

### 2. What were some challenges your group faced in this unit?

The biggest challenge was time management. Balancing school, other assignments, and building a full project in just a few weeks made it difficult to stay perfectly synchronized. Sometimes tasks piled up toward the end, and there were moments where more frequent team working sessions would have helped us move faster. We also had to coordinate different skill levels and work habits, which created some uneven pacing ...but we adapted best that we could and made it work.

### 3. What were some of the highlights or achievements that you are most proud of in this project?
I’m most proud that we got everything connected end-to-end,  the frontend, backend, API routes, deployment, and UI all functioning as one experience. Working with APIs and seeing our data flow properly felt like a major milestone. Another highlight was receiving feedback during the demo day: other teams introduced ideas like automated workout tracking and background activity logging, which validated our concept and opened the door for future improvements. Overall, the creativity and technical execution came together better than we expected.

### 4. Reflecting on your web development journey so far, how have you grown since the beginning of the course?

We have grown in our confidence to tackle big projects. At the beginning of the course, building full websites felt overwhelming. Now we understand how the pieces connect, how to structure a project, and how to collaborate effectively within a team. We have all become more comfortable troubleshooting issues, reading error messages, and navigating the frontend-to-backend workflow. This project pushed us to think like a developer. 

### 5. Looking ahead, what are your goals related to web development, and what steps do you plan to take to achieve them?

Adrian: my main goals are to improve my backend skills, get faster at debugging, and continue building real, functional products. I want to get more comfortable designing APIs, connecting databases, and deploying apps more efficiently. I plan to do this by continuing to build personal projects, practicing with frameworks, and studying backend architecture. I also want to work on more team-based builds, since collaborative problem-solving was one of the best parts of this experience.

Abby: Looking ahead, my main goal is to become stronger at building fully functional, polished products from start to finish. I want to improve the way I design and execute APIs so that my projects feel more seamless and professional. I also hope to push myself creatively by exploring new features and ideas that make my work stand out. To achieve this, I plan to keep experimenting with personal projects and studying real-world examples of good product design. Ultimately, I want to build things that feel both innovative and genuinely useful.

Anthony: I want to focus on becoming a stronger team collaborator who contributes more effectively during group projects. I hope to improve my project execution and organization skills so that I can help keep the team aligned and on schedule. Another big goal for me is expanding my portfolio with more polished and diverse web development projects. To do that, I want to continue practicing with new tools and frameworks outside of class. Overall, I want to grow into someone who can communicate well, support my teammates, and produce high-quality work consistently
