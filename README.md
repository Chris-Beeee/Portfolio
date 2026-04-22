# Portfolio
Brief portfolio with links v1.0. I have automation examples marked as private. when they are ready I will publish them here. 

### About me :wave:


[My Linkedin profile](https://www.linkedin.com/in/chris-blenkarn-a25319179/)

### My experience 

### Tools 
* [Azure DevOps](https://azure.microsoft.com/en-us/products/devops) - Defet Mangement, Kanban and piplelines for CI
* [Jira](https://www.atlassian.com/pl/software/jira)  - Defect management and Kanban
* [Microsoft Teams](https://www.microsoft.com/en-gb/microsoft-teams/group-chat-software) - Team collaboration and planning 
* [Slack](https://slack.com/) - Team collaboration and planning
* [SSMS](https://learn.microsoft.com/en-us/sql/ssms/) - Our main client-facing DB
* [Toad for Oracle](https://www.quest.com/toad) - Our primary DB for business apps
* [Powershell](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/powershell) - Scripting for environnment management
* [Chrome Devtools](https://developer.chrome.com/docs/devtools/) - 
* [Postman](https://www.postman.com/) - API testing
* [SOAP UI](https://www.soapui.org/) - API testing
* [Pycharm](https://www.jetbrains.com/pycharm/) - IDE for Python
* [Antigravity](https://antigravity.google/) - IDE for generating code using Gemini, Claude and GPT
* [Selenium](https://www.selenium.dev/)
* [Kibana](https://www.elastic.co/kibana)


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
* Python and C# for web fonr-end test automation
* Selenium for Python and C#
* Pytest for Python
* HTML and CSS
* Creating documentation (test plans, test scripts, test cases, defect statistics)
* Testing SaaS applications (websites, APIs, complex multi-step workflows)
* Facilitating UAT sessions
* Different software development models scrum, waterfall, v model, iterative and incremental model, agile) 

### Projects
* Large-scale transformational project to move media content management from a Windows Form connected to an on-prem Oracle instance to an Azure cloud environment to allow outsourcing and machine learning
  Key deliverables
  - Business priorities: Migrating 2,000 existing clients (80% of customer base for this service) over several waves Copyright licencing, replication of content ordering and summaries, resilience, performance, services to bridge between the Oracle and Azure instances for media            content (both into and back out of Azure) and client metadata, which must remain in synch. Full regression of remaining legacy systems. Daily UAT sessions with 4 business users. Full functionality, regression and UAT test plans and test scripts. 
  -Timescale: I joined the project relatively late, and due to redundancy notices having already been issued clients needed to begin migration in around 2 months with no possibility of delay.
  -Example defect: I noticed that the software vendor's work asssignment roster included a major flaw relating to a misunderstaood requirement. If a client did not get a delivery each day (which many of the smaller clients did not) then any media content that arrived after that point    would be stuck assigned to a worker in the past, who may or may not be currently working. After some discussion a new stored procedure was written which would move all undelivered content to the next available shift. This issue was discovered several weeks before launch, avoiding     a high-severity defect on launch with live clients. 

### Certificates 
* ISTQB Foundation Level
* ISTQB Advanced Level Test Automation Engineer

