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