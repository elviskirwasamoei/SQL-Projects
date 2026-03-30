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

1. Revenue vs Profit Insight
   
High Sales ≠ High Profit

Some records show high revenue but low margins

Discounts significantly reduce profitability

<img width="911" height="259" alt="Screenshot 2026-03-30 105831" src="https://github.com/user-attachments/assets/9dfe40f6-38ef-4080-a679-dc7f7f81566d" />

Insight:

The business generates strong revenue but profit margins vary due to pricing and discounts.


2. Top Performing Countries
   
   <img width="862" height="382" alt="Screenshot 2026-03-30 110824" src="https://github.com/user-attachments/assets/abc3fa5c-11fe-48d9-96c8-f3e02136a378" />
   
  Insight:

Countries like USA, Canada, Germany dominate sales

Some countries have high sales but lower profitability


3.  Segment Performance
   
<img width="857" height="361" alt="Screenshot 2026-03-30 111749" src="https://github.com/user-attachments/assets/4038197d-4256-4637-bd0d-bc408ac93906" />

Insight:

Government segment generates highest revenue

Small Business often yields strong profit margins


















   

 
          

         



   


   


         



      
      
      




