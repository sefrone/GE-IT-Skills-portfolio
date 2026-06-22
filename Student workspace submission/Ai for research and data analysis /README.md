
# Data Analytics & Visual Report #

## Dataset Focus: Mindanao Regional Waste Generation & Resource Recovery Index (Raw CSV Emergency Analysis) ##

### 1. Data Cleaning Protocol Log ###

Raw Input Problem: The CSV file contains duplicated municipal records, inconsistent date formats (MM/DD/YYYY and YYYY-MM-DD), blank values in the "Waste Generated (Tons)" column, and mixed unit measurements (kilograms, metric tons, and cubic meters). Several municipality names also contain spelling inconsistencies.

AI Cleaning Instruction:
"Upload and scan the complete CSV dataset. Detect and remove duplicate records. Standardize all date fields into YYYY-MM-DD format. Convert all waste volume measurements into Metric Tons (MT) using documented conversion factors. Identify missing values in the 'Waste Generated' and 'Recycled Volume' columns and impute them using the median value of comparable municipalities within the same province. Correct municipality name inconsistencies through fuzzy matching. Generate a Data Cleaning Log summarizing every structural adjustment and output the first 10 rows of the cleaned dataset."

Result: Successfully normalized all records into a standardized regional database, removed formatting corruptions, corrected geographic labels, and generated a validated dataset ready for policy analysis.


### 2. Visualizations Generated ###

(Embedded High-Contrast Trend Chart #1: Municipal Waste Generation by Province, 2020–2025)

[Interactive Visualization: Provincial Waste Generation Growth Trends]

(Embedded High-Contrast Trend Chart #2: Waste Recovery & Recycling Performance by LGU, 2020–2025)

[Interactive Visualization: Resource Recovery Rate Comparison Dashboard]

### 3. Human Analytical Narrative (The "Why" Factor) ###

"The visualizations reveal a significant divergence between waste generation growth and resource recovery capacity across several Mindanao provinces. While urbanized municipalities exhibit steady increases in total waste volume due to population growth and commercial expansion, recycling and recovery rates have not kept pace.

The second chart highlights a concentration of resource recovery performance among a small number of LGUs, suggesting unequal access to waste processing infrastructure and environmental management programs. This disparity creates increased pressure on local landfills and raises the likelihood of illegal dumping and waterway contamination.

From a regional development perspective, the findings indicate that future environmental investments should prioritize Material Recovery Facility (MRF) expansion, community-based segregation initiatives, and inter-municipal waste management partnerships. Strategic allocation of environmental funds can help reduce landfill dependence while supporting climate resilience objectives and public health outcomes across Mindanao.

Human review of the AI-generated findings further suggests that infrastructure gaps, rather than waste generation alone, are the primary driver of declining recovery efficiency in several municipalities. Policymakers should therefore focus not only on waste reduction campaigns but also on strengthening collection, sorting, and processing capacity at the local government level."

### 4. Automated GitHub Portfolio Publication Instruction ###

AI Instruction:

> "After completing the data cleaning and analysis workflow, generate a professional HTML or Markdown-based Automated Visual Data Report. Include:

1. Executive Summary


2. Data Cleaning Protocol Log


3. Cleaned Dataset Overview


4. Two Embedded Interactive High-Contrast Charts


5. Human Analytical Narrative


6. Policy Recommendations for Regional Decision-Makers


7. Data Sources and Methodology Notes



Publish the report structure in a GitHub-ready format suitable for direct upload to a public portfolio repository. Ensure all visualizations are responsive, accessible, and optimized for policymakers requiring rapid evidence-based decision-making during emergency budget deliberations."
