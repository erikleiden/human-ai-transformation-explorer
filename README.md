# Human + AI Transformation Explorer

An interactive prototype that helps workers and leaders understand how AI transforms workforce skills — built on the **Skills-First Workforce Initiative** skill taxonomy from [skills-first.org](https://www.skills-first.org).

## 🔗 Live Demo

Open `index.html` directly in any browser — no server or dependencies needed.

## What It Does

Walk through a four-step flow:

1. **Select a Job Category** — Technology & Knowledge Work, Operations & Logistics, Retail & Customer Service, or Business & Management
2. **Choose an AI Use Case** — e.g. AI Co-Pilot, Predictive Analytics, Intelligent Process Automation, AI-Powered Customer Interaction, AI Monitoring & Safety, or AI-Assisted Development
3. **Pick a Specific Role** — All 30 roles from the Skills-First Workforce Initiative
4. **See the Skill Transformation** — A side-by-side view of:
   - Current skills grouped by category (Foundational & Leadership, Baseline Applied, Core Role-Specific, Specializations)
   - Skills that are **declining** due to AI (highlighted at the bottom of the current profile)
   - **New AI skills** added to the role by the selected use case (shown clearly in the transformed profile)

## Data Sources

- **Skill taxonomy & labels** (Durable, High Growth, High Value, Declining) sourced from the [Skills-First Workforce Initiative CSV](https://www.skills-first.org), covering 30 roles and 35M+ U.S. workers
- **AI use case overlays** are research-informed additions representing emerging skill demands per role × AI adoption scenario
- **AI Fluency Framework** domains from the skills-first.org × Grow with Google collaboration

## Roles Covered (30 total)

| Category | Roles |
|---|---|
| Technology & Knowledge Work | Software Developers, Data Scientists, Cybersecurity Analysts, Product Managers |
| Operations & Logistics | Transportation/Storage/Distribution Managers, Truck Drivers, Stockers & Order Fillers, Shipping & Receiving Clerks, Laborers & Material Movers, Industrial Machinery Mechanics, Inspectors/Testers/Samplers, Assemblers & Fabricators, Packers & Packagers, Maintenance & Repair Workers, Transportation Supervisors |
| Retail & Customer Service | Customer Service Representatives, Customer Service Managers, Retail Salespersons, First-Line Supervisors of Retail Sales Workers, Cashiers, Receptionists & Information Clerks, Security Guards |
| Business & Management | Financial Analysts, Financial Managers, HR Specialists, Project Management Specialists, Sales Managers, Sales Representatives, Purchasing Agents, Production & Expediting Clerks |

## AI Use Cases

| Use Case | Categories |
|---|---|
| 🤖 AI Co-Pilot for Daily Work | Tech, Business, Retail |
| 📈 Predictive Analytics & Decision Intelligence | Tech, Business, Operations |
| ⚙️ Intelligent Process Automation | Operations, Retail, Business |
| 💬 AI-Powered Customer Interaction | Retail, Business |
| 🔍 AI-Augmented Monitoring & Safety | Operations, Retail |
| 🧑‍💻 AI-Assisted Development & Engineering | Technology |

## Tech Stack

Single-file HTML/CSS/JS — zero dependencies, zero build step.

---

Built as a prototype for workforce transformation planning. Data from the [Burning Glass Institute](https://www.burningglassinstitute.org) / Skills-First Workforce Initiative.
