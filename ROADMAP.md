# Yek Flashcards — Project Roadmap

**Project:** Yek Flashcards  
**Repository:** `Yek_flashcard`  
**Primary Goal:** Develop and launch a Farsi language-learning flashcard application while documenting the project as a professional project-management and software-development portfolio piece.  
**Target Launch:** January 1, 2027 *(target; flexible if additional development time is required)*  
**Development Capacity:** Approximately 10 hours/week  
**Current Roadmap Version:** 1.0  
**Last Updated:** August 29, 2026

---

## 1. Roadmap Purpose

This roadmap provides a high-level view of the major phases, milestones, and deliverables required to take Yek Flashcards from project planning through public launch and post-launch improvement.

Yek Flashcards serves two purposes:

1. **Product:** A functional mobile flashcard application for language learning, initially focused on Farsi and English.
2. **Portfolio Project:** A publicly documented demonstration of project management, software development, requirements analysis, UX/UI design, testing, analytics, and product decision-making.

The roadmap is intentionally higher-level than the Jira backlog and project schedule. Jira should contain the individual Stories, Tasks, and technical work items required to execute each roadmap phase.

---

# 2. Product Vision

Yek Flashcards will provide a simple, accessible way for users to learn vocabulary between Farsi and English using flashcards, pronunciation audio, categories, and eventually additional learning and retention features.

The initial product will prioritize:

- Simple vocabulary learning
- Farsi ↔ English translation
- Native-speaker pronunciation
- Audio-assisted learning
- Category-based vocabulary
- Offline access to core flashcard content
- Simple, intuitive navigation
- A foundation for future languages and content
- A sustainable free/premium business model

The initial primary audience is English speakers learning Farsi, with the potential for native Farsi speakers learning English to become a secondary audience.

---

# 3. Roadmap at a Glance

| Phase | Major Focus | Target Status |
|---|---|---|
| Phase 1 | Project Initiation & Planning | 🟢 Substantially Complete |
| Phase 2 | Requirements & Product Definition | 🟢 Substantially Complete |
| Phase 3 | UX/UI Design | 🟡 In Progress |
| Phase 4 | Technical Architecture & Setup | 🟡 In Progress |
| Phase 5 | Content & Audio Production | 🟡 In Progress |
| Phase 6 | Core MVP Development | 🟡 Upcoming / In Progress |
| Phase 7 | Feature Development & Monetization | ⚪ Upcoming |
| Phase 8 | Testing & Quality Assurance | ⚪ Upcoming |
| Phase 9 | Launch Preparation | ⚪ Upcoming |
| Phase 10 | Public Launch | ⚪ Upcoming |
| Phase 11 | Post-Launch Monitoring & Improvement | ⚪ Future |

**Status Key**

- 🟢 Complete / substantially complete
- 🟡 In progress
- ⚪ Not started
- 🔴 Blocked
- 🔵 Future enhancement

---

# 4. Phase 1 — Project Initiation & Planning

**Status:** 🟢 Substantially Complete

### Objective

Establish the project's purpose, scope, goals, stakeholders, constraints, and overall management approach.

### Major Deliverables

- Project Charter
- Business Case
- Vision Document
- Project Scope Statement
- Initial Success Metrics
- Stakeholder Register
- Communication Plan
- Initial Risk Register
- Project Management approach
- Initial WBS
- Project Schedule
- Budget framework
- Decision Log
- Changelog
- Project documentation structure

### Key Accomplishments

- Defined Yek Flashcards as both a software-development project and a PM portfolio project.
- Established the project's language-learning focus.
- Established the intended free/premium business model.
- Established the initial target launch date.
- Established approximately 10 hours/week as the expected development capacity.
- Began documenting project decisions and changes.
- Established GitHub as a primary development/documentation repository.
- Began using Jira for project execution and backlog management.

### Exit Criteria

- Project purpose documented
- Scope defined
- Major stakeholders identified
- Initial risks documented
- Project management system established
- High-level roadmap approved

**Phase Status:** Complete enough to support execution.

---

# 5. Phase 2 — Requirements & Product Definition

**Status:** 🟢 Substantially Complete

### Objective

Define what Yek Flashcards must do and establish traceability between requirements, design, development, and testing.

### Major Deliverables

- Product Requirements Document (PRD)
- Functional Requirements
- Non-Functional Requirements
- User Stories
- Acceptance Criteria
- Success Metrics
- Feature prioritization
- Product backlog
- Requirements Traceability structure

### Core Product Requirements

Initial functionality is expected to include:

- Display vocabulary flashcards
- Display Farsi and English vocabulary
- Reveal/hide translations
- Play pronunciation audio
- Organize vocabulary into categories
- Navigate between cards
- Support multiple vocabulary categories
- Support offline access to core vocabulary
- Track appropriate learning statistics
- Provide settings
- Support future expansion to additional languages/content

### Potential / Future Requirements

- Auto-play
- Configurable audio order
- Streak tracking
- Premium statistics
- Ads
- Premium subscription
- Lifetime premium purchase
- User voting for new content/categories
- Additional language support
- Merchandise/reward integrations
- Additional analytics

### Exit Criteria

- MVP requirements approved
- Backlog sufficiently defined
- Requirements linked to user stories
- Major scope boundaries established

**Phase Status:** Substantially complete, with requirements continuing to evolve as design and development reveal new needs.

---

# 6. Phase 3 — UX/UI Design

**Status:** 🟡 In Progress

### Objective

Design a simple and intuitive mobile experience before significant UI implementation begins.

### Major Activities

- Establish UI design system
- Create wireframes
- Create mockups
- Define navigation structure
- Design flashcard interface
- Design category selection
- Design settings
- Design statistics
- Design premium-related screens
- Design onboarding if included
- Design error/empty/loading states
- Review accessibility considerations

### Key Screens

At minimum, design should address:

1. Home / Main Screen
2. Category Selection
3. Flashcard Screen
4. Audio Controls
5. Statistics
6. Settings
7. Premium / Upgrade
8. About / Information
9. Appropriate onboarding/help screens

### Design Tools

Figma and/or another suitable wireframing/mockup tool may be used.

Material Design principles may be used as a design reference rather than treated as a source of automatically generated application code.

### Deliverables

- UX flow
- Wireframes
- High-fidelity mockups
- UI component definitions
- Navigation map
- Design decisions documented in Decision Log

### Exit Criteria

- Core user flows designed
- MVP screens approved
- Designs sufficiently detailed for implementation

---

# 7. Phase 4 — Technical Architecture & Development Environment

**Status:** 🟡 In Progress

### Objective

Establish the technical foundation necessary to develop, test, maintain, and eventually distribute the application.

### Technology

Current development direction includes:

- Flutter
- Dart
- VS Code
- Git
- GitHub

### Major Activities

- Configure Flutter development environment
- Establish project repository
- Establish Git branching/version-control practices
- Define project directory structure
- Define application architecture
- Define data architecture
- Establish JSON content structure
- Establish audio file organization
- Define unique vocabulary IDs
- Establish asset management process
- Establish local/offline data strategy
- Establish configuration/environment approach
- Document architecture

### Architecture Documentation

The Architecture Document should address:

- Application architecture
- UI layer
- Application/business logic
- Data layer
- Local assets
- JSON vocabulary data
- Audio assets
- Analytics
- Advertising
- Premium functionality
- External services
- Future expansion

### Exit Criteria

- Application builds successfully
- Development environment stable
- Architecture documented
- Data structures established
- Asset-management conventions established
- Basic application navigation functional

---

# 8. Phase 5 — Vocabulary, Translation & Audio Content

**Status:** 🟡 In Progress

### Objective

Create high-quality language-learning content that can be integrated into the application.

### Vocabulary Development

Initial content should be organized into categories with approximately 30–50 vocabulary items per category, with the final number determined by the product requirements and available content.

Potential categories include:

- Greetings
- Numbers
- Family
- Food
- Animals
- Colors
- Common verbs
- Common adjectives
- Places
- Household items
- Travel
- Time/date
- Everyday expressions
- Body
- Clothing
- School/work

### Data Structure

Each vocabulary item should have an appropriate unique identifier.

The project should maintain a consistent data model containing appropriate fields such as:

- ID
- English
- Farsi
- Romanization/pronunciation aid where appropriate
- Category
- Audio reference
- Additional metadata where needed

### Audio Production

Audio should prioritize accurate pronunciation and consistency.

The recording workflow should establish:

- Recording environment
- Microphone settings
- Recording distance
- Volume standards
- File format
- Naming convention
- Silence/noise handling
- Quality-control process
- Speaker metadata if needed

Audacity is the planned recording/editing tool.

### Audio Format

Master recordings should be retained in a lossless format such as WAV, while an appropriate compressed format may be generated for application distribution if file size requires it.

### Pronunciation Support

Romanization may be included as a learning aid for English speakers learning Farsi, but it should complement rather than replace the Farsi script.

### Exit Criteria

- Initial vocabulary set completed
- Vocabulary reviewed for accuracy
- Audio recorded
- Audio reviewed
- Content mapped to application data
- Content quality-control process documented

---

# 9. Phase 6 — Core MVP Development

**Status:** 🟡 Upcoming / In Progress

### Objective

Build the minimum viable version of Yek Flashcards containing the essential learning experience.

### MVP Priorities

#### 6.1 Application Foundation

- Application startup
- Navigation
- Basic theme
- Asset loading
- Local data loading

#### 6.2 Vocabulary System

- Load vocabulary from JSON
- Select categories
- Select cards
- Display vocabulary
- Display translations
- Handle card progression

#### 6.3 Audio

- Play Farsi pronunciation
- Play English pronunciation where appropriate
- Play/pause/replay
- Handle missing audio gracefully

#### 6.4 Flashcard Experience

- Card display
- Flip/reveal behavior
- Next/previous functionality as appropriate
- Category context
- Audio controls
- Appropriate visual feedback

#### 6.5 Offline Functionality

Core vocabulary and associated assets should remain usable without an internet connection.

### MVP Exit Criteria

A user should be able to:

1. Open the application.
2. Select a vocabulary category.
3. View a flashcard.
4. See the appropriate Farsi/English content.
5. Reveal the answer/translation.
6. Hear pronunciation audio.
7. Continue through the vocabulary set.
8. Use the core experience without an internet connection.

---

# 10. Phase 7 — Feature Development & Monetization

**Status:** ⚪ Upcoming

### Objective

Expand beyond the basic MVP and implement features that improve retention, usability, and potential revenue.

### Potential Features

#### Learning Features

- Auto-play
- Configurable audio order
- Streaks
- Learning statistics
- Progress tracking
- Additional study modes

#### Engagement

- Daily streak points
- Rewards
- Achievement system
- User voting
- New category requests

#### Monetization

Potential model:

**Free Version**
- Core flashcard functionality
- Advertising
- Limited statistics/features

**Premium Version**
- Reduced/no advertising
- Expanded statistics
- Additional features
- Potential premium content
- Potential lifetime purchase option

### Premium Voting Concept

One possible engagement model is:

- Free users: limited voting frequency
- Premium users: increased voting frequency

This should be evaluated through product testing rather than assumed to be necessary for the MVP.

### Exit Criteria

- Priority post-MVP features selected
- Monetization model finalized
- Premium functionality defined
- Analytics requirements established

---

# 11. Phase 8 — Testing & Quality Assurance

**Status:** ⚪ Upcoming

### Objective

Verify that the application works reliably and provides an accurate, usable learning experience.

### Testing Areas

#### Functional Testing

- Navigation
- Flashcards
- Categories
- Audio
- Settings
- Statistics
- Premium functionality
- Advertising
- Offline functionality

#### Content Testing

- Translation accuracy
- Spelling
- Farsi script
- Romanization
- Audio accuracy
- Audio-to-word mapping
- Category assignment

#### Device Testing

Test across appropriate:

- Screen sizes
- Operating-system versions
- Performance conditions
- Offline/online states

#### Usability Testing

Test with representative users, particularly:

- English speakers learning Farsi
- Native Farsi speakers where relevant

### Quality Documentation

- Test Plan
- Test Cases
- Defect Log
- QA results
- User Acceptance Testing
- Release checklist

### Exit Criteria

- Critical defects resolved
- MVP acceptance criteria met
- Core content validated
- Performance acceptable
- Release candidate approved

---

# 12. Phase 9 — Launch Preparation

**Status:** ⚪ Upcoming

### Objective

Prepare the application, documentation, marketing, analytics, and operational systems for public release.

### App Store / Distribution Preparation

- Developer account setup
- Application metadata
- Application icon
- Screenshots
- Store description
- Privacy documentation
- Terms where appropriate
- Age/content ratings
- Pricing configuration
- Premium configuration
- Advertising configuration

### Analytics

Implement anonymous analytics capable of measuring useful product metrics such as:

- Downloads
- Active users
- Sessions
- Category usage
- Flashcard usage
- Audio usage
- Retention
- Streak participation
- Premium conversion
- Advertising interactions where appropriate

Analytics should avoid collecting unnecessary personally identifiable information.

### Marketing / Website

- Portfolio website
- Project overview
- Product screenshots
- Project documentation
- Development story
- PM artifacts
- GitHub repository
- Launch announcement
- Basic promotional materials

### Exit Criteria

- Release candidate complete
- Store listing complete
- Analytics operational
- Privacy requirements satisfied
- Website ready
- Launch checklist completed

---

# 13. Phase 10 — Public Launch

**Target:** January 1, 2027

### Objective

Release Yek Flashcards to users and establish baseline product performance.

### Launch Activities

- Final production build
- Submit application
- Resolve store-review issues
- Publish application
- Verify production functionality
- Monitor crash reports
- Monitor analytics
- Monitor user feedback
- Track initial revenue
- Track acquisition sources

### Launch Metrics

Initial metrics may include:

- Downloads
- Daily/weekly/monthly active users
- Day 1 / Day 7 / Day 30 retention
- Session frequency
- Flashcards studied
- Audio usage
- Category popularity
- Premium conversion
- Ad engagement
- Revenue
- Cost per acquisition where paid advertising is used

### Launch Milestone

**M1 — Public Release**

The application is publicly available and functioning in production.

---

# 14. Phase 11 — Post-Launch Monitoring & Continuous Improvement

**Status:** 🔵 Future

### Objective

Use real-world data and user feedback to improve the application.

### Activities

- Monitor analytics
- Monitor crashes
- Review user feedback
- Analyze retention
- Evaluate monetization
- Identify popular categories
- Identify underused features
- Prioritize improvements
- Release updates
- Add vocabulary
- Improve audio
- Test new monetization approaches
- Conduct periodic retrospectives

### Product Improvement Cycle

**Measure → Analyze → Decide → Implement → Test → Release → Measure Again**

This phase should become an ongoing product-management cycle rather than a one-time milestone.

---

# 15. Major Milestones

| Milestone | Description | Target |
|---|---|---|
| M1 | Project Foundation Complete | Complete |
| M2 | Requirements / PRD Established | Complete / Ongoing refinement |
| M3 | UX/UI MVP Design Complete | Upcoming |
| M4 | Architecture Established | Upcoming |
| M5 | Initial Content Complete | Upcoming |
| M6 | Core MVP Functional | Upcoming |
| M7 | MVP Testing Complete | Upcoming |
| M8 | Release Candidate | Upcoming |
| M9 | Launch Preparation Complete | Upcoming |
| M10 | Public Launch | January 1, 2027 target |
| M11 | First Post-Launch Review | After launch |
| M12 | First Major Product Update | Post-launch |

---

# 16. Project Management Deliverables

Because Yek Flashcards is also intended to demonstrate project-management capability, the following documentation should be maintained alongside development.

### Planning

- Project Charter
- Business Case
- Vision Document
- Project Scope Statement
- Product Requirements Document
- WBS
- Project Schedule
- Roadmap
- Budget

### Requirements

- Functional Requirements
- Non-Functional Requirements
- User Stories
- Acceptance Criteria
- Requirements Traceability Matrix

### Execution

- Jira Backlog
- Sprint Plans
- Sprint Reviews
- Sprint Retrospectives
- Daily/Development Logs
- Time Tracking

### Monitoring & Control

- Risk Register
- Issue/Defect Log
- Decision Log
- Changelog
- Project Performance Dashboard
- Earned Value Analysis where appropriate
- Change Management documentation

### Design & Technical

- Wireframes
- Mockups
- Architecture Document
- Data Model
- Recording Standards
- Content Standards
- Testing Documentation

### Closing / Launch

- Release Checklist
- Launch Plan
- Post-Launch Review
- Lessons Learned
- Final Project Report

---

# 17. Portfolio Strategy

The roadmap should support a second deliverable: demonstrating professional project-management and technical capability to prospective employers.

The final portfolio should demonstrate the ability to:

- Define a project
- Develop a business case
- Establish requirements
- Build a WBS
- Develop a schedule
- Manage a backlog
- Use Jira
- Manage risks
- Track decisions
- Manage scope changes
- Design software
- Develop software
- Conduct testing
- Analyze performance
- Launch a product
- Monitor real-world results
- Conduct retrospectives
- Communicate project status

The goal is not simply to show that an application was built. The portfolio should show **how the project was planned, executed, measured, controlled, and improved.**

---

# 18. Roadmap vs. Jira

The roadmap should remain at the strategic level.

### Roadmap

Answers:

> **Where is the project going and what major stages must it pass through?**

### Jira

Answers:

> **What specific work needs to be completed to get there?**

For example:

**Roadmap:**  
Phase 6 — Core MVP Development

↓

**Epic:**  
Flashcard Experience

↓

**Stories:**
- Create flashcard UI
- Implement card flip
- Display English vocabulary
- Display Farsi vocabulary
- Implement next-card functionality
- Implement audio playback

↓

**Tasks/Subtasks:**  
Specific implementation work.

This hierarchy keeps the roadmap from becoming another copy of the Jira backlog.

---

# 19. Major Dependencies

Several areas of the project depend on one another.

### Requirements → Design

The MVP requirements must be sufficiently defined before final UI designs are created.

### Design → Development

Core screens should be designed before their implementation is finalized.

### Architecture → Development

The data model and application architecture need to support the flashcard system before significant development occurs.

### Content → Testing

Vocabulary and audio need to exist before the complete learning experience can be tested.

### MVP → Monetization

The basic learning experience should work before significant monetization functionality is prioritized.

### Development → QA

A sufficiently complete MVP is required before comprehensive testing.

### QA → Launch

Critical defects must be resolved before release.

### Analytics → Post-Launch Decisions

Analytics must be implemented before meaningful post-launch product decisions can be made from user behavior.

---

# 20. Current Project Priorities

As of August 29, 2026, the project's highest-level priorities are:

### Priority 1 — Finish Product Definition

Finalize the MVP requirements and ensure the Jira backlog accurately represents the intended product.

### Priority 2 — Complete UX/UI Design

Create the wireframes and mockups necessary to confidently implement the major application screens.

### Priority 3 — Finalize Architecture

Document the technical architecture and establish the data/content structure.

### Priority 4 — Build Initial Content

Continue developing vocabulary, translations, romanization where appropriate, and pronunciation audio.

### Priority 5 — Build the MVP

Implement the core flashcard experience before investing heavily in secondary features.

### Priority 6 — Test

Validate functionality, language content, audio, usability, and offline behavior.

### Priority 7 — Prepare for Launch

Complete analytics, monetization decisions, store materials, website, and release documentation.

---

# 21. Scope Management

The January 2027 launch date should **not** require every proposed feature to be completed.

Features such as:

- Advanced statistics
- User voting
- Rewards
- Merchandise
- Giveaways
- Sophisticated premium functionality
- Multiple languages
- Advanced retention mechanics

should remain candidates for post-MVP development unless they become necessary for the core product.

The project should prioritize:

**Functional MVP > Quality > Launch > Data Collection > Expansion**

This approach reduces the risk of scope creep and allows real user data to influence future development.

---

# 22. Definition of a Successful Launch

The initial launch will be considered successful if:

1. The application is publicly available.
2. Users can complete the core flashcard-learning experience.
3. Vocabulary and pronunciation are accurate.
4. Core functionality works offline as intended.
5. Critical defects are resolved.
6. Analytics provide actionable usage data.
7. Users can provide feedback.
8. The project documentation demonstrates a professional development process.
9. Initial user behavior can be measured.
10. Post-launch data can be used to prioritize the next development cycle.

Success should **not** be defined solely by download count or revenue during the first release.

---

# 23. Long-Term Product Direction

Following the initial launch, Yek Flashcards can evolve from a basic flashcard application into a broader language-learning platform.

Potential future directions include:

- Additional language pairs
- Expanded vocabulary
- Spaced repetition
- More advanced statistics
- Personalized learning
- Gamification
- User-generated content
- Community voting
- Premium learning features
- Additional audio resources
- Additional study modes
- Improved retention systems
- Expanded monetization

These remain future possibilities rather than commitments to the initial release.

---

# 24. Roadmap Change Management

This roadmap should be reviewed periodically and updated when there are significant changes to:

- Project scope
- Launch date
- Product strategy
- Major features
- Technology
- Monetization
- Major risks
- Resource availability
- User feedback
- Business objectives

Changes should be documented in the project's **Changelog** and, when appropriate, the **Decision Log**.

The roadmap should not be silently changed simply to make the project appear on schedule.

---

# 25. Roadmap Governance

**Review Frequency:** At major project milestones and approximately monthly during active development.

**Primary Sources for Updates:**

- Jira
- Project Schedule
- Changelog
- Decision Log
- Risk Register
- Sprint Reviews
- Retrospectives
- Project Performance Dashboard

The roadmap represents the current strategic plan. Jira remains the authoritative source for detailed execution work.

---

## 26. Current High-Level Timeline

### August–September 2026
**Planning → Design → Architecture → Content**

Primary focus:
- Complete requirements
- Finish core wireframes
- Develop mockups
- Finalize architecture
- Establish data structures
- Continue vocabulary development
- Begin/continue audio production

### September–October 2026
**MVP Development**

Primary focus:
- Flutter application structure
- Navigation
- JSON data integration
- Flashcard interface
- Categories
- Audio playback
- Offline functionality

### October–November 2026
**Feature Completion + Testing**

Primary focus:
- MVP feature completion
- Initial statistics
- Settings
- Selected secondary features
- Content QA
- Functional testing
- Device testing
- Usability testing
- Bug fixing

### November–December 2026
**Launch Preparation**

Primary focus:
- Release candidate
- Analytics
- Monetization implementation
- Store assets
- Privacy/legal requirements
- Website
- Portfolio documentation
- Final QA
- Launch checklist

### January 2027
**Public Launch**

Target:
**January 1, 2027**

Primary focus:
- Production release
- Monitoring
- Bug fixes
- User feedback
- Initial analytics

### January 2027+
**Post-Launch Improvement**

Primary focus:
- Analyze user behavior
- Measure retention
- Evaluate monetization
- Prioritize new features
- Expand content
- Release updates
- Document lessons learned

---

# 27. Final Roadmap Principle

Yek Flashcards should be developed as both a **product and a professional project-management case study**.

The project should therefore demonstrate the complete lifecycle:

**Initiate → Plan → Define → Design → Build → Test → Launch → Measure → Improve**

The ultimate deliverable is not merely the application.

It is a working application supported by evidence that the project was managed using a disciplined, traceable, data-informed process.