# Chris Blenkarn – QA Automation Portfolio

**Software QA Engineer & Test Manager** with 8+ years leading testing in Agile SaaS environments.

This portfolio demonstrates my recent hands-on focus on strengthening **Python-based automation** after a career break, particularly with Selenium + Pytest, while actively expanding into Playwright and other tools.

- [LinkedIn](https://www.linkedin.com/in/chris-blenkarn-a25319179/)
- Location: London E2 | UK Citizen | Willing to relocate

---

## Highlighted Projects

### Machine Learning Movie Recommender (CLI Experiment)
**Purpose**: Personal experiment applying Software QA practices to Machine Learning development.

- Hybrid offline-first recommendation engine (TF-IDF + Cosine Similarity)
- Profile-based mode + interactive **'Tinder for movies'** active learning with Epsilon-Greedy
- Extensive QA focus: data quality, bias mitigation, edge cases, and regression issues

→ [View Project & Detailed QA Changelog](https://github.com/Chris-Beeee/ML_sandbox/blob/main/README.md)

### Web UI Automation + Backend API Verification (TMDB)
**Core strength**: Comprehensive test suites combining UI interactions, scraping, and live backend API verification with complex filtering logic.  
**Primary tool**: Selenium + Pytest (Python) — my strongest and most mature implementation.

**Implementations**:
- **Selenium + Pytest (Python)** ← *Most complete & recommended*
- Playwright + Pytest (Python) — recent refactoring exercise
- Playwright + TypeScript — early exploration

→ [Selenium Version (Primary)](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/README.md)  
→ [Playwright Python Version](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/README.md)  
→ [Playwright TypeScript](https://github.com/Chris-Beeee/Typescript/blob/main/README.md)

### Other Notable Projects
- **Infrastructure Verification** — Pytest + PowerShell for folder structures and Windows services → [Link](https://github.com/Chris-Beeee/infrastructure_sandbox/blob/main/README.md)
- **Mobile Testing** — Appium + Pytest → [Link](https://github.com/Chris-Beeee/Appium/blob/main/README.md)
- **API Testing** — Pytest + Requests (positive/negative) → [Link](https://github.com/Chris-Beeee/APITestGeneric/blob/main/README.md)
- **Load Testing** — Basic Locust implementation → [Link](https://github.com/Chris-Beeee/Locust_load_test/blob/main/README.md)

<details>
<summary><strong>Archived: Test Case Design (Linear vs Page Object Model)</strong></summary>

This older project demonstrates the refactoring of linear test cases to the Page Object Model using three complex dynamic websites. 
* [ReadMe](https://github.com/Chris-Beeee/SeleniumTests/blob/master/README.md)
* [YouTube (Linear)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_youtube_search_linear.py) | [YouTube (POM)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_youtube_search_pom.py)
* [Amazon (Linear)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_amazon_search_linear.py) | [Amazon (POM)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_amazon_search_pom.py)
* [GiantBomb (Linear)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_giantbomb_frontpage_linear.py) | [GiantBomb (POM)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_giantbomb_frontpage_pom.py)
</details>

<details>
<summary><strong>Archived: Past Professional Project (Cloud Migration)</strong></summary>

**Large-scale transformational project** to move media content management from a Windows Form connected to an on-prem Oracle instance to an Azure cloud environment to allow outsourcing and machine learning.

* **Key Deliverables & Business Priorities:** Migrating 2,000 existing clients (80% of customer base for this service) over several waves - Copyright licencing - replication of content ordering and summaries - resilience - performance - Internally developed Windows services to bridge between the Oracle and Azure instances for media content (both into and back out of Azure) and client metadata, which must remain in synch - Full regression of remaining legacy systems. Daily UAT sessions with 4 business users. Full functionality, regression and UAT test plans and test scripts.
* **Timescale:** I joined the project relatively late, and due to redundancy notices having already been issued, clients needed to begin migration in around 2 months with no possibility of delay.
* **Example Defect:** I noticed that the software vendor's work assignment roster included a major flaw relating to a misunderstood requirement. If a client did not get a delivery at each possible opportunity (which many of the smaller clients did not) then any media content that arrived after that point would be stuck assigned to a worker in the past, who may or may not be currently working. After some discussion a new stored procedure was written which would move all undelivered content to the next available shift. This issue was discovered several weeks before launch, avoiding a high-severity defect affecting newly migrated live clients. 
</details>

---

## Skills Demonstrated
- **Strongest**: Python, Selenium WebDriver, Pytest, Page Object Model, API + UI verification
- **Developing**: Playwright (Python & TypeScript)
- Test design (parameterised, randomised, complex filtering)
- Applying QA rigour to ML systems

---

## Background
Test Manager / QA Engineer in Media & Publishing SaaS (Kantar, Onclusive, Precise Media).  
ISTQB Advanced Test Automation Engineer + Foundation.

---

Feel free to explore the repositories. I'm happy to discuss code, design decisions, trade-offs, or run through any of the test suites live.
