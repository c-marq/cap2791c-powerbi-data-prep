---
title: "Transforming and Reshaping Data"
label: ch-06
description: "Clean data is not yet ready data. Sabor Miami needs names split, columns merged, a revenue column worked out, dates broken into year and month, rows grouped into totals, and a wide monthly table turned into a tall one."
---

# Transforming and Reshaping Data

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

Clean data is not yet ready data. Sabor Miami needs names split, columns merged, a revenue column worked out, dates broken into year and month, rows grouped into totals, and a wide monthly table turned into a tall one. The chapter ends with your first two-column questions and the right visual for each pair.

## Learning objectives

By the end of this chapter you will be able to:

- Split, merge and extract text columns, and say when each is the right tool.
- Add a custom column and a conditional column, and check the result against a trusted column.
- Create year, month number and month name columns from a Date column, and explain why the number and the year are kept.
- Group rows with Group By, and prove the group totals add up to the original total.
- Unpivot a wide table, and choose a visual for a category-with-number or category-with-category pair.

## In this chapter

1. **Taking text apart and putting it together.** Transform changes a column in place; Add Column keeps the original and adds a new one.
2. **New columns from formulas.** Fix the types first, write the formula second, and check the new column against one you trust.
3. **Dates: keep the month number and the year.** Keep the month number and the year; show the month name.
4. **Group By: from many rows to a few.** Group By makes the table shorter, and the group totals must add up to the total you started with.
5. **Wide to tall: unpivot.** Models and charts prefer tall tables: one row per fact.
6. **Bivariate analysis: two columns at a time.** Pick the pair type first, category with number or category with category, and the visual follows.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **Taking text apart and putting it together.** Split the Events location text by its delimiter, then merge two columns with a separator you choose. Rename the new columns, set their types, and remove a column you will not need. Which step would you hate to do by hand for every row?
- **New columns from formulas.** Add a custom column of Quantity times Unit Price and compare it with Amount. Add a conditional column that labels tips "none" or "some". What do you learn if the first column disagrees with Amount?
- **Dates: keep the month number and the year.** Add Year, Month and Name of Month from Date. Put Name of Month on a table visual and see how it sorts. What would fix it? (Chapter 8 does.)
- **Group By: from many rows to a few.** Group Sales by Truck and sum Amount. Add the totals by hand or with a card and compare with the original total. If they differ, what would you check first?
- **Wide to tall: unpivot.** Unpivot the monthly totals table, rename the new columns, and make a table visual. Which version would you rather chart, and why?
- **Bivariate analysis: two columns at a time.** Choose one pair from Sales. Build one visual and explain it in two sentences: what you compared, and what it suggests for the business.

The chapter closes with a longer capstone Try This (about 20 minutes): from clean data to a two-column answer.

## Resources

Microsoft Learn pages for this chapter:

- [Split columns by delimiter](https://learn.microsoft.com/en-us/power-query/split-columns-delimiter)
- [Add a custom column](https://learn.microsoft.com/en-us/power-query/add-custom-column)
- [Add a conditional column](https://learn.microsoft.com/en-us/power-query/add-conditional-column)
- [Common query tasks in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-common-query-tasks)
- [How to GROUP BY or Summarize Rows](https://learn.microsoft.com/en-us/power-query/group-by)
- [Unpivot columns](https://learn.microsoft.com/en-us/power-query/unpivot-column)
- [Create and use column charts in Power BI](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-column-charts)
