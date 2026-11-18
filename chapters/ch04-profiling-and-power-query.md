---
title: "Profiling Your Data and Meeting Power Query"
label: ch-04
description: "Before Sabor Miami's owner trusts a number, the analyst looks at each column on its own."
---

# Profiling Your Data and Meeting Power Query

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

Before Sabor Miami's owner trusts a number, the analyst looks at each column on its own. You will meet the Power Query Editor and Applied Steps, learn why data types matter, turn on the three profiling tools, describe one numeric and one categorical column in plain words, and build a histogram from bins in Report view.

## Learning objectives

By the end of this chapter you will be able to:

- Name the parts of the Power Query Editor and explain what Applied Steps record.
- Change a column's data type and explain why Text cannot be summed.
- Read Column quality (Valid, Error, Empty) and Column distribution (distinct and unique) for a column, and switch profiling from the top 1,000 rows to the entire data set.
- Describe one numeric column (average, median, spread, smallest and largest values, and shape) and one categorical column (count per value, most common value) in words.
- Build a histogram with bins and explain what a wider bin hides.

## In this chapter

1. **Look before you fix.** Profiling shows what is wrong without changing anything.
2. **The Power Query Editor and Applied Steps.** Power Query records every step, so any change can be seen, removed and replayed.
3. **Data types: why the little icon matters.** The type decides what you can do: text cannot be summed, numbers can.
4. **Column quality and distribution.** Quality tells you what share is valid, error or empty; distribution tells you how many different values there are.
5. **Univariate analysis: describing one column.** One column at a time: a numeric column gets a center and a spread, a categorical column gets counts and a most common value.
6. **The histogram: counting rows in bins.** A histogram counts rows per bin, and the bin size changes the story.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **Look before you fix.** In Table view, sort Tip from smallest to largest and back. Write the first odd thing you notice.
- **The Power Query Editor and Applied Steps.** Open the editor (Home > Transform data). Click an earlier step and watch the preview change. Delete a step you added, then reload the page of steps. What did the recorder keep?
- **Data types: why the little icon matters.** Change Amount to Text, then try to put it on a card. Change it back. Say what happened in one sentence.
- **Column quality and distribution.** Turn on all three profiling tools. Find the column with the most Empty. Read distinct and unique for Payment Method. Switch profiling to the entire data set and note what moves.
- **Univariate analysis: describing one column.** Describe Tip in three sentences and Payment Method in two, using only the profiling panes. Where did the panes stop helping you?
- **The histogram: counting rows in bins.** Right-click Amount in the Data pane, choose New group, set a Bin size, and put the bins on the X-axis of a clustered column chart with a count of rows. Change the bin size twice and write what you notice.

The chapter closes with a longer capstone Try This (about 20 minutes): profile Sales, one column at a time.

## Resources

Microsoft Learn pages for this chapter:

- [Using the data profiling tools](https://learn.microsoft.com/en-us/power-query/data-profiling-tools)
- [Use Power Query to Transform Data](https://learn.microsoft.com/en-us/power-query/power-query-ui)
- [Using the Applied Steps list](https://learn.microsoft.com/en-us/power-query/applied-steps)
- [Data types in Power Query](https://learn.microsoft.com/en-us/power-query/data-types)
- [Use grouping and binning in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-grouping-and-binning)
