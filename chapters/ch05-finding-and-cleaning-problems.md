---
title: "Finding and Cleaning Problems in Your Data"
label: ch-05
description: "The problem list from Chapter 4 becomes a cleaning plan: missing tips, payment methods written four ways, extra spaces, numbers stored as text, duplicate rows and impossible values."
---

# Finding and Cleaning Problems in Your Data

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

The problem list from Chapter 4 becomes a cleaning plan: missing tips, payment methods written four ways, extra spaces, numbers stored as text, duplicate rows and impossible values. You will choose each fix by its business meaning, apply it in Power Query so it replays on refresh, and prove that it worked.

## Learning objectives

By the end of this chapter you will be able to:

- Name the seven kinds of data problems and match a fix to each.
- Decide among remove, replace and fill for a null, and defend the choice with the business meaning.
- Standardize text with Trim, Clean, a case choice and Replace Values.
- Turn numbers stored as text into numbers, and handle the errors that remain.
- Remove duplicate rows and impossible values, and prove every fix with a before and after row count.

## In this chapter

1. **Seven ways data goes wrong.** Name the problem before you pick the fix.
2. **Missing values: remove, replace or fill.** The business meaning decides: remove the row, replace the value, or fill it down.
3. **Text that looks the same but is not.** Power Query is case-sensitive and space-sensitive, so Trim, Clean and a case choice make text match.
4. **Numbers stored as text, and errors.** Strip the extra words, turn N/A into null, set the type, and only then decide what to do with the errors left.
5. **Duplicates and impossible values.** Trim and Clean before Remove Duplicates, and ask the business before you delete a value that looks impossible.
6. **Clear names, and proving the fix worked.** Clean in Power Query, not in the source: the steps replay on refresh, and the counts prove each fix.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **Seven ways data goes wrong.** Open Sales in Table view and find one example of two different problem kinds. Write each in one line.
- **Missing values: remove, replace or fill.** Replace null tips with 0 in one copy of the query and remove those rows in another. Compare the average tip in each. Which tells the truer story, and why?
- **Text that looks the same but is not.** Standardize Payment Method with Trim, Clean, a case choice and Replace Values. Look at the Column distribution before and after. Write what you noticed in the bars, and what you would tell a teammate who asks how you knew it worked.
- **Numbers stored as text, and errors.** Find the values that stop a numeric-looking column from converting. Fix one kind in Power Query and watch Column quality. Write what changed, what is still wrong, and a case where Replace Errors would hide a real problem.
- **Duplicates and impossible values.** Remove duplicates using the key column alone, then using all columns. Compare the row counts. Find one impossible value and write who you would ask before changing it.
- **Clear names, and proving the fix worked.** Edit the source file, add one messy row, refresh, and see whether your steps cleaned it. Write the row count before and after each fix in a log.

The chapter closes with a longer capstone Try This (about 20 minutes): clean the Sabor Miami data and keep a cleaning log.

## Resources

Microsoft Learn pages for this chapter:

- [Clean, Transform, and Load Data in Power BI (training module)](https://learn.microsoft.com/en-us/training/modules/clean-data-power-bi/)
- [Replace values and errors](https://learn.microsoft.com/en-us/power-query/replace-values)
- [Fill values in a column](https://learn.microsoft.com/en-us/power-query/fill-values-column)
- [Dealing with errors](https://learn.microsoft.com/en-us/power-query/dealing-with-errors)
- [Working with duplicates](https://learn.microsoft.com/en-us/power-query/working-with-duplicates)
- [Filter by values](https://learn.microsoft.com/en-us/power-query/filter-values)
- [Using the Applied Steps list](https://learn.microsoft.com/en-us/power-query/applied-steps)
