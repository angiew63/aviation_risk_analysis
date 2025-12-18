# Aviation Risk Analysis

## Overview
This project analyzes historical aviation accident data to identify lower-risk aircraft for a company entering the aviation industry. The goal is to provide data-driven recommendations that minimize safety, financial, and operational risks.

## Business Understanding
The company plans to purchase and operate aircraft for commercial and private use but lacks aviation risk expertise.  
**Key Business Questions:**
- Which aircraft manufacturers present the lowest injury risk?
- How severe are injuries in typical aviation incidents?
- How often do accidents result in severe aircraft damage?

## Data Understanding and Analysis
**Data Source:**  
National Transportation Safety Board (NTSB) aviation accident data (1962–2023)

The dataset includes information on aircraft make and model, injury severity, aircraft damage, and purpose of flight. Data cleaning and aggregation were performed using pandas to calculate injury risk and summarize accident outcomes.

## Methodology
1. Cleaned and prepared aviation accident data in Python
2. Created an Injury Risk Score from injury severity
3. Aggregated injury risk by:
   - Aircraft manufacturer
   - Aircraft damage level
   - Purpose of flight
4. Visualized findings using Tableau dashboards

### Key Visualizations
*(Visuals generated using Python and Matplotlib)*

## Interactive Dashboard
Tableau Public Dashboard:  
<https://1drv.ms/f/c/72382ae919dbc767/IgCKxml3VcOpRpgXSUrgyirYARHSdLzmADS2Fr28dsxAPnE?e=tMqsgt


1. **Lowest Injury Risk Aircraft Manufacturers**  
   Identifies manufacturers with consistently lower injury outcomes.

2. **Distribution of Injury Severity**  
   Shows that most incidents result in minor or no injuries.

3. **Aircraft Damage Levels**  
   Demonstrates that total aircraft destruction is less common than minor or substantial damage.

## Conclusion
The analysis indicates that selecting aircraft from manufacturers with lower historical injury risk, prioritizing safer use cases, and avoiding high-damage models can significantly reduce operational risk. These insights support a safer and more cost-effective entry into the aviation market.

## Recommendations
- Prioritize aircraft manufacturers with consistently lower injury risk
- Avoid operational contexts associated with higher injury risk
- Use aircraft damage severity as a key risk indicator in safety planning
