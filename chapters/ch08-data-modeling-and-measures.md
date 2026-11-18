---
title: "Data Modeling and Your First Measures"
label: ch-08
description: "The cleaned, combined tables become a model. Sabor Miami gets a star schema: one fact table of sales and dimension tables for trucks, menu items, employees and events."
---

# Data Modeling and Your First Measures

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

The cleaned, combined tables become a model. Sabor Miami gets a star schema: one fact table of sales and dimension tables for trucks, menu items, employees and events. You will draw the relationships, write four explicit measures in DAX, and build a matrix of revenue by truck and month with a slicer to ask your first multivariate question.

## Learning objectives

By the end of this chapter you will be able to:

- Identify the fact table and the dimension tables in the Sabor Miami model, and state the grain of the fact table.
- Create a relationship in Model view with Many to one cardinality and a Single cross filter direction, and fix the "One of the columns must have unique values" error.
- Write four explicit measures (SUM, COUNTROWS, DISTINCTCOUNT, DIVIDE) and format them.
- Explain why a measure gives a different number in each matrix cell and after each slicer click.
- Build a matrix with a slicer, sort a month name by its month number, and check the matrix total against a card and a Group By total.

## In this chapter

1. **What a data model is: fact and dimension.** The fact table records events; the dimension tables describe them.
2. **Relationships: cardinality and filter direction.** Many to one, single direction: filters flow from the one side to the many side.
3. **Build the star in Model view.** Drag the key, check the cardinality, and if it complains about unique values, clean the dimension.
4. **Columns, measures, and your first four formulas.** A column is worked out row by row and stored; a measure is worked out when a visual asks for it, using that visual's filters.
5. **A matrix, a slicer, and months in order.** Same measure, different filters: every cell and every slicer click changes what the measure sees.
6. **Multivariate questions, correlation, and what comes next.** Multivariate means one measure across several dimensions, and correlation shows a link, not a cause.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **What a data model is: fact and dimension.** Open Model view. Say which table is the fact table and how you know. Write the grain in one sentence.
- **Relationships: cardinality and filter direction.** Pick one dimension and the fact table. Predict which columns Power BI will connect and which side is the one. Check against Model view.
- **Build the star in Model view.** Create two relationships. Deliberately pick a column with duplicates and read the error. Fix it. Describe in a sentence what the line looks like when it is right.
- **Columns, measures, and your first four formulas.** Write Total Revenue. Put it on a card, then in a table by Truck. Why does the same measure show different numbers? Write it in your own words.
- **A matrix, a slicer, and months in order.** Build the matrix with Truck in Rows, Month Name in Columns and Total Revenue in Values. Fix the month order. Click two slicer values and write what changed.
- **Multivariate questions, correlation, and what comes next.** Add a second slicer and click around. Pick one combination that interests you and write what you see in one business sentence, then one reason it might not be a cause. Say what you would ask the owner next.

The chapter closes with a longer capstone Try This (about 25 minutes): revenue by truck and month, checked three ways.

## Resources

Microsoft Learn pages for this chapter:

- [Understand star schema and the importance for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)
- [Create and Manage Relationships in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-create-and-manage-relationships)
- [Measures in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-measures)
- [Tutorial: Create your own measures in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-tutorial-create-measures)
- [Create a Matrix Visual in Power BI](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-matrix-visual)
- [Sort by column](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-sort-by-column)
- [Use quick measures for common and powerful calculations](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-quick-measures)
