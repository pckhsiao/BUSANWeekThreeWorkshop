# General Notes / Guidance When Creating Power BI Report

You can use GenAI tools for brainstorming, coding, or software assistance.

## 1.	Import the data into Power BI Desktop and build a data model

 - Ensure the data types are correctly specified. There is no need for further data cleaning or transformations.
 - Create a Date dimension table using the `CALENDARAUTO()` function.
 - Ensure the relationships between tables are correctly established.

## 2. Create calculated columns and/or calculated measures that could help provide useful insights

 - For instance, you could use nested `IF()` statements or the `SWITCH()` function to create a `Crash Severity` column, which reflects the most severe injury sustained in a crash (categories: `Fatal`, `Serious`, `Minor`, and `Non-injury`), and a `Crash Serious` column, which indicates whether a death or serious injury occurred in a crash (categories: `Yes` and `No`).
 - If calculation groups are created and your visuals do not display as expected, create explicit measures and use those measures in the visuals.

## 3. Format and adjust properties to enhance data usability and report aesthetics

 - For instance: rename tables and columns; hide tables and/or columns that end users should not see or use; format fields used in visuals (e.g., % and thousand separator); set data categories for location-related data; and create hierarchies.

## 4. Build a Power BI report

 - The output should feature relevant and appropriate visuals and be user-friendly and nicely formatted.
 - Focus on communicating information of interest to end users (i.e., not all data provided need to be analysed and presented).
 - Select visuals that are appropriate for the data being visualised and apply principles of effective visualisation and report design.
 - Make use of the `Slicer` visual and/or the `Filters pane` for filtering.
