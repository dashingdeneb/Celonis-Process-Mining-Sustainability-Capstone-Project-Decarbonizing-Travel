**README:** **Sustainability** **Capstone** **-** **Decarbonizing**
**Travel**

This document serves as a guide for navigating the Sustainability
Capstone project. It

outlines the step-by-step workflow required to complete the analysis and
provides a

manifest of all included files.

**Project** **Workflow:** **Step-by-Step**

To complete this capstone, follow these phases:

**Phase** **1:** **Environment** **Setup** **&** **Data** **Prep**

> 1\. Create an academic team a[t
> **signup.celonis.com**](https://signup.celonis.com)
>
> 2\. Register for free with the academic email address (please avoid
> gmail or personal
>
> accounts)
>
> 3\. Open the invitation e-mail and complete the registration
> as**STUDENT**
>
> 4\. Access your academic account

**Phase** **2:** **Data** **Modeling**

> 1\. Data Pool Integration: Upload the CSV files into a Celonis Data
> Pool.
>
> 2\. Create Relationships: Link the tables to allow for granular
> filtering. The TripID is the
>
> common key across the travel data, event log, and attributes.
>
> ○ *Minimum* *Requirement:* Ensure the CarbonEmission_kgCO2e field is
>
> correctly mapped.

**Phase** **3:** **Process** **Analysis** **&** **Dashboarding**

> ❖ Process Discovery: Build a Process Explorer and Variant Explorer
> using the
>
> public_trip_event_log.csv. Identify bottlenecks or "out-of-policy"
> behaviors.
>
> ❖ Build Views: Create at least three distinct dashboard tabs focusing
> on:
>
> ○ Emissions Overview: High-level KPIs (Total CO2, Costs).
>
> ○ Benchmarking: Emissions by Region or Business Unit.
>
> ○ Emission Drilldown: With actionable Insights: Identifying specific
> metrics
>
> (e.g., Flight vs. Train).

**Phase** **4:** **Final** **Pitch**

> 1\. Synthesize Findings: Identify "Hotspots" (high-emission areas) and
> "Quick Wins."
>
> 2\. Develop Recommendations: Propose specific policy updates (e.g.,
> "All trips under X km
>
> must be by train").
>
> 3\. Present: Deliver a consultant-style pitch including a live demo of
> your Celonis
>
> environment.

**File** **Manifest** **&** **Descriptions**

**Core** **Datasets** **(CSV)**

> ● public_trip_data..csv: The master data table. Contains trip details
> (locations,
>
> transport type, costs) and pre-calculated carbon emissions. Use this
> for the
>
> standard project path.
>
> ● public_trip_event_log.csv: The activity table. Contains timestamps
> for every step
>
> of a trip (Booking -\> Approval -\> Departure -\> Reimbursement).
> Essential for the
>
> Process Explorer.
>
> ● public_trip_event_attributes..csv: Contextual data. Provides
> specific reasons for
>
> policy exceptions, flight cancellations, or hotel changes. Use this to
> enrich your
>
> analysis of *why* certain process variants occur.

**Documentation**

> ● Sustainability Capstone Outline: Decarbonizing Travel Provides the
> business case,
>
> the "Net Zero by 2030" goal, and the evaluation criteria for your
> final presentation.
>
> ● \<FullName\>\_Project Use this template to submit your presentation.

**LearningMaterials**

> Recommendations from the Celonis Academy:
>
> [<u>Introduction to Process
> Mining</u>](https://academy.celonis.com/courses/introduction-to-process-mining)
>
> [<u>Process Mining
> Fundamentals</u>](https://academy.celonis.com/learning-paths/process-mining-fundamentals-for-students)
>
> [<u>Rising Stars Business and Technical
> Tracks</u>](https://academy.celonis.com/courses/the-celonis-rising-stars-program)
>
> [<u>Sustainability
> Bootcamp</u>](https://academy.celonis.com/courses/sustainability-business-bootcamp) -
> to learn about sustainability and our current solutions

Collaboration Examples:

> [<u>Climatiq x Celonis
> collaborations</u>](https://www.climatiq.io/customers/celonis)

Celonis AI Foundations

> [<u>Configure Process
> Copilots</u>](https://academy.celonis.com/courses/configure-process-copilot)
>
> [<u>Accelerate Process Analysis with Insight
> Explorer</u>](https://academy.celonis.com/courses/accelerate-process-analysis-with-insight-explorer)
>
> [<u>Maximize Data Value with AI Annotation
> Builder</u>](https://academy.celonis.com/courses/ai-annotation-builder)
