# The MBBS Dream Dilemma: Seats. Dreams. Reality

**A Data-Driven Story of India’s Medical Aspirants (2019–2024)**

## Overview

This repository contains a comprehensive analysis of medical education challenges faced by Indian students. Combining NEET and FMGE statistics (2019–2024), it uncovers the true odds, trends, and outcomes for those pursuing MBBS in India and abroad.

## Data Source

- **National Board of Examinations’ Report on Country/Institute Wise Performance in FMGE (2019–2024)**

## Project Highlights

- 📊 Deep-dive analysis of over 2 million students and 2000+ colleges
- 🇮🇳 India’s MBBS seat bottleneck visualized
- 🌏 Trends and pass rates of top & emerging foreign MBBS destinations
- ⚖️ Challenges and insights for stakeholders: students, parents, educators, and policymakers

---

## Carousel
The data analysis was presented in form of a carousel on LinkedIn. View the ![carousel](/FMGE_Data_Analysis)
Below is a preview of the cover and selected slides from the LinkedIn carousel:


---


## Data & Methodology

- **Data file:** ![FMGE_Data](FMGE_Data_Analysis.xlsx)
- **Data visualization files** ![NEET Exam Statistics]([NEET Exam Statistics.png](FMGE-Data-Story/blob/main/NEET%20Exam%20Statistics.png)), ![FMGE Exam's % Pass Rate vs. Year](FMGE-Data-Story/blob/main/%25%20Pass%20Rate%20vs.%20Year.png) and ![Top 10 destinations for Foreign MBBS](FMGE-Data-Story/blob/main/Top%2010%20Destinations.png).

This analysis was conducted using a rigorous, multi-stage workflow leveraging Google Sheets for all data operations. Year-wise FMGE results were individually downloaded as PDF documents from the official National Board of Examinations in Medical Sciences’ website (https://natboard.edu.in/). Each PDF was converted into Excel format using specialized online tools to ensure accurate data extraction.

The Excel files representing different years were integrated into a single `.xlsx` workbook, with every year’s data housed in a dedicated sheet. For in-depth country-wise analysis, summary sheets were meticulously developed using advanced spreadsheet functions such as `COUNTIF` and `SUMIF` to aggregate results across all years.

Data cleaning was performed with a focus on precision:
- **Repetitions and missing information** were resolved through careful sorting, filtering, and de-duplication.
- **Inconsistent country names** (e.g., alternate spellings, abbreviations, or informal references) were standardized using lookup tables, naming conventions, and automated functions including `IFERROR` to handle exceptions.
- All steps ensured robust harmonization of data for downstream analysis.

Analytical operations included the use of functions like `VLOOKUP`, `SUM`, and various arithmetic operations to generate key metrics and insights. A `final_result` summary sheet was constructed to distill the cleaned, consolidated data into actionable narratives and core findings.

For data visualization, a series of interactive and static bar charts were produced directly within Google Sheets, spotlighting trends, comparisons, and summary statistics critical to stakeholders. The entire analytical process demonstrates proficiency in large-scale data management, advanced spreadsheet techniques, data cleaning, transformation, and compelling data storytelling—ensuring results are transparent, reproducible, and relevant for diverse audiences.


## Key Insights

- Only **1 in 22** NEET applicants secures an MBBS seat in India.
- From **297,757** foreign MBBS graduates, just **22%** passed the FMGE (2019–2024).
- Pass rates vary sharply by country; new destinations are rising, but with mixed outcomes.

---

## Reuse & Collaboration

- **Open for discussion:** Contact via Issues or Pull Requests for collaboration, use, or questions.
- **For full LinkedIn post:** [Link to your LinkedIn post] (Add after publishing)

---

## License

Distributed under the MIT License. See `LICENSE` for more info.
