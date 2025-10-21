# Consultant 360 — Project Profitability & Utilization Dashboard

### 🎯 Overview
Consultant 360 is a Power BI project that simulates a consulting firm's operations—tracking billable utilization, project profitability, and client portfolio health using a synthetic dataset.

### 📂 Files
| File | Description |
|------|--------------|
| `Consultant360.pbix` | Power BI report |
| `data/` | Synthetic CSV datasets |
| `theme/Consultant360_Modern_Theme.json` | Custom dark theme |
| `screenshots/` | Preview images |
| `README.md` | Documentation |

### 🧠 Key Insights
- Billable utilization trends across practices and roles  
- Gross Margin vs Target Margin comparison per project  
- T&M vs Fixed-Fee profitability  
- What-if analysis for rate uplift and expense reduction  

### 💡 Tech Stack
Power BI Desktop (June 2025) | DAX | Star Schema Modeling | Data Visualization Design

### 🎨 Theme
The project uses a custom **dark theme** with teal, blue, and green accents for a modern look.  
You can import it via **View → Themes → Browse for themes → Consultant360_Modern_Theme.json**.

### 🖼️ Screenshots
📸 Download screenshots.zip to see all dashboard previews.
| Page | Preview |
|------|----------|
| Executive Overview | ![Executive Overview](screenshots/ExecutiveOverview.png) |
| Project Profitability | ![Project Profitability](screenshots/ProjectProfitability.png) |
| Resource Utilization | ![Resource Utilization](screenshots/ResourceUtilization.png) |
| Project Details | ![Project Details](screenshots/ProjectDetails.png) |

### 🧩 Data Model
Star schema with 3 facts (fact_timesheets, fact_expenses, fact_plan_hours) and 3 dimensions (dim_consultant, dim_project, dim_client).

### 🚀 How to Run
1. Clone this repo or download as ZIP  
2. Open `Consultant360.pbix` in Power BI Desktop (June 2025)  
3. If prompted, update dataset paths → **data/** folder  
4. Apply theme → **View → Themes → Consultant360_Modern_Theme.json**  
5. Explore the report!

### 📄 License
MIT License — free for personal and educational use.

---
*Created by [Meenakshi Rajeev Nair]([https://www.linkedin.com/in/meenakshi-rajeev-nair-43301b248/])*  
