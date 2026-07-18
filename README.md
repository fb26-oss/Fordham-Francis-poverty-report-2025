Fordham Francis Index 2025


Authors
Frederic Bomba,  Adriana Curto, Luke Olsen, Philip Chan, Viviane Hirwa, David Osgood, Lisa Patern, Bismi Samia, Saujan Khapung
Coordinators Henry Schwalbenberg, Donna Odra, Giaccomo Santangelo

Fordham University, Graduate Program in International Political Economy and Development (IPED)

Project Overview

The Fordham Francis Index (FFI) is a composite global poverty measure developed by the Fordham IPED program and named in honor of Pope Francis. The index moves beyond purely economic measures of poverty, such as GDP per capita or the international poverty line, by combining material and spiritual dimensions of human deprivation into a single, comparable score for countries around the world.

The project is inspired by Pope Francis' repeated calls to see poverty as a multidimensional condition that affects not only a person's material security but also their dignity, freedom, and rights. The FFI operationalizes that vision by building two sub indices, the Material Wellbeing Index and the Spiritual Freedom Index, and combining them into the overall Fordham Francis Index.


Objective

The main objectives of this project are:

1. To construct a multidimensional poverty index that captures both material deprivation (water, food, housing, and employment) and spiritual or social deprivation (education, gender equity, and religious freedom).

2. To rank countries according to their FFI score and identify the nations most and least affected by global poverty in 2025.

3. To compare the explanatory power of the FFI against two widely used poverty and development benchmarks, GDP per capita and the Human Development Index (HDI), through correlation and regression analysis.

4. To provide a transparent, reproducible dataset and methodology that other researchers, students, and policymakers can use or extend.


Repository Contents

2025 Fordham Francis Index Report.pdf
The full written report. It documents the motivation, methodology, data sources, index construction formulas, country rankings, correlation analysis, regression results, and conclusions of the FFI project.

FFI Presentation 2025.pdf
The slide deck used to present the project. It walks through each of the seven underlying indicators (water, food, housing, employment, education, gender, and religious freedom), shows global trends and maps for each, presents the Material Wellbeing Index and Spiritual Freedom Index, and concludes with the combined Fordham Francis Index rankings and maps.

Consolidated 2024.xlsx
The underlying dataset. This workbook contains one sheet per indicator plus a consolidated summary sheet:

  Water: percent of population with basic access to an improved drinking water source, 2013 to 2022, sourced from the WHO/UNICEF Joint Monitoring Programme.

  Food: percent of population undernourished, 2013 to 2021, sourced from the Food and Agriculture Organization.

  Housing: percent of population living in inadequate housing, 2013 to 2022, sourced from the Oxford Poverty and Human Development Initiative.

  Employment: distressed labor rate (population unemployed or earning below 3.20 PPP dollars per day), 2013 to 2023, computed from International Labour Organization data.

  Education: adult literacy rate, 2013 to 2022, sourced from UNESCO and the World Bank.

  Gender: Health and Survival Index score (female to male ratio of life outcomes), sourced from the World Economic Forum Global Gender Gap Report.

  Religious Freedom: Government Restrictions Index score, sourced from the Pew Research Center.

  Consolidated: a summary sheet bringing together the most recent available year for each indicator by country, used as the base dataset for the index calculations.

  Sheet1 and Sheet2 contain supporting correlation matrix calculations referenced in the report.


Methodology Summary

The FFI is built in three stages.

Stage 1, Sectoral Indices. Each of the seven raw indicators is rescaled to a 0 to 1 range using a min max normalization:

Sectoral Index equals (Data minus Minimum Value) divided by (Maximum Value minus Minimum Value)

Stage 2, Sub Indices. The four material indicators (water, food, housing, employment) are combined using a geometric mean to form the Material Wellbeing Index. The three spiritual and social indicators (education, gender, religious freedom) are combined using a geometric mean to form the Spiritual Freedom Index.

Stage 3, Composite Index. The Material Wellbeing Index and the Spiritual Freedom Index are combined using a geometric mean, each weighted equally, to produce the final Fordham Francis Index:

Fordham Francis Index equals the square root of (Material Wellbeing Index multiplied by Spiritual Freedom Index)

Higher FFI scores indicate lower deprivation. The report also benchmarks the FFI, the Material Wellbeing Index, and the Spiritual Freedom Index against the log of GDP per capita and the Human Development Index using ordinary least squares regression, and reports a correlation matrix among the seven underlying indicators.

Suggested Citation

Fordham IPED. (2025). Fordham's Pope Francis Global Poverty Index. Fordham University, Graduate Program in International Political Economy and Development.


How to Use This Repository

1. Read the report PDF for the full narrative, methodology, and findings.

2. Review the presentation PDF for a visual summary suitable for classroom or conference use.

3. Open the Excel workbook to explore, verify, or extend the underlying country level data and calculations.

4. Researchers wishing to update or extend the index for future years can add new columns to each indicator sheet following the existing structure, then recompute the sectoral, material, spiritual, and composite indices using the formulas described above.


Data Sources

WHO/UNICEF Joint Monitoring Programme for Water and Sanitation
Food and Agriculture Organization of the United Nations
Oxford Poverty and Human Development Initiative
International Labour Organization
UNESCO and World Bank
World Economic Forum, Global Gender Gap Report
Pew Research Center, Government Restrictions Index


Contact

For questions about the data, methodology, or report, please open an issue in this repository.
