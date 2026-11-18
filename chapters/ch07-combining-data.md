---
title: "Combining Data from Multiple Sources"
label: ch-07
description: "Sabor Miami's sales arrive as monthly files, and the facts the owner needs are spread across Menu Items, Trucks and Employees."
---

# Combining Data from Multiple Sources

:::{important}
Preview: this chapter is being written. Here is what it will cover.
:::

## Purpose

Sabor Miami's sales arrive as monthly files, and the facts the owner needs are spread across Menu Items, Trucks and Employees. You will append the monthly files into one table, merge in details by matching a key, choose the right join kind, find orphan rows, and keep helper queries from cluttering the model.

## Learning objectives

By the end of this chapter you will be able to:

- Explain when to append and when to merge.
- Append two, then three or more, queries, and check the new row count equals the sum of the parts.
- Merge two queries on a key with matching data types and expand the columns you need.
- Choose among Left outer, Inner and Left anti joins and read a null after expanding.
- Build a staging query (Enable load off), make a Reference query, and name the final tables clearly.

## In this chapter

1. **Two reasons to combine.** Append stacks rows; merge adds columns by matching a key.
2. **Append: stacking the monthly files.** Columns match by name, not position, and the new row count must equal the sum of the parts.
3. **Keys and the Merge window.** Matching keys must have the same type, spacing and case. Read the match estimate before you click OK.
4. **Join kinds, and the null that tells you something.** Left outer is the usual choice. A null after expanding means no match, and a Left anti join lists the orphans.
5. **Staging queries and tidy loading.** Stage the pieces, combine them, and load only the final tables.

## Try This ideas

Each section ends with a short "Try This" activity. A few of the ideas:

- **Two reasons to combine.** For each of three situations you invent from Sabor Miami (one per type, plus one that needs neither), say append or merge.
- **Append: stacking the monthly files.** Append two months. Rename one column in one query before appending and see what Power BI does. Fix it and compare the row counts.
- **Keys and the Merge window.** Merge Sales with Menu Items on the menu item key. Read the match estimate. Then change the type of one key on purpose and see the estimate change.
- **Join kinds, and the null that tells you something.** Merge Sales to Menu Items with Left outer, expand the columns, and filter the expanded column for null. Describe any unmatched rows: what do they have in common, and what might it mean for the business? Repeat with Left anti and write how the two results relate.
- **Staging queries and tidy loading.** Turn off Enable load for one helper query, Close and Apply, and confirm it is gone from the Data pane. Write which queries in your report should load.

The chapter closes with a longer capstone Try This (about 20 minutes): one model-ready Sales table.

## Resources

Microsoft Learn pages for this chapter:

- [Merge queries overview](https://learn.microsoft.com/en-us/power-query/merge-queries-overview)
- [Append queries](https://learn.microsoft.com/en-us/power-query/append-queries)
- [Left outer join](https://learn.microsoft.com/en-us/power-query/merge-queries-left-outer)
- [Combine files overview](https://learn.microsoft.com/en-us/power-query/combine-files-overview)
