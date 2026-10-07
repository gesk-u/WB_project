## Sanahaku — Sprint 3 Documentation

This directory contains the Sprint 3 planning, implementation artifacts and deliverables for Sanahaku, a web platform built to help language learners hear natural, conversational Finnish pronunciation in timestamped YouTube videos.

## Sprint 3 Overview 

**Sprint 3 Goals:** connecting the backend and frontend into fully integrated application, adding AI features into our project, implementing authentication, writing tests, fixing final bugs and improving general functionality and design. At the very end, writing the documentation and deploying the application.

- **Team Members:**
    - Maria (Scrum Master)
    - Anastasiia
    - Georgs
    - Veranika

## Planning
The workflow was split into 5 epics:
- Finishing/ improving frontend and backend functionality.
- Integrating frontend and backend together. 
- Adding AI features (generating sentences with AI + voicing). 
- Adding authentication. 
- Writing tests.

Here is how work was planned to be spread through weeks:
Tasks were split at the start of the sprint between all members, so that we could make progress in all directions and complete the project before the deadline.

## Alignment with Sprint 1 Prototype

The original plan was to have 3 pages as follows:
    1. Search page 1- the starting page to search the word;
    2. Result page 2 - to see videos where searched word is pronounced;
    3. AI page 3 - with AI-generated sentences using the searched word; the sentences can also be voiced by AI.


**The final version of application vs planned prototype:**

**What stayed the same:**
    - All planned functionality was implemented.
    - Page 1 and 2 were done quite close to prototype.

**What ended up different:** 
    - The general design was done in the same style, but in prototype it was rather simplified, so in final result the design has more elements and also some animation.
    - The functionality of the 3rd page (AI-generated sentences that can be voiced by AI), was moved into the second page, so the search results show on the same page videos and generated sentences. Word searchbox was also added into the result page, so user doesn't have to go back to the starting page and can continue search immediately.
    - We added a feature to save favorite words/videos, so now the 3rd page shows the list of saved videos/words to revisit it again.
    - Authentication was added: sign up and login pages were created where user can register itself.

**Summary:** Our final page structure and design were following the original prototype style and functionality, however we managed to add more additional features, so our website can offer more to the user. The main changes were structuring some pages different and improving the design.

## Artifacts of Sprint 3

**Connecting backend and frontend**
- ✓ Frontend fetches videos from YouTube API where searched word is pronounsed and places the searched results correctly.
- ✓ Backend correctly places the request and returns the response.
- ✓ Completed working on unfinished components left from sprint 2.

**Implementing AI**
- ✓ Created a component to display definition of word, sentences and button to voice them with AI.
- ✓ Implemented the backend using the Gemini API to generate sentences.

**Design**
- ✓ Improved design with animations and better styling. 
- ✓ Made transitions between pages/components smoother by using a loading animation.

**Adding the saved words feature**
- ✓ Implementing backend and frontend functionality to enable users to save searched words/videos.
- ✓ Creating automatically guest token for all users.
- ✓ Words are saved in cache.

**Authentication**
- ✓ Frontend pages for signup/login. 
- ✓ Authentication is connected to the database and created users are saved.
- ✓ Navbar is changed depending on the registration status (login/logout)

**Testing**
- ✓ Tests for fetching from the YouTube API.
- ✓ Tests for AI functionality. 
- ✓ Tests for saving words feature. 


## Core Deliverables
Here is the list of fully completed features during the Sprint 3:
- Fully functioning backend code.
- Fully functioning frontend code.
- Integrated application with connected backend and frontend.
- Improved design.
- Saved words functionality was added as a separate page.
- Authentication was added.


## Project Links
- [Deployed website](https://wb-project-metropolia-1.onrender.com/)

- [Link to presentation Sprint 3](https://www.figma.com/slides/9CjE5pQVHDSPfgJxjXgY8D/SANAHAKU_S3?node-id=60-20&t=o5IBVwHaYK8rDDCy-0)

- [Main project repository](https://github.com/gesk-u/WB_project_Metropolia)

- [Trello](https://trello.com/b/cpzmVdSy/sprint3)