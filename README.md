# Audible Data Cleaning & Standardization | Excel Power Query

## Project Overview

This project demonstrates how Excel Power Query can transform raw Audible audiobook data into a clean, consistent, and analysis-ready dataset.

The objective was to improve data quality by standardising text, converting data types, separating combined fields, validating numeric values, and creating a consolidated release information column.

## Business Context

Audible's audiobook catalogue contains information about book titles, authors, narrators, release dates, languages, prices, and customer ratings.

Inconsistent formatting and mixed data types can affect reporting accuracy, search functionality, and downstream analysis. This project applies systematic data-cleaning techniques to improve data consistency and reliability.

## Tools & Technologies

- Microsoft Excel
- Power Query Editor
- Data transformation and standardisation
- Data type conversion and validation
- Text manipulation and column operations

## Data Cleaning Tasks

The project covers nine data-cleaning tasks:

1. ** Standardise Title Casing:** Apply consistent title casing to book names.
2. **Separate Multiple Authors:** Split combined author names into separate fields.
3. **Standardize Release Dates:** Convert release dates to a consistent DD-MM-YYYY format.
4. **Convert Time to Duration:** Transform text-based listening durations into recognisable duration values.
5. **Validate Prices:** Convert price values to numeric/currency types and identify invalid entries.
6. ** Standardise Ratings:** Convert text-based star ratings into numeric values where applicable.
7. **Split Narrator Details:** Separate combined narrator information into individual fields.
8. **Create Release Information:** Combine the formatted release date and language into a new `releaseinfo` column.
9. **Format Currency:** Display prices consistently with two decimal places.

## Key Power Query Techniques

- Capitalise Each Word
- Split Column by Delimiter
- Change Type with Locale
- Custom Column transformations
- Text extraction and replacement
- Data type conversion
- Merge Columns
- Data validation and formatting

## Project Outcomes

- Improved consistency in book titles and contributor information.
- Standardised release-date and duration representations.
- Prepared price and rating fields for quantitative analysis.
- Created a consolidated release information field.
- Established a repeatable data-transformation workflow using Power Query.

## Business Value

Clean and standardised audiobook data supports more reliable reporting, improved catalogue management, consistent filtering, and better downstream analysis.

## Project Files

- `Audible_Data_Cleaning.pdf` — Project presentation documenting the business context, nine cleaning tasks, transformation steps, and before-and-after examples.
- `Audible_Data_Cleaning.xlsx` — Include this file if you have the Excel workbook containing the Power Query transformations.

## How to Review the Project

1. Open the project PDF to understand the cleaning requirements.
2. Review the nine transformations and their before-and-after examples.
3. If the Excel workbook is included, inspect the Power Query steps to understand how the transformations were implemented.

## Disclaimer

This is an independent data-cleaning portfolio project for learning and demonstrating Excel Power Query skills. The project focuses on data preparation rather than predictive modelling or dashboard development.
