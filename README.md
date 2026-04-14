**Project 1 overview**

This project analyzes global tuberculosis (TB) data across multiple countries from 1990 to 2013 using SQL. The dataset captures key health indicators such as TB prevalence, mortality, HIV-related TB cases, and population estimates.

The goal of this project is to uncover trends, regional disparities, and health risk factors influencing TB outcomes worldwide.

**Key Variables**

Country_Name – Name of the country
Region – WHO region classification (AFR, EUR, SEA, etc.)
Year – Time period (1990–2013)
Estimated_population – Population size
Prevalence_per1000 – TB prevalence rate
Estimated_mortality – Estimated mortality rate
TB_Deaths – Total TB-related deaths
Hiv_Tb – TB cases associated with HIV
prevalence_low / prevalence_high – Confidence intervals


 1. **Global TB Trend Over Time**
    
TB prevalence generally declines from 1990 to 2013 in most countries
Indicates improvement in global health interventions
<img width="731" height="334" alt="Screenshot 2026-03-23 105046" src="https://github.com/user-attachments/assets/b8276d41-aca4-4a98-acd5-a2c32de0be0f" />

 2. **Countries with Highest TB Burden**
    
Some countries consistently show extremely high TB prevalence
These are priority regions for intervention
<img width="823" height="327" alt="Screenshot 2026-03-23 113446" src="https://github.com/user-attachments/assets/129a42c3-805b-4f26-882d-08e4ac43330f" />

3. **Regional TB Distribution**
   
   AFR (Africa) region has the highest TB prevalence
   EUR (Europe) shows the lowest burden
   <img width="857" height="329" alt="Screenshot 2026-03-23 121600" src="https://github.com/user-attachments/assets/98eeb18e-39ab-4dc3-8239-407d4406e466" />
   
4. **HIV and TB Relationship**
 
      Countries with high HIV-TB cases also show high TB deaths
      Confirms HIV as a major driver of TB severity
      <img width="932" height="331" alt="Screenshot 2026-03-23 123157" src="https://github.com/user-attachments/assets/8c7fe597-f2b3-4abd-a1cf-2c25b7c8708f" />
      
5. **Countries with Highest TB Mortality**
   

High mortality indicates:

         Poor healthcare access
         Late diagnosis
         Weak treatment systems
<img width="909" height="350" alt="Screenshot 2026-03-23 124422" src="https://github.com/user-attachments/assets/6afa6087-8112-4c67-9b63-d2b873a2254a" />


6. **Population vs TB Deaths**
   
   Countries with large populations (e.g., Bangladesh) have high total TB deaths
   Absolute numbers can be misleading → need per capita analysis
   <img width="911" height="330" alt="Screenshot 2026-03-23 125935" src="https://github.com/user-attachments/assets/60e607f0-546a-44ac-9b7c-082594f30661" />

7. **Most Improved Countries (Declining TB)**

   Some countries show consistent reduction in TB prevalence
   Reflects strong healthcare systems
   <img width="939" height="357" alt="Screenshot 2026-03-23 141242" src="https://github.com/user-attachments/assets/ab02f221-5948-48a8-8d86-0b075e30d0ae" />

8. **Yearly TB Death Trend**
   
   Helps identify whether global mortality is improving or worsening
   <img width="821" height="337" alt="Screenshot 2026-03-23 141925" src="https://github.com/user-attachments/assets/b342c938-cf43-4e8b-bb4a-b9b1aed9864a" />





**Key Findings Summary**
   
.TB prevalence is declining globally, but unevenly

.Africa remains the highest burden region

.Strong HIV–TB correlation exists

.Population size influences absolute TB deaths

.Some countries show significant improvement, others are worsening








**Project 2 overview(Finance)**

This project presents a comprehensive financial data analysis using SQL, based on a global sales dataset. The objective is to uncover key business insights related to revenue, profitability, product performance, and customer segments.

The dataset includes transactional data across multiple countries, products, and market segments, allowing for in-depth analysis of sales trends, discount impacts, and profit margins.

Through structured SQL queries, this project demonstrates data cleaning, transformation, and analytical techniques to answer critical business questions and support data-driven decision-making.


Main Table: financial sample

Key Fields:

Segment (Government, Midmarket, Enterprise, etc.)
Country
Product
Discount Band (None, Low, Medium)
Units Sold
Sales, COGS, Profit
Date (Month, Year)

Key Business Insights:

**1. Revenue vs Profit Insight**
   
High Sales ≠ High Profit

Some records show high revenue but low margins

Discounts significantly reduce profitability

<img width="911" height="259" alt="Screenshot 2026-03-30 105831" src="https://github.com/user-attachments/assets/9dfe40f6-38ef-4080-a679-dc7f7f81566d" />

Insight:

The business generates strong revenue but profit margins vary due to pricing and discounts.


**2. Top Performing Countries**
   
   <img width="862" height="382" alt="Screenshot 2026-03-30 110824" src="https://github.com/user-attachments/assets/abc3fa5c-11fe-48d9-96c8-f3e02136a378" />
   
  Insight:

Countries like USA, Canada, Germany dominate sales

Some countries have high sales but lower profitability


**3.  Segment Performance**
   
<img width="857" height="361" alt="Screenshot 2026-03-30 111749" src="https://github.com/user-attachments/assets/4038197d-4256-4637-bd0d-bc408ac93906" />

Insight:

Government segment generates highest revenue

Small Business often yields strong profit margins


**4. Impact of Discounts**
   
 <img width="862" height="363" alt="Screenshot 2026-03-30 113828" src="https://github.com/user-attachments/assets/6c48275b-d3c6-42fd-8863-a3eb1ef2db07" />


   
Insight:


Low discounts = higher sales volume

BUT excessive discounts → reduced profit margins



**5.Best Performing Combination**

<img width="918" height="362" alt="Screenshot 2026-03-30 114352" src="https://github.com/user-attachments/assets/9cdc8ce5-108d-4cfb-bbe1-f776ff6216b1" />

 
 
 Summary

The business generates strong global revenue but profitability is inconsistent

Government and Enterprise segments dominate sales volume

Discounts significantly impact profit margins

Certain products (like Paseo & VTT) are high performers

Some transactions operate at a loss → pricing strategy issue

Sales peak toward the end of the year (seasonality effect)

Profitability varies heavily by country and segment

**Business Recommendations**

Reduce heavy discounting strategies

Focus on high-margin products

Optimize pricing for Enterprise segment

Target high-performing countries

Investigate loss-making transactions




**Project 3 overview(nike)**



**Dataset Overview**

The dataset contains sales transactions for Nike products with fields like:

Date

Region

State

City

Product Category (Footwear, Apparel)

Price,

Units Sold

Total Sales

Operating Profit

Operating Margin



**Top-Selling Products by Region**


<img width="839" height="381" alt="Screenshot 2026-04-09 145740" src="https://github.com/user-attachments/assets/c87986cd-0f9a-41e1-8c31-1f4b2abecf41" />

**Insight:**

Footwear dominates sales across all regions.

Men’s Street Footwear is consistently a top-seller.

**Monthly Sales Trend**


<img width="926" height="367" alt="Screenshot 2026-04-09 150553" src="https://github.com/user-attachments/assets/2a387b2f-cd8d-4f77-beba-59b8832391a8" />


**Insight:**

Shows seasonal peaks in summer months (June–August).

Useful for inventory planning and marketing campaigns.


**Profitability by Product**

<img width="919" height="367" alt="Screenshot 2026-04-09 152454" src="https://github.com/user-attachments/assets/439ca811-341f-4aad-9b10-0ff0b3baec8a" />

**Insight:**

Men’s Footwear has highest total profit.

Apparel has lower margins but high consistency.


**Regional Comparison of Sales and Margin**


**Insight:**

Northeast leads in total sales.

South and West have higher average operating margins—potential for expansion.

<img width="915" height="357" alt="Screenshot 2026-04-09 154619" src="https://github.com/user-attachments/assets/732d0818-b740-4d97-8de5-b2da3c621245" />

**Units Sold vs. Price per Unit**

**Insight:**

Products with lower price per unit sell more units (e.g., Women’s Street Footwear).

Helps design pricing strategy.

**Key Portfolio Insights**

Cleaned and structured sales dataset ready for analysis.

Shows top products, regions, and months for Nike.

Identifies profit leaders vs. volume leaders.

Demonstrates SQL skills: cleaning, aggregation, date handling, ranking, and business insight extraction.

Can feed Tableau dashboards for interactive visualization (trend, top-N, regional comparison).





**Project 3 overview(store)**

**Dataset Overview**

This dataset contains transactional retail data including:

Sales, Profit, Discount

Customer segments

Product categories & sub-categories

Shipping modes

Geographic data (Region, State, City)

Order & shipping dates

**Data Cleaning**

Fix column name issue (BOM issue)

<img width="495" height="102" alt="Screenshot 2026-04-13 152950" src="https://github.com/user-attachments/assets/581f995a-9531-4c14-b64b-c5943fae3b01" />

**Key Business Insights**

**Overall Performance**

<img width="873" height="339" alt="Screenshot 2026-04-13 154921" src="https://github.com/user-attachments/assets/82d45a00-0112-45a5-a94b-10a631b38f02" />

**Insight:**

High sales but profit is inconsistent

Discounts are impacting margins


**Profitability by Product Category**

**Insight:**

Technology → highest profit driver

Furniture → often high sales but low or negative profit

<img width="912" height="318" alt="Screenshot 2026-04-13 160702" src="https://github.com/user-attachments/assets/7d16c2b9-16f5-4923-8570-edbd9cebbe0b" />

**Loss-Making Transactions**


<img width="856" height="345" alt="Screenshot 2026-04-14 145130" src="https://github.com/user-attachments/assets/ca658e10-a192-4a0f-aa06-4580390e14f2" />

**Insight:**

Dataset clearly shows frequent negative profits

Suggests:

Over-discounting

High shipping costs

Poor pricing strategy


**Discount Impact on Profit**


<img width="856" height="334" alt="Screenshot 2026-04-14 151110" src="https://github.com/user-attachments/assets/b5bbbe5b-fed4-460a-8e1d-54f90020ef47" />

**Insight:**

Higher discounts → lower or negative profit

Strong case for:

 Discount optimization strategy

 **Category Performance**

 <img width="863" height="337" alt="Screenshot 2026-04-14 152208" src="https://github.com/user-attachments/assets/43dfa46c-c3cb-4120-bc08-faa7e9815176" />

**Insight:**
Technology → high profit generator

Furniture → often low/negative profit (seen in sample rows)


**Sub-Category Risk Analysis**


<img width="915" height="359" alt="Screenshot 2026-04-14 153413" src="https://github.com/user-attachments/assets/a5250dc7-53f7-4fd0-9d73-ff0a0b5077c6" />


Insight:

Some sub-categories consistently lose money,
   These are business risk areas




 **General Key Business Insights**
 
 ✔ Discounts are the biggest driver of losses
 
✔ Some products consistently generate negative profit

✔ Furniture category needs pricing review

✔ Corporate customers generate highest value

✔ Shipping cost significantly impacts margins

✔ Regional inefficiencies exist (sales ≠ profit)




















































   

 
          

         



   


   


         



      
      
      




