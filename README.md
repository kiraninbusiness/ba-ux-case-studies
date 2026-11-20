# BA and UI/UX case studies

Case studies by **Kiran Mamadapur**, Business Analyst and UI/UX Designer. Each folder holds the requirements documents, process flows, wireframes, backlog, traceability matrix and UAT scenarios for one concept project. My real product, THE OFF GRID, has its own repository.

Portfolio: https://kiraninbusiness.github.io/portfolio/

| Case study | Type | Domain | Tools |
|---|---|---|---|
| [UrbanThread](urbanthread/) | Concept project | Fashion e-commerce | Figma, Jira, Excel |
| [MediCare Plus](medicare/) | Concept project | Healthcare appointment management | Figma, BPMN, Power BI |
| [NovaBank](novabank/) | Concept project | Mobile banking | Figma, SQL, Excel |
| [TalentBridge](talentbridge/) | Concept project | Recruitment management | Figma, Jira, Power BI |
| [QuickBite](quickbite/) | Concept project | Food delivery service design | Figma, BPMN, Power BI |

## Please read

- All five are **concept projects** with fictional clients and simulated data. KPI baselines and targets are assumptions, and no UAT has been run.
- Wireframes and high-fidelity screens are schematic drawings, not final screenshots.

## Try the prototypes

Each project has a working app in `<project>/prototype/`. It runs in the browser with no build step and no network calls, and keeps its data in your browser's local storage.

| Project | What you can do |
|---|---|
| [UrbanThread](urbanthread/prototype/) | Search and filter products, wishlist, guest checkout, order tracking |
| [MediCare Plus](medicare/prototype/) | Book, reschedule and check in as a patient; shared calendar for staff; doctor day list |
| [NovaBank](novabank/prototype/) | Add a beneficiary with a one-time code, transfer within limits, search transactions (demo PIN 2468) |
| [TalentBridge](talentbridge/prototype/) | Pipeline board, shortlist and weekly report by role, interview scheduling |
| [QuickBite](quickbite/prototype/) | Customer, restaurant, rider and manager views; open two tabs to see them sync |

To run them online, open the repo Settings, then Pages, choose the `main` branch and the root folder, and save. To run locally, open any `prototype/index.html` in a browser.

**Tests:** each prototype keeps its business rules in `logic.js` with tests in `logic.test.js`. Run `node --test` inside a prototype folder (Node 18 or later). GitHub runs all five on every push (`.github/workflows/ci.yml`). Each prototype's README maps its requirements to code and tests, and says plainly what is real and what is simulated.

## What each folder contains

`README.md` overview, personas and journey · `docs/` BRD summary, FRD, user stories with acceptance criteria, process flow, Jira-style backlog, RTM, UAT scenarios, KPIs · `assets/` cover, BPMN-style diagram, sitemap, wireframes and high-fidelity screens.
