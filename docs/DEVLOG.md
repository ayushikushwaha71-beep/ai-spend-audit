Day 1 — 2026-05-07

Hours worked: 2–3 hour

**What I did:**
Today I went through the full assignment carefully and tried to understand what exactly is expected. I spent time breaking down the idea of the AI Spend Audit tool and what the user flow should look like.
After that, I set up my project using Next.js with TypeScript and Tailwind. I also created a GitHub repository and connected my local project to it.
I didn’t start building features yet, just focused on setup and understanding the structure.

**What I learned:**
I realized this task is more about building a complete product than just writing code. Planning the flow properly is more important before jumping into implementation.

**Blockers / what I'm stuck on:**
Right now I’m a bit unsure about how detailed the pricing data should be and how to structure the audit rules in a clean way.

**Plan for tomorrow:**
Tomorrow I will start building the spend input form and focus on designing a simple and clear user interface.




Day 2 — 2026-05-08

**Hours worked:** 6

**What I did:**  
- Finalized the overall project structure for the AI Spend Audit application.  
- Set up the GitHub repository and cleaned up the Git workflow after accidentally creating a nested repository.  
- Added and organized the required documentation files for the Credex submission:
  - README.md
  - ARCHITECTURE.md
  - DEVLOG.md
  - REFLECTION.md
  - TESTS.md
  - PRICING_DATA.md
  - PROMPTS.md
  - GTM.md
  - ECONOMICS.md
  - USER_INTERVIEWS.md
  - LANDING_COPY.md
  - METRICS.md
- Created the `/docs` folder structure to separate evaluation documents from application code.
- Started researching official pricing pages for:
  - Cursor
  - ChatGPT
  - Claude
  - GitHub Copilot
  - Gemini
- Began designing the audit engine logic:
  - plan downgrade detection
  - per-seat savings calculation
  - alternative tool recommendations
- Added `.gitignore` and configured the repo to avoid pushing secrets and unnecessary files.
- Pushed the latest structure and documentation changes to GitHub.

**What I learned:**  
- Git repositories should never be nested inside each other because it creates tracking and push conflicts.  
- Structuring the repository cleanly matters a lot for AI-based evaluations and long-term maintainability.  
- The audit engine logic is more important than UI polish for this assignment because the recommendations must feel financially credible.

**Blockers / what I'm stuck on:**  
- Pricing structures for AI tools vary significantly between API usage and seat-based plans, so creating consistent comparison logic is harder than expected.  
- Need a better strategy for generating trustworthy savings recommendations without making unrealistic assumptions.

**Plan for tomorrow:**  
- Implement the initial spend input form with persistent local state.  
- Complete the first version of the pricing dataset using official vendor pricing pages.  
- Start building the audit engine with rule-based savings recommendations.  
- Write initial unit tests for savings calculations.


Day 3 — 2026-05-09

**Hours worked:** 7

**What I did:**  
- Completed the initial production-ready folder structure for the AI Spend Audit project.  
- Organized the repository into clear sections for:
  - frontend routes
  - reusable components
  - pricing datasets
  - audit logic
  - prompts
  - testing
  - evaluation documents
- Added all required documentation files mentioned in the assignment brief:
  - ARCHITECTURE.md
  - GTM.md
  - ECONOMICS.md
  - USER_INTERVIEWS.md
  - METRICS.md
  - LANDING_COPY.md
  - PROMPTS.md
  - TESTS.md
- Cleaned up Git history and fixed repository structure issues caused by an accidental nested Git repository.
- Started implementing the pricing dataset structure using official vendor pricing sources.
- Created the initial audit engine files:
  - auditEngine.ts
  - savingsCalculator.ts
  - recommendationEngine.ts
- Began drafting the recommendation logic for:
  - unnecessary team plans
  - per-seat overspending
  - alternative AI tool recommendations
  - API vs subscription cost comparisons
- Set up the testing folder and planned test coverage for audit calculations and edge cases.
- Added `.env.example` and improved `.gitignore` to avoid exposing secrets and generated files.

**What I learned:**  
- A clean repository structure significantly improves maintainability and makes the project easier to review both manually and programmatically.  
- Separating pricing data, recommendation logic, and UI components early prevents unnecessary refactoring later.  
- The assignment is much more focused on product thinking and credibility of recommendations than just frontend polish.

**Blockers / what I'm stuck on:**  
- Some AI tools have complicated pricing structures that depend on token usage instead of fixed subscriptions, making accurate comparison logic more difficult.  
- Need to decide how aggressive the audit recommendations should be without making unrealistic savings claims.

**Plan for tomorrow:**  
- Implement the spend input form UI and local persistence.  
- Add the first working version of the audit calculation flow.  
- Start building the audit results page with savings breakdown cards.  
- Add initial unit tests for savings calculations and recommendation rules.


 Day 4 — 2026-05-10

**Hours worked:** 8

**What I did:**  
- Implemented the initial spend input form UI for the AI Spend Audit application.  
- Added core input fields for:
  - AI tool selection
  - subscription plan
  - monthly spend
  - number of seats
  - team size
  - primary use case
- Started implementing local persistence logic so form data can survive page reloads and accidental refreshes.
- Built the first working version of the audit calculation flow connecting form inputs to recommendation logic.
- Added initial savings calculation logic for:
  - unnecessary team plans
  - oversized subscriptions
  - downgrade recommendations
  - alternative tool suggestions
- Began designing the audit results page with:
  - savings breakdown cards
  - recommendation summaries
  - total monthly and annual savings sections
- Started writing automated unit tests for:
  - savings calculations
  - recommendation engine rules
  - edge-case audit scenarios
- Refactored some audit logic into separate utility files to improve maintainability and testing.
- Continued improving repository organization and commit discipline throughout development.

**What I learned:**  
- Persisting form state significantly improves user experience, especially for longer multi-input workflows.  
- Separating audit calculations from UI rendering makes testing and debugging much easier.  
- Even relatively simple recommendation systems require careful handling of edge cases to avoid unrealistic savings suggestions.

**Blockers / what I'm stuck on:**  
- Need to improve the consistency of recommendation logic across different pricing models, especially API-based billing versus seat-based subscriptions.  
- Still deciding how detailed the audit explanations should be without overwhelming users with too much financial information.

**Plan for tomorrow:**  
- Connect pricing datasets directly into the audit engine calculations.  
- Improve the audit results UI with clearer recommendation explanations and better visual hierarchy.  
- Implement lead capture flow and backend storage setup.  
- Continue expanding automated test coverage for the audit engine.