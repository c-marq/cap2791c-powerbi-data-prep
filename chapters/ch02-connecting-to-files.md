---
title: "Connecting to Files You Already Know"
label: ch-02
description: "Sabor Miami's records arrive in three file types: sales as a CSV, menu items in an Excel workbook, and employees in a tab-delimited text file."
---

# Connecting to Files You Already Know

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

Sabor Miami's records arrive in three file types: sales as a CSV, menu items in an Excel workbook, and employees in a tab-delimited text file. You will open each one in its own tool first, connect it to Power BI, read the preview before loading, and learn what Import mode and Refresh do. This is also the first chapter that opens the Power Query Editor, to repair a broken file path.

## Learning objectives

By the end of this chapter you will be able to:

- Describe what a CSV and a tab-delimited file contain and name the delimiter of each.
- Connect Power BI Desktop to a CSV file, a tab-delimited text file and an Excel workbook, and choose a table rather than a sheet in the Navigator.
- Read the file preview (delimiter, Data Type Detection, first rows) and decide between Load and Transform Data.
- Explain what Import mode and Refresh do, and repair a broken file path from the Source step.
- Check the row count of each loaded table against its source file.

## In this chapter

1. **Flat files: what a CSV really is.** A CSV is a table written as text, with a delimiter between the values.
2. **The Get data list and the file preview.** Read the preview first: the delimiter, the types and the first rows tell you whether the load will be right.
3. **Excel workbooks: sheets, tables and the Navigator.** When a workbook has a table, pick the table, not the sheet.
4. **Import mode, Refresh and the broken path.** Import takes a copy; Refresh re-reads the file; a moved file breaks the link, and the Source step is where you repair it.
5. **Load or Transform Data, then count the rows.** After every load, count the rows and compare them with the source.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **Flat files: what a CSV really is.** Open the Sales CSV in Notepad. Count the commas in one row. Open the tab-delimited file and say what separates its values. What would break if a menu item name contained a comma?
- **The Get data list and the file preview.** Connect the CSV and set Data Type Detection to "Do not detect". Notice what changes in the preview. Then set it back. Why might a guess from the first 200 rows be wrong?
- **Excel workbooks: sheets, tables and the Navigator.** Load the Menu Items sheet, then the Menu Items table. Compare the first rows of each. Which would you hand to a teammate?
- **Import mode, Refresh and the broken path.** Add one row to the CSV, save and close it, then click Home > Refresh and watch the row count. Then move the file to another folder, refresh, read the error, and repair the path with the gear beside the Source step.
- **Load or Transform Data, then count the rows.** Load all three files. Find them in the Data pane, rename one query, and compare each row count with its source. Write down any difference.

The chapter closes with a longer capstone Try This (about 18 minutes): three formats, one report.

## Resources

Microsoft Learn pages for this chapter:

- [Power Query Text/CSV connector](https://learn.microsoft.com/en-us/power-query/connectors/text-csv)
- [Connect to data in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-connect-to-data)
- [Data sources in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources)
- [Power Query Excel connector](https://learn.microsoft.com/en-us/power-query/connectors/excel)
- [Data refresh in Power BI](https://learn.microsoft.com/en-us/power-bi/connect-data/refresh-data)
- [Use Power Query to Transform Data](https://learn.microsoft.com/en-us/power-query/power-query-ui)
- [Getting data overview (Power Query)](https://learn.microsoft.com/en-us/power-query/get-data-experience)
