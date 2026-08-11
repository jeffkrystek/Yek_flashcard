# Decision 001

**Date:** 2026-07-07

**Status:** Accepted

**Category:** Legal

---

## Decision

Use a custom **"All Rights Reserved"** license for the GitHub repository instead of an open-source license such as the MIT License or GNU General Public License (GPL) v3.

---

## Context

The repository is intended to serve as:

- A professional software engineering portfolio
- A project management portfolio
- Documentation of the software development lifecycle
- A demonstration of technical writing and project planning

The project may also lead to future commercial opportunities, including:

- Mobile application sales
- Premium application features
- Paid project management templates
- Educational content and YouTube tutorials

---

## Alternatives Considered

### Option 1 – MIT License

**Pros**

- Extremely popular
- Encourages community adoption
- Very simple license
- Employers immediately recognize it

**Cons**

- Allows commercial reuse
- Allows proprietary derivatives
- Others could incorporate significant portions of the project into their own products with minimal restrictions

---

### Option 2 – GNU GPL v3

**Pros**

- Protects against proprietary forks
- Encourages open-source contributions
- Requires derivative software to remain open source

**Cons**

- Still allows redistribution
- Does not prevent others from using the project commercially under GPL terms
- Not aligned with potential future commercialization of project assets

---

### Option 3 – Custom "All Rights Reserved"

**Pros**

- Retains full ownership of all project assets
- Allows employers and recruiters to review the repository
- Protects documentation, templates, source code, and media assets
- Preserves flexibility for future commercialization
- Clearly communicates that the repository is a portfolio rather than an open-source project

**Cons**

- External developers cannot legally contribute without permission
- The repository cannot be considered open source
- May reduce opportunities for community collaboration

---

## Decision Rationale

The primary objective of this repository is to demonstrate professional software engineering and project management skills rather than encourage community development.

Maintaining full copyright ownership protects intellectual property while still allowing employers, recruiters, and other evaluators to inspect the implementation, documentation, and project history.

Because the project may later include commercially valuable assets, retaining all rights provides the greatest flexibility for future distribution and licensing decisions.

---

## Consequences

### Positive

- Full control of intellectual property
- Professional portfolio remains publicly viewable
- Commercial opportunities remain available
- Documentation and templates remain protected

### Negative

- Repository is not open source
- Community contributions require explicit permission
- Reduced opportunity for open-source collaboration

---

## Related Documents

- LICENSE
- README.md
- Project Charter
- Business Case
- Marketing Strategy

---

## Follow-up Actions

- Create LICENSE file
- Add licensing section to README.md
- Review licensing approach prior to public release of the repository

---

## Review Date

Upon public release of the repository or before commercialization of the project.

## Impact

Project Areas Affected

- ☑ Documentation
- ☑ Source Code
- ☑ Website
- ☑ Marketing
- ☐ Database
- ☐ UI/UX
- ☐ Testing
- ☐ Deployment


# Decision 002

**Date:** 2026-08-10

**Status:** Accepted

**Category:** Legal

---

## Decision

The initial release will focus on native English speakers learning Farsi.

---

## Context

The app will attempt to expand in future versions depending on anticipated demand, developer commitment, and availability of researouces (native language speakers).

While the planned architecture will easily allow additional languages to be added, via JSON files, it will open the possibility of delays, paying language contrators, and other legal considerations that can be avoided in order to produce a MVP.

---

## Alternatives Considered

French and Spanish were considered as they are highly popular languages and generally have higher demand. Developer has novice level of the French language making setup quicker than all other languages.

Other languages such as Chinese and Turkish were considered as I might have readily avialble native speakers who oould be willing to participate and/or be contracted. Less familiarity with these languages combined with new alphabets and characters make it challenging.

---

## Decision Rationale

One language pair keeps the MVP focused rather than attempting multiple languages immediately.

---

## Consequences

Farsi has a relatively small learner interest base compared to French and Spanish. Therefore it is anticipated to have fewer downloads, user engagement, and other volume metrics.

Each additional language would take approximately a minimum of one month (best case) to develop, record audio, verify content, and test. One language pair allow for the quickest launch while still meeting all project goals.

---

## Related Documents

- Project Charter
- Stakeholder Register
- PRD
- Release Roadmap
- WBS
- Project Schedule
- Business Case Document

---

## Follow-up Actions

- Research most impactful languages to add combined with accessibility to resources for future releases.

---

## Review Date

Upon or near release of MVP for consideration of additional languages.

---

## Impact

Project Areas Affected

- Documentation
- Source Code (JSON files)
- Monitization
- Legal (for contractors)


# Decision 003

**Date:** 2026-08-10

**Status:** Accepted

**Category:** Content

---

## Decision

The initial release will consist of 12 learning categories.

---

## Context

The app will expand on content through updates as the app grows. A MVP will provide basic but regularly used words that appear in natural conversations.

---

## Alternatives Considered

I currently have an estimated 100 potential categories that could be implemented or added in the future. I will choose the most commons words, mostly nouns and organized in categories, that appear in regualr conversations. 

---

## Decision Rationale

Provides meaningful MVP content without requiring hundreds/thousands of words immediately.

---

## Consequences

Limited categories at launch might not serve the complete interests of a new language learner. Notes can be made within the app to state additional categories are in development and will be included later.  Users might run out of flashcards to learn and abandon the app.

Users may feel that because the content is limited that they will look elsewhere before investing time into a new app. 

The option to add additional categories after launch could be an opportunity for Premium users to get instant or early access.

---

## Related Documents

- Project Charter
- PRD
- Release Roadmap
- Content Plan

---

## Follow-up Actions

- Decide on the exact categories and how granular they will be. Should I use "Animals" or split into "Mammels", "Birds", "Reptiles", etc.?

---

## Review Date

Before the creation of JSON files which will organize the categories and vocabulary words.

---

## Impact

Project Areas Affected

- Documentation
- Source Code (JSON files)
- Monitization
- Monitor and Controlling
- Content Management

# Decision 004

**Date:** 2026-08-10

**Status:** Accepted

**Category:** Content

---

## Decision

Target approximately 20–50 vocabulary items per category

---

## Context

Each category will have similar and related items that are intuitively organized. Learning by grouped words makes learning engaging and relevant. 

---

## Alternatives Considered

Some categories will naturally have more or fewer words that feel appropriate to be included. Categories such as "Colors" gets to more uncommon colors after 15-20 entries. Whereas "Household Items" could easily have 50+ items that are regularly seen and used on a given day and worthy of learning.

Categories should be long enough (20 min) to have meaningful groupings but not too long (50 max) as to not be too broad and seem unrelated. The length of categories should also not overwhelm users with too many new words to try and learn at once.

---

## Decision Rationale

Provides enough content for useful study while keeping initial content creation manageable.

---

## Consequences

Limiting the word database at launch might not serve the complete interests of a new language learner. Users might run out of flashcards to learn and abandon the app.

Users may feel that because the content is too limited that they will look elsewhere before investing time into a new app. 

---

## Related Documents

- Project Charter
- PRD
- Content Plan

---

## Follow-up Actions

- Decide on which words, and how many, to include into each category. Will be case-by-case as each category will have its own natural list.

---

## Review Date

Before the creation of JSON files which will organize the categories and vocabulary words.

---

## Impact

Project Areas Affected

- Documentation
- Source Code (JSON files)
- Monitization
- Content Management


# Decision 005

**Date:** 2026-08-10

**Status:** Accepted

**Category:** Scope

---

## Decision

The application will support offline flashcard functionality.

---

## Context

A simple differentiator for this app will include full content review without an internet connection. This sets it apart from other applications that need to stay connected to the internet for fully work.

---

## Alternatives Considered

A required internet connection will only be necessary for updates, purchases, and data uploads to the developer. An internet connection is an unnecessary addition for an application with this scope.

Internet related features, such as cross-device sync and user accounts, can be added later due to architectural design.

---

## Decision Rationale

A core product requirement and useful feature for learners without reliable internet access.

---

## Consequences

Users have the possibly of losing their data and progress since the data will be stored on their devices and not the cloud. 

Updates to the developer, such as statistic. analytics, feedback, and crash reports, will be delayed until the user connects to the internet for automatic uploads. 

Users might not always have the most updated version.

Users might miss announcements.

Ads will not show, limiting ad revenue.

---

## Related Documents

- Vision Document
- Project Charter
- PRD
- Architectural Design
- Project Scope Statement
- Communication Plan
- Risk Register

---

## Follow-up Actions

- None

---

## Review Date

After testing offline functionality.

---

## Impact

Project Areas Affected

- Documentation
- Source Code (offline management and storage)
- Monitization
- Stakeholder Communication
- Analytics


# Decision 006

**Date:** 2026-08-10

**Status:** Accepted

**Category:** Scope

---

## Decision

User Accounts are excluded from the initial scope.

---

## Context

User accounts create a reliable environment for saving their data, progress, and logging in to multiple devices. Setting this up as a new developer with no experience was not going to be an easy task and can be a feature in later versions.

---

## Alternatives Considered

Storing data on their local device allows for offline study which is a core feature of this product. This could also be done with the account login but it bypasses a large workload to get the MVP launched sooner.

It could be possible to have no saved data and just work fresh each study session. This would mean recording no user data for statistical purposes. This was not chosen because longitudinal user data are valuable analytics for both the developer and good user experience to see basic progress stats.

---

## Decision Rationale

Keeps the MVP simpler and avoids requiring account infrastructure.

---

## Consequences

Users have the possibly of losing their data and progress since the data will be stored on their devices and not the cloud. 

Unable to gather user emails for alternate method of communication.

Users lock their progress to one device at a time. Separate devices will have different progress. User can redownload on the same Apple/Google platform to retain purchase information most times. Not ideal for Premium plans. If they switch platforms the Premium won't be cross-recognized by Apple/Google.

---

## Related Documents

- Project Charter
- PRD
- Architectural Design
- Project Scope Statement
- Communication Plan
- Risk Register

---

## Follow-up Actions

- Consider user accounts after V1.0 launch.

---

## Review Date

After V1.0 launch.

---

## Impact

Project Areas Affected

- Documentation
- Source Code (offline management and storage)
- Monitization
- Stakeholder Communication
- Analytics
- Risk Analysis
- User Experience


# Decision 007

**Date:** 2026-08-10

**Status:** Accepted

**Category:** Project Management

---

## Decision

Use Agile/Scrum methodology

---

## Context

Agile Scrum works well when there is somewhat high uncertainty and best to review during iterive updates. While this project has some well-defined terms and goals from the outset, how to get there, how to do it, how long it will take, among other uncertainties, including my own regular feedback, lead me to using an Agile Scrum framework.

---

## Alternatives Considered



---

## Decision Rationale

Allows incremental development and provides useful PM experience/documentation.

---

## Consequences

Not having a predefined, absolute project schedule could lead to work slippage, causing delays.

Scope change could get overwhelming if I decide to take on too many tasks not critical to the MVP. I could change my mind on many things over and over without a more formalized structure from the beginning.

It is not strictly Agile Scrum as I do have many points of interest set from the beginnning and I am using a Kanban board for Sprints. I also do not have regular standups (being a sole developer).

---

## Related Documents

- WBS
- Project Schedule
- Jira backlog

---

## Follow-up Actions

- Regular reviews after each 3-week Sprint.

---

## Review Date

After each Sprint.

---

## Impact

Project Areas Affected

- Documentation
- Work flow
- Project Planning