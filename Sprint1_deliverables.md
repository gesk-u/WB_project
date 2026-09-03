# Deliverables[cite: 1]

## 1. Project Description[cite: 1]

**Include:**[cite: 1]
* **Project title:** Sanahaku[cite: 1]
* **Team members:** Anastasiia, George, Veronika, Maria[cite: 1]
* **Target users:** Finnish language students, language teachers and tutors[cite: 1]
* **Stakeholders:** Conversational Finnish learners who need reliable visual and auditory examples of native pronunciation[cite: 1]
* **Problem being addressed:** there are services that scan youtube for a particular phrase to do exactly this but they do not have finnish as an option presumably because they don't care[cite: 1]
  theoretically with how the youtube api works any language at all could be used with this[cite: 1]
* **Product vision:** To provide a fast, web-based learning platform that bridges the gap between textbook Finnish and spoken language by dynamically finding, timestamping, and playing YouTube videos at the exact moment a phrase is pronounced -  supplemented by AI context tools to reinforce learning.[cite: 1]
* **Main functionality:**[cite: 1]

A website that has:[cite: 1]

### 1. Core Search & Embedded Media[cite: 1]
* **Timestamped Video Synchronization:** Queries YouTube caption data for the exact Finnish phrase and instantly loads an embedded player queued to the precise starting second.[cite: 1]
* **Navigation Controls:** Next/Previous buttons allow users to seamlessly jump through every video occurrence found across the database.[cite: 1]
* **Automatic Spellchecking:** Detects and suggests corrections for misspelled Finnish input prior to searching to handle complex Finnish morphology.[cite: 1]

### 2. AI & Study Support[cite: 1]
* **AI Context Generator:** Uses AI to auto-generate simple, everyday example sentences incorporating the searched phrase to help users practice applying it in conversation.[cite: 1]
* **Bookmark System:** Allows users to save specific phrase timestamps or full video clips to personal libraries for later review.[cite: 1]

### 3. User Interface & Personalization[cite: 1]
* **Theme Switching:** Native support for both Dark Mode and Light Mode toggling.[cite: 1]
* **Clean Player Layout:** A distraction-free interface focused purely on the video segment, transcript line, and practice panel[cite: 1]

---

## 2. Product Backlog[cite: 1]

**Include:**[cite: 1]

**User stories:**[cite: 1]
* **US-01: Phrase Search**[cite: 1]
  * **As a** Finnish learner, **I want to** search for a specific Finnish word or phrase, **so that** I can find video clips where native speakers use it.[cite: 1]
  * **Acceptance Criteria:** Integrates with YouTube API/caption index; handles case-insensitive queries; returns a list of matching videos.[cite: 1]
* **US-02: Timestamped Player**[cite: 1]
  * **As a** user, **I want** the embedded player to automatically start at the exact second the phrase is spoken, **so that** I don't have to manually scrub through the video.[cite: 1]
  * **Acceptance Criteria:** Uses YouTube IFrame Player API; sets start parameter dynamically based on transcript offset.[cite: 1]
* **US-03: Result Navigation**[cite: 1]
  * **As a** user, **I need** the ability to switch between all the videos the site finds, to have more than one example[cite: 1]
  * **Acceptance Criteria:** Allows skipping forward/backward through result items without reloading the entire page.[cite: 1]
* **US-04: Theme Toggle**[cite: 1]
  * **As a** user, **I need** a dark/light mode option, because I hate light mode[cite: 1]
  * **Acceptance Criteria:** defaults to system preferences.[cite: 1]
* **US-05: Finnish Spellchecker**[cite: 1]
  * **As a** user, **I need** a spellchecker, because I might mistype and I don't want to get errors until I correct[cite: 1]
  * **Acceptance Criteria:** Analyzes input before search execution; prompts user with "Did you mean X?" if a spelling mismatch is detected.[cite: 1]
* **US-06: Bookmark System**[cite: 1]
  * **As a** user, **I need** a way to bookmark phrases to easily come back to them later[cite: 1]
  * **Acceptance Criteria:** LocalStorage or user database persistence; accessible via a dedicated "Saved Phrases" view.[cite: 1]
* **US-07: AI Practice Sentence Generator**[cite: 1]
  * **As a** user, **I need** an option to AI generate new sentences where the phrase could apply to practice easier[cite: 1]
  * **Acceptance Criteria:** Connects to an LLM endpoint; generates 3–5 natural conversational sentences in Finnish with English translations.[cite: 1]

---

## 3. Sprint 1 Documentation[cite: 1]

**Sprint Goal:** to find the final idea for the project, create the initial design, and prototype the most important functionality according to the chosen user stories.to split roles and organize our responsibilities and workflow.[cite: 1]

**Sprint Backlog:**[cite: 1]
* Task 1.1 (Ana): Setup repository, branch protection rules, and Trello project board.[cite: 1]
* Task 1.2 (Ana): Create Sprint backlog and write Sprint documentation.[cite: 1]
* Task 1.3 (Ana): Track and log Scrum sessions throughout the sprint.[cite: 1]
* Task 1.4 (George): Write product description and project requirements.[cite: 1]
* Task 1.5 (George): Write initial product backlog and define core user stories.[cite: 1]
* Task 1.6 (Maria): Create project presentation slides.[cite: 1]
* Task 1.7 (Nika): Verify student status on Figma.[cite: 1]
* Task 1.8 (Nika - UI/UX): Design Figma Video Page for the "Find Word" user journey.[cite: 1]
* Task 1.9 (Nika - UI/UX): Build interactive Figma prototype and optional AI integration UI components.[cite: 1]
* Task 1.10 (Nika): Deliver Figma prototype links and design assets to a team.[cite: 1]
* Task 1.11 (In Progress): Set up CSS / Tailwind styling framework.[cite: 1]

**Definition of Done**[cite: 1]
* **Design:** Wireframes/UI prototypes are reviewed and approved by the team.[cite: 1]
* **Documentation:** relevant updates are documented in the GitHub or project wiki.[cite: 1]
* **Project Management:** The associated card on the Trello board is marked as Done.[cite: 1]

**Team roles and responsibilities**[cite: 1]
* Anastasiia - Scrum Master[cite: 1]
* George - Product Owner[cite: 1]
* Veronika - Lead UI/UX Designer[cite: 1]
* Maria - CSS/Tailwind[cite: 1]

**Evidence/reflection on Scrum events**[cite: 1]
During our Scrum sessions, we solve any misunderstandings and discuss every problem raised by each team member.[cite: 1] In Sprint 1, our daily scrums were quite short because we were just starting and didn't have that many questions to discuss, but these first scrums were still good practice for getting used to the routine, so scrums in future Sprints won't feel so unusual.[cite: 1]

**What worked?** So far it has been relatively easy to reach an agreement on any kind of problem, but we'll see how it goes in future scrums.[cite: 1]

**What was difficult?** It was sometimes not that easy to accept scrums as a daily chore that we just have to do no matter what, so we had a couple of days without scrums.[cite: 1] But then we realized that left too much to discuss at the next scrum session.[cite: 1]

So, the lesson from Sprint 1 is that it's better to have short but regular scrum sessions than long ones held less often.[cite: 1]

---

## 4. Low-Fidelity Prototype[cite: 1]

Submit your prototype or an appropriate export/link.[cite: 1]
https://www.figma.com/make/8TR8Xrl4kgxNrMFJ3xoLPF/Learning-By-Video--FISOUND?code-node-id=0-6&t=vkfTH3bhfRDKl47m-0&fullscreen=1[cite: 1]

---

## 5. Presentation[cite: 1]

https://www.figma.com/slides/gbykFozhIeCLst0rT3KiPa/Untitled?node-id=4-90&t=h7kGgdtaWWgBE2qn-0[cite: 1]