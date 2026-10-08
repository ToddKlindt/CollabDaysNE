# Prompt to create AI Use Cases library:
Create a new SharePoint List named **AI Use Cases**.

Use the list to track AI initiatives across a fictional mid-sized organization.

Create these columns:

* **Use Case** — Single line of text
* **Department** — Choice: HR, Finance, Sales, IT, Legal, Marketing, Operations
* **Owner** — Single line of text
* **Status** — Choice: Idea, Pilot, Production, Paused
* **AI Tool** — Choice: Copilot Chat, SharePoint Agent, SharePoint Skill, Copilot Studio, Cowork
* **Business Value** — Choice: Low, Medium, High
* **Risk Level** — Choice: Low, Medium, High
* **Users** — Number
* **Hours Saved Per Month** — Number
* **Monthly Cost** — Currency
* **Annual Value Estimate** — Currency
* **Satisfaction** — Number, using values between 1.0 and 5.0
* **Last Reviewed** — Date

After creating the list, populate it with **30 realistic demo records**.

Make the demo data varied and useful for dashboarding:

* Include records from every department.
* Include a mix of Idea, Pilot, Production, and Paused projects.
* Include examples using every AI Tool.
* Most projects should have Low or Medium risk, but include several High-risk projects.
* Include a mix of Low, Medium, and High business value.
* Make Production projects generally have more users and more hours saved than Idea or Pilot projects.
* Include a few projects with high monthly cost but relatively low hours saved so they can be identified as poor-value projects.
* Include several clear success stories with high business value, low or medium risk, strong satisfaction scores, significant hours saved, and strong Annual Value Estimate.
* Include at least one high-risk, high-value project that would deserve executive attention.
* Make the Annual Value Estimate broadly consistent with the project's scale, users, hours saved, and business value.
* Include some projects where Annual Value Estimate is much higher than annualized cost so they stand out as strong investments.
* Include a few projects where annualized cost is relatively high compared with Annual Value Estimate so they stand out as weak investments.
* Include realistic project names such as employee onboarding assistants, contract review, sales proposal generation, document classification, service desk automation, marketing content creation, financial reporting, and knowledge management.
* Use fictional employee names for owners.
* Use Last Reviewed dates spread across the last 90 days.

The data should look realistic enough for an executive AI portfolio dashboard, but it is entirely fictional demo data.

When finished, show me the completed list.


# Create the HTML Dashboard
Create a polished, interactive HTML dashboard based on the **AI Use Cases** SharePoint List.

The dashboard should be designed for executives who want a quick view of the health, value, cost, risk, and adoption of the organization's AI initiatives.

Use the live data from the **AI Use Cases** list.

Include these KPI cards across the top:

* Total AI Use Cases
* Production Use Cases
* Total Users
* Total Hours Saved Per Month
* Total Monthly Cost
* Total Annual Value Estimate

Create visualizations that help answer these questions:

* How are AI initiatives distributed by **Status**?
* Which **Departments** are getting the most value from AI?
* Which **AI Tools** are being used most often?
* Which departments are saving the most hours per month?
* Which projects have the highest Annual Value Estimate?
* Which projects appear to have poor value relative to their cost?
* Where are the High-risk initiatives?

Include:

* A chart showing Use Cases by Status
* A chart showing Hours Saved Per Month by Department
* A chart showing Annual Value Estimate by Department
* A chart showing adoption by AI Tool
* A table of the top 5 projects by Annual Value Estimate
* A section highlighting High-risk projects
* A section highlighting projects that may be poor investments because their annualized cost is high compared with their Annual Value Estimate

Add interactive filters for:

* Department
* Status
* AI Tool
* Business Value
* Risk Level

When filters are changed, update the KPI cards, charts, and tables to reflect the filtered data.

Use a clean, modern Microsoft 365 / SharePoint-inspired design. Make it visually polished enough to show to executives.

Use cards, charts, clear spacing, and subtle visual emphasis. Make high-risk items easy to spot without making the dashboard look alarming.

Include useful tooltips or labels where appropriate.

Make the dashboard responsive so it works well at different browser sizes.

The dashboard must remain connected to the **AI Use Cases** SharePoint List so that changes to the list data are reflected in the dashboard.

Do not create static sample data or copy the data into the HTML. Use the SharePoint List as the live data source.

When finished, show me the completed dashboard.


# Add more items to the list
Create 5 more random records in the AI Use Cases list.

# Add another visualization to the dashboard
Add a visualization to the HTML dashboard comparing annualized cost to Annual Value Estimate for each department so I can quickly identify departments that may not be getting good ROI.

# Add a bad project to the list
Add one absurdly bad project in the list—something with high cost, low value, low satisfaction, and high risk

# Ask about it
Which initiative should leadership question first?