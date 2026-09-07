Marketing Investment Optimizer | Power BI

A Power BI decision-support solution designed to help marketing leaders identify efficient markets, evaluate marketing spend performance, and simulate budget reallocations before moving investment.

The business problem I wanted to solve was not simply understanding marketing performance, but helping a marketing manager answer a more practical question:

Where should we invest the next marketing dollar?

On the first page, I created the Executive Dashboard.

It provides an overview of total revenue, bookings, marketing spend, blended CPA, blended ROAS and the Efficiency Index.

Managers can also filter the dashboard by marketing channel and market and analyse how ROAS changes over time.

But overall performance doesn't necessarily tell us where investment should move.

That's why I created the second page, the Market Scorecard.

Here I compare each market's revenue, spend, bookings, ROAS, CPA, share of revenue and share of spend.

I also calculate an Efficiency Index, which compares a market's revenue contribution with its share of marketing investment.

This helps identify markets that may be generating disproportionately stronger or weaker returns.

The final page converts those insights into a decision-support tool.

In the Reallocation Simulator, a user selects a market to reduce investment in, another market to increase investment in, and the amount of budget they want to move.

The dashboard then compares the acquisition cost of the two markets and estimates the bookings that could potentially be lost and gained from that reallocation.

So rather than building another reporting dashboard, I designed this project around a complete analytics workflow:

Measure performance, identify opportunities, simulate a decision, and estimate its business impact.

The solution was built using Power BI, Power Query and DAX.

Business Problem

Marketing teams frequently distribute budgets across multiple markets and channels but struggle to determine whether investment is aligned with actual business performance.

Traditional dashboards can show revenue, bookings, spend, CPA and ROAS, but decision-makers still need to answer:

Which markets are generating disproportionately more revenue than their share of spend?

Which markets may be over-invested?

Where could additional marketing budget generate better returns?

What could happen to bookings if budget is moved from one market to another?

The goal of this project was to turn marketing performance data into an actionable investment decision framework.

Solution

I developed a three-page Power BI solution that moves from executive-level monitoring to market diagnosis and finally to budget simulation.

Page 1 — Executive Dashboard

Provides an executive overview of marketing performance through KPIs including:

Total Revenue
Total Bookings
Total Spend
Blended CPA
Blended ROAS
Efficiency Index
Share of Revenue
Share of Spend
Monthly ROAS Trend

Interactive filters allow performance to be analysed by:

Marketing Channel
Country / Market

The objective is to quickly identify whether marketing investment is converting efficiently into revenue and bookings.




Page 2 — Market Scorecard

The Market Scorecard compares investment efficiency across individual markets.

Metrics include:

Revenue
Marketing Spend
Bookings
Blended CPA
Blended ROAS
Share of Spend
Share of Revenue
Efficiency Index
Investment Signal

This page is designed to answer:

Which markets deserve more investment, and which require further investigation or reduced spending?




Page 3 — Budget Reallocation Simulator

The Reallocation Simulator converts analysis into a potential business decision.

Users can:

Select the market where investment could be reduced.
Select the market where investment could be increased.
Enter the amount of budget to shift.
Compare the CPA of both markets.
Estimate Bookings Lost from the reduced market.
Estimate Bookings Gained in the increased market.

This creates a simple what-if scenario before a marketing manager makes an actual budget allocation decision.

Key Business Metrics
Blended ROAS

Blended ROAS = Total Revenue / Total Marketing Spend

Measures how much revenue is generated for every unit of marketing investment.

For example, a ROAS of 5.0x indicates that every $1 invested generated approximately $5 in revenue.

Blended CPA

Blended CPA = Total Marketing Spend / Total Bookings

Shows the average acquisition cost required to generate one booking.

Lower CPA generally indicates greater acquisition efficiency, assuming customer and revenue quality remain comparable.

Share of Spend

Measures the percentage of total marketing investment allocated to each market.

Share of Revenue

Measures the percentage of total revenue contributed by each market.

Efficiency Index

Efficiency Index = Share of Revenue / Share of Spend

The metric helps determine whether a market's revenue contribution is proportionate to its investment allocation.

Efficiency Index > 1

The market generates a greater share of revenue than its share of marketing spend.

Efficiency Index < 1

The market consumes a greater share of spend than its corresponding revenue contribution.

The metric should be analysed alongside ROAS, CPA, booking volume and business constraints rather than being used independently.
Decision Framework

The dashboard combines multiple metrics rather than relying on a single KPI.

A market showing:

High Efficiency Index + Strong ROAS + Competitive CPA

may represent a candidate for increased investment.

A market showing:

Low Efficiency Index + Weak ROAS + High CPA

may require optimisation, further investigation, or potentially reduced investment.

The Reallocation Simulator can then be used to estimate the possible impact of transferring budget between those markets.

Business Recommendations

The analysis supports four practical recommendations:

1. Prioritise efficiency, not just revenue

A high-revenue market is not automatically the best investment opportunity. Revenue should be evaluated relative to the amount of marketing spend required to generate it.

2. Compare Revenue Share with Spend Share

Markets producing a higher share of revenue than their share of investment may deserve deeper investigation for potential scaling.

3. Use CPA when evaluating budget transfers

Budget should not simply be transferred from the lowest-ROAS market to the highest-ROAS market. Acquisition efficiency, booking volume and market capacity should also be considered.

4. Simulate before reallocating

The reallocation model provides an estimated impact before changing the actual marketing budget, reducing the risk of making allocation decisions based purely on intuition.

DAX / Analytical Measures

The project includes measures covering:

Total Revenue
Total Spend
Total Bookings
Blended ROAS
Blended CPA
Share of Revenue
Share of Spend
Efficiency Index
Investment Signal
CPA of Reduce Market
CPA of Increase Market
Amount to Shift
Bookings Lost
Bookings Gained

These measures convert raw marketing performance data into metrics that can support investment decisions.

Tools Used

Power BI Desktop

Dashboard development,

visualisation and interactive analysis.

DAX
KPI calculations, 
context-aware measures
and reallocation scenario calculations.

Power Query

Data preparation and transformation.

Excel

Data Cleaning, validation.

Skills Demonstrated

Power BI

DAX

Power Query

Data Modelling

Marketing Analytics

Business Intelligence

KPI Development

ROAS Analysis

CPA Analysis

Marketing Investment Analysis

Budget Optimisation

Scenario Analysis

Data Visualisation

Business Problem Solving

Executive Dashboard Design

Data Storytelling

Commercial Decision Support

Business Value

This project demonstrates how analytics can progress beyond descriptive reporting.

Instead of simply showing marketing performance, the solution supports a decision-making workflow:

Data → KPI → Market Comparison → Investment Signal → Budget Scenario → Business Decision

The final objective is to help decision-makers allocate marketing investment more efficiently while understanding the potential effect on customer acquisition and bookings.


