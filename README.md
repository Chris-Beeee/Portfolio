# Portfolio

## About me

* [My Linkedin profile](https://www.linkedin.com/in/chris-blenkarn-a25319179/)

## Automation Examples

### (Work in Progress) Machine learning movie recommendation engine 
* [ReadMe](https://github.com/Chris-Beeee/ML_sandbox/blob/main/README.md) contains changelog of 20+ significant QA issues tackled so far
* [Profile based recommendations](https://github.com/Chris-Beeee/ML_sandbox/blob/main/main_profile.py) using TF-IDF Vectorization and Cosine Similarity
* ['Tinder for movies'](https://github.com/Chris-Beeee/ML_sandbox/blob/main/main_active.py)  - a more experimentalactive learning project with 'Epsilon greedy' mathematical weighting

### (Work in Progress) Basic infrastructure verification using Pytest with Powershell integration
* [ReadMe](https://github.com/Chris-Beeee/infrastructure_sandbox/blob/main/README.md)
* [Verify a folder structure and file contents](https://github.com/Chris-Beeee/infrastructure_sandbox/blob/main/tests/test_folder_structure.py)
* [Verify Windows services and status](https://github.com/Chris-Beeee/infrastructure_sandbox/blob/main/tests/test_services.py)

### (Work in Progress - very early) Performance/Load testing with Locust/Python
* [ReadMe](https://github.com/Chris-Beeee/Locust_load_test/blob/main/README.md)
* [Basic load test using a public test resource](https://github.com/Chris-Beeee/Locust_load_test/blob/main/locustfile.py)

### (Complete) Python script to add bespoke text to application cover letters
* [ReadMe](https://github.com/Chris-Beeee/coverletter/blob/main/README.md)
* [Main method](https://github.com/Chris-Beeee/coverletter/blob/main/main.py)

### Web UI automation with backend API verification

This project is using [themoviedb.org](https://www.themoviedb.org/) as it has a free API available for non-commercial projects. It combines several different elements into one set of test cases
* Front-end web UI interactions
* Scraping for movie data from web UI
* Comparing scraped results with back-end API results, with increasingly complex filter logic applied to both
* A fallback mock API if user does not have API credentials
* Tests can be run either with or without user login credentials. 
* Parameterised tests
* Randomised paramaters
    
#### Selenium / Pytest (IDE: Pycharm)
* [ReadMe](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/README.md)
* [Verifying a single top level menu result](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/tests/test_tmdb_now_playing_pom.py)
* [Verifying multiple top level menu results](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/tests/test_tmdb_categories_pom.py)
* [Filtering on 3 basic metrics](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/tests/test_tmdb_discover_pom.py)
* [Filtering on multiple complex metrics](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/tests/test_tmdb_discover_complex.py)
* [Filtering on randomised metrics](https://github.com/Chris-Beeee/SeleniumUIVerification/blob/main/tests/test_tmdb_discover_random.py)

#### Playwright / Pytest (IDE: Pycharm)
These are the same test cases re-factored to work in Playwright for Python
* [ReadMe](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/README.md)
* [Verifying a single top level menu result](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/tests/test_tmdb_now_playing.py)
* [Verifying multiple top level menu results](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/tests/test_tmdb_categories.py)
* [Filtering on 3 basic metrics](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/tests/test_tmdb_discover.py)
* [Filtering on multiple complex metrics](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/tests/test_tmdb_discover_complex.py)
* [Filtering on randomised metrics](https://github.com/Chris-Beeee/playwright_sandbox/blob/main/tests/test_tmdb_discover_random.py)

#### Typescript / Playwright (IDE: VS Code)
These are the same test cases re-factored to work in Playwright for Typescript
* [ReadMe](https://github.com/Chris-Beeee/Typescript/blob/main/README.md)
* [Verifying a single top level menu result](https://github.com/Chris-Beeee/Typescript/blob/main/tests/tmdbNowPlaying.spec.ts)
* [Verifying multiple top level menu results](https://github.com/Chris-Beeee/Typescript/blob/main/tests/tmdbCategories.spec.ts)
* [Filtering on 3 basic metrics](https://github.com/Chris-Beeee/Typescript/blob/main/tests/tmdbDiscover.spec.ts)
* [Filtering on multiple complex metrics](https://github.com/Chris-Beeee/Typescript/blob/main/tests/tmdbDiscoverComplex.spec.ts)
* [Filtering on randomised metrics](http://github.com/Chris-Beeee/Typescript/blob/main/tests/tmdbDiscoverRandom.spec.ts)

### Test case design: Linear design vs Page Object Model
This project demonstrates re-factoring of linear test cases to the Page Object Model using three complex dynamic websites. 
* [ReadMe](https://github.com/Chris-Beeee/SeleniumTests/blob/master/README.md)
* [GiantBomb (Linear)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_giantbomb_frontpage_linear.py)
* [GiantBomb (Page Object Model)](https://github.com/Chris-Beeee/SeleniumTests/blob/master/tests/test_giantbomb_frontpage_pom.py)

### Mobile app tests using Appium + Pytest
* [ReadMe](https://github.com/Chris-Beeee/Appium/blob/master/README.md)
* [Front end scraping and back-end verification](https://github.com/Chris-Beeee/Appium/blob/master/tests/test_inventory_verification.py)

### API testing using Pytest and requests
* [ReadMe](https://github.com/Chris-Beeee/APITestGeneric/blob/main/README.md)
* [Positive tests](https://github.com/Chris-Beeee/APITestGeneric/blob/main/tests/test_posts_negative.py)
* [Negative tests (failures and expected failures)](https://github.com/Chris-Beeee/APITestGeneric/blob/main/tests/test_posts_positive.py)
 
### My experience 

### Tools 
* [Azure DevOps](https://azure.microsoft.com/en-us/products/devops) - Defect Management, Kanban and pipelines for CI
* [Jira](https://www.atlassian.com/pl/software/jira)  - Defect management and Kanban
* [Microsoft Teams](https://www.microsoft.com/en-gb/microsoft-teams/group-chat-software) - Team collaboration and planning 
* [Slack](https://slack.com/) - Team collaboration and planning
* [SSMS](https://learn.microsoft.com/en-us/sql/ssms/) - Our main client-facing DB
* [Toad for Oracle](https://www.quest.com/toad) - Our primary DB for business apps
* [Powershell](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/powershell) - Scripting for environnment management
* [Telerik Web Debugger (Fiddler)](https://www.telerik.com/fiddler) - Network analysis
* [Chrome Devtools](https://developer.chrome.com/docs/devtools/) - Defect triage
* [Pycharm](https://www.jetbrains.com/pycharm/) - IDE for Python
* [VS Code](https://code.visualstudio.com/download) - IDE for Typescript
* [Antigravity](https://antigravity.google/) - IDE for generating code using Gemini, Claude and GPT
* [Selenium](https://www.selenium.dev/) Webdriver for front end web UI testing. Used with both C# and Python
* [Pytest](https://docs.pytest.org/en/stable/) - Test framework for Python
* [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) - Superset of Javascript
* [Postman](https://www.postman.com/) - API testing
* [SOAP UI](https://www.soapui.org/) - API testing
* [Kibana](https://www.elastic.co/kibana) Logging and monitoring


### Tech skills
* [SQL]()

| syntax and order of execution | comparison operators | logical operators | scalar functions                 | aggregation functions | others
|:-----------------------------:|:--------------------:|:-----------------:|:--------------------------------:|:---------------------:|:-------:|
| SELECT (*, LIKE, TOP)         |          =           | AND               | GETDATE                          | COUNT ()              | JOIN    |
| FROM                          |         !=           |   BETWEEN         | UPPER                            | SUM ()                | AS      |
| WHERE                         |         <>           |    IN             | LOWER                            | MIN ()                |  UNION  |
| GROUP BY                      |          >           |    LIKE           | DATEDIFF (HOUR, MONTH, YEAR etc.)|                       |         |
| ORDER BY (ASC, DESC)          |          <           |    NOT            |                                  |                       |         |
|  UPDATE (SET)                 |         >=           |    OR             |                                  |                       |         |
|    ALTER TABLE (ADD)          |         <=           |    IS NULL        |                                  |                       |         |
|  INSERT INTO                  |         !<           |    IS NOT NULL    |                                  |                       |         |
|                               |         !>           |                   |                                  |                       |         |

* Rest API testing
* SOAP API testing
* Python and C# for web front-end test automation
* Selenium for Python and C#
* Pytest for Python
* HTML and CSS
* Creating documentation (test plans, test scripts, test cases, defect statistics)
* Testing SaaS applications (websites, APIs, complex multi-step workflows)
* Facilitating UAT sessions
* Different software development models (scrum, waterfall, v model, iterative and incremental model, agile) 

### Test environment management
Environment: Around 50 on-prem servers, the vast majority VMs, running different versions of Windows server OS. The primary workflow reuired Microsoft Message Queueing to be operational, which required regular ordered restarts to be operational. I would do this and other minor IT Operations tasks, only escalating to the wider IT team via servicedesk ticket if normal remedies were not working to resolve the issue. 

### Servicedesk defect management
Issues raised by both clients and business users were escalated to me as a point of first contact within the dev team to triage and recommend causes and solutions.
I would then add my analysis onto the development ticket for developers to analyse. and liase with the business stakeholder or client services manager (depending on the source of the ticket)

### Projects
* Large-scale transformational project to move media content management from a Windows Form connected to an on-prem Oracle instance to an Azure cloud environment to allow outsourcing and machine learning
  Key deliverables

Business priorities: Migrating 2,000 existing clients (80% of customer base for this service) over several waves - Copyright licencing - replication of content ordering and summaries - resilience - performance - Internally developed Windows services to bridge between the Oracle and Azure instances for media content (both into and back out of Azure) and client metadata, which must remain in synch - Full regression of remaining legacy systems. Daily UAT sessions with 4 business users. Full functionality, regression and UAT test plans and test scripts.
  
Timescale: I joined the project relatively late, and due to redundancy notices having already been issued clients needed to begin migration in around 2 months with no possibility of delay.

Example defect: I noticed that the software vendor's work asssignment roster included a major flaw relating to a misunderstood requirement. If a client did not get a delivery at each possible opportunity (which many of the smaller clients did not) then any media content that        arrived after that point would be stuck assigned to a worker in the past, who may or may not be currently working. After some discussion a new stored procedure was written which would move all undelivered content to the next available shift. This issue was discovered several weeks   before launch, avoiding a high-severity defect affecting newly migrated live clients. 

### Certificates 
* ISTQB Foundation Level
* ISTQB Advanced Level Test Automation Engineer

