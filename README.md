# phase-one-project
# Aviation Accident Risk Analysis

📌 **Project Overview**
This project analyzes aviation accident data to identify the safest aircraft for investment. The goal is to help a company entering the aviation industry determine 
which aircraft manufacturer presents the lowest risk based on historical accident trends and severity.

💼 **Business Problem**
Your company is expanding into commercial and private aviation but lacks information on potential aircraft risks. The objective is to analyze historical accident data and identify the safest aircraft for investment.

🔍 **Key Questions Addressed**:
Which aircraft makes have the highest and lowest accident rates?
What are the most common causes of accidents?
How do different engine types affect accident frequency and severity?
Does weather impact accident rates for different aircraft?
Which aircraft manufacturer presents the lowest risk?

📊 **Data Overview**
The dataset used for this analysis consists of aviation accident records from 1963 to 2023, obtained from the National Transportation Safety Board (NTSB).

# Key Variables Analyzed:

Event.Id – ID of the accident

Investigation.Type

Make – Aircraft manufacturer

Model – Aircraft model

Injury.Severity – Fatal, serious, minor, or uninjured

Total.Fatal.Injuries – Number of deaths per accident

Total.Serious.Injuries – Number of serious injuries

Total.Minor.Injuries – Number of minor injuries

Total.Uninjured – Number of passengers who survived uninjured

Engine.Type – Single-engine, multi-engine, jet, etc.

Number.of.Engines

Weather.Condition – VMC (Visual Meteorological Conditions) vs. IMC (Instrument Meteorological Conditions)

📈 Analysis Conducted & Key Findings

1️⃣ **Accident Frequency by Aircraft Make**
Top 10 aircraft manufacturers with the highest number of accidents were identified.
Mooney Aircraft Corporation had one of the lowest accident frequencies, making it a potential candidate for investment.

📊 Visualization:

✔ Bar chart –  Total Accident counts per aircraft make

![image](https://github.com/user-attachments/assets/b5391b18-919d-49fc-ad2e-54023509582d)

2️⃣ **Injury & Fatality Rate Analysis**
Fatality rate = Total.Fatal.Injuries / Total Accidents
Serious injury rate = Total.Serious.Injuries / Total Accidents
Mooney Aircraft had one of the lowest fatality rates, reinforcing its safety record.

📊 Visualizations:

✔ Bar chart – Top 10 safest and riskiest aircraft based on fatality rate

![image](https://github.com/user-attachments/assets/167d83c0-60c4-40f2-84d8-b0434250ce8a)

3️⃣ **Total Uninjured by Make and Total Uninjured by Engine Type**
Yearly accidents were analyzed to determine if certain aircraft makes are improving in safety over time.
Mooney Aircraft had a consistently low accident rate over the years.

📊 Visualization:

✔ Bar chart - Total Uninjured by Make and Total Uninjured by Engine Type

https://public.tableau.com/app/profile/paul.otuoro/viz/02-11-2025-PO/Dashboard1?publish=yes

4️⃣ **Engine Type & Safety Analysis**
Aircraft were grouped by engine type (Engine.Type) to compare accident frequencies.
Mooney’s engine type had one of the safest records.

📊 Visualization:

✔ Bar chart – Accident rate per engine type

![image](https://github.com/user-attachments/assets/81c281de-5ba5-46b8-9f9c-151a2ef7a431)

5️⃣**Weather & Accident Correlation**
Accidents were analyzed based on weather conditions (Weather.Condition).
Aircraft operating in poor weather conditions (IMC - Instrument Meteorological Conditions) had a higher accident rate.

📊 Visualization:

✔ Stacked bar chart – Accident distribution by weather condition for different aircraft

![image](https://github.com/user-attachments/assets/9b032944-563d-412f-8a71-1eeee80bd807)

6️⃣ **Statistical Analysis**

Spearman Correlation – Determined if there was any correlation between aircraft make and fatal injuries (result: no strong correlation).

✅ **Final Recommendation**

Based on the data analysis, statistical tests, and visualizations, the organization should invest in Mooney Aircraft Corporation because:

✔ It has very few recorded accidents.

✔ It has one of the lowest fatality rates.

✔ Its engine type has a strong safety record.

👥 **Contributors**

Paul Otuoro – Data Analyst
Company Name: Moringa School

📅 Date: February 2025
