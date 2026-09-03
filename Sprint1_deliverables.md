# Deliverables

## 1. Project Description

**Include:**
* **Project title:** Sanahaku
* **Team members:** Anastasiia, George, Veronika, Maria
* **Target users:** Finnish language students, language teachers and tutors
* **Stakeholders:** Conversational Finnish learners who need reliable visual and auditory examples of native pronunciation
* **Problem being addressed:** there are services that scan youtube for a particular phrase to do exactly this but they do not have finnish as an option presumably because they don't care
  theoretically with how the youtube api works any language at all could be used with this
* **Product vision:** To provide a fast, web-based learning platform that bridges the gap between textbook Finnish and spoken language by dynamically finding, timestamping, and playing YouTube videos at the exact moment a phrase is pronounced -  supplemented by AI context tools to reinforce learning.
* **Main functionality:**

A website that has:

### 1. Core Search & Embedded Media
* **Timestamped Video Synchronization:** Queries YouTube caption data for the exact Finnish phrase and instantly loads an embedded player queued to the precise starting second.
* **Navigation Controls:** Next/Previous buttons allow users to seamlessly jump through every video occurrence found across the database.
* **Automatic Spellchecking:** Detects and suggests corrections for misspelled Finnish input prior to searching to handle complex Finnish morphology.

### 2. AI & Study Support
* **AI Context Generator:** Uses AI to auto-generate simple, everyday example sentences incorporating the searched phrase to help users practice applying it in conversation.
* **Bookmark System:** Allows users to save specific phrase timestamps or full video clips to personal libraries for later review.

### 3. User Interface & Personalization
* **Theme Switching:** Native support for both Dark Mode and Light Mode toggling.
* **Clean Player Layout:** A distraction-free interface focused purely on the video segment, transcript line, and practice panel

---

## 2. Product Backlog

**Include:**

**User stories:**
* **US-01: Phrase Search**
  * **As a** Finnish learner, **I want to** search for a specific Finnish word or phrase, **so that** I can find video clips where native speakers use it.
  * **Acceptance Criteria:** Integrates with YouTube API/caption index; handles case-insensitive queries; returns a list of matching videos.
* **US-02: Timestamped Player**
  * **As a** user, **I want** the embedded player to automatically start at the exact second the phrase is spoken, **so that** I don't have to manually scrub through the video.
  * **Acceptance Criteria:** Uses YouTube IFrame Player API; sets start parameter dynamically based on transcript offset.
* **US-03: Result Navigation**
  * **As a** user, **I need** the ability to switch between all the videos the site finds, to have more than one example
  * **Acceptance Criteria:** Allows skipping forward/backward through result items without reloading the entire page.
* **US-04: Theme Toggle**
  * **As a** user, **I need** a dark/light mode option, because I hate light mode
  * **Acceptance Criteria:** defaults to system preferences.
* **US-05: Finnish Spellchecker**
  * **As a** user, **I need** a spellchecker, because I might mistype and I don't want to get errors until I correct
  * **Acceptance Criteria:** Analyzes input before search execution; prompts user with "Did you mean X?" if a spelling mismatch is detected.
* **US-06: Bookmark System**
  * **As a** user, **I need** a way to bookmark phrases to easily come back to them later
  * **Acceptance Criteria:** LocalStorage or user database persistence; accessible via a dedicated "Saved Phrases" view.
* **US-07: AI Practice Sentence Generator**
  * **As a** user, **I need** an option to AI generate new sentences where the phrase could apply to practice easier
  * **Acceptance Criteria:** Connects to an LLM endpoint; generates 3–5 natural conversational sentences in Finnish with English translations.

---

## 3. Sprint 1 Documentation

**Sprint Goal:** to find the final idea for the project, create the initial design, and prototype the most important functionality according to the chosen user stories.to split roles and organize our responsibilities and workflow.

**Sprint Backlog:**
* Task 1.1 (Ana): Setup repository, branch protection rules, and Trello project board.
* Task 1.2 (Ana): Create Sprint backlog and write Sprint documentation.
* Task 1.3 (Ana): Track and log Scrum sessions throughout the sprint.
* Task 1.4 (George): Write product description and project requirements.
* Task 1.5 (George): Write initial product backlog and define core user stories.
* Task 1.6 (Maria): Create project presentation slides.
* Task 1.7 (Nika): Verify student status on Figma.
* Task 1.8 (Nika - UI/UX): Design Figma Video Page for the "Find Word" user journey.
* Task 1.9 (Nika - UI/UX): Build interactive Figma prototype and optional AI integration UI components.
* Task 1.10 (Nika): Deliver Figma prototype links and design assets to a team.
* Task 1.11 (In Progress): Set up CSS / Tailwind styling framework.

**Definition of Done**
* **Design:** Wireframes/UI prototypes are reviewed and approved by the team.
* **Documentation:** relevant updates are documented in the GitHub or project wiki.
* **Project Management:** The associated card on the Trello board is marked as Done.

**Team roles and responsibilities**
* Anastasiia - Scrum Master
* George - Product Owner
* Veronika - Lead UI/UX Designer
* Maria - CSS/Tailwind

**Evidence/reflection on Scrum events**
During our Scrum sessions, we solve any misunderstandings and discuss every problem raised by each team member. In Sprint 1, our daily scrums were quite short because we were just starting and didn't have that many questions to discuss, but these first scrums were still good practice for getting used to the routine, so scrums in future Sprints won't feel so unusual.

**What worked?** So far it has been relatively easy to reach an agreement on any kind of problem, but we'll see how it goes in future scrums.

**What was difficult?** It was sometimes not that easy to accept scrums as a daily chore that we just have to do no matter what, so we had a couple of days without scrums. But then we realized that left too much to discuss at the next scrum session.

So, the lesson from Sprint 1 is that it's better to have short but regular scrum sessions than long ones held less often.

---

## 4. Low-Fidelity Prototype

Submit your prototype or an appropriate export/link.
https://www.figma.com/make/8TR8Xrl4kgxNrMFJ3xoLPF/Learning-By-Video--FISOUND?code-node-id=0-6&t=vkfTH3bhfRDKl47m-0&fullscreen=1

---

## 5. Presentation

https://www.figma.com/slides/gbykFozhIeCLst0rT3KiPa/Untitled?node-id=4-90&t=h7kGgdtaWWgBE2qn-0