# NVDA (v2020)
Understand the core navigation methods for NVDA with the [NVDA keyboard shortcuts](https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts). 

<a href="https://govau.github.io/accessibility/">Demo calibration page</a>

## Screen reader tests
1. `Ensure the screen reader output matches the visual output of all headings`
1. `Ensure the screen reader output matches the visual output of all links (as a minimum)`
1. `Ensure the screen reader output matches the visual output of all list elements`
1. `Ensure the screen reader output the first 2 rows of a table and announces the columns`
1. `Ensure the screen reader output every visual error message`
1. `Ensure the screen reader output all significant page activity (ajax spinner icon, new page)`
1. `Ensure the screen reader output a controls outcome (collapsed/expanded, x number of items returned)`

## General
1.	Open Chrome
2.	Go to the testing URL
3.	Start NVDA

## Test Headings
1.	Press **H** to move forward through all headings, **Shift + H** to move backward through all headings
3.	TEST : `Ensure the screen reader output matches the visual output of all headings`

## Test Links
1.	Press **K** to move forward through all links, **Shift + K** to move backward through all links
3.	TEST : `Ensure the screen reader output matches the visual output of all links (as a minimum)`

## Test Lists

1.	Press **L** to move forward through all lists, **Shift + L** to move backward through all lists
2.  Within each list Press **I** to move forward through all list items, **Shift + I** to move backward through all list items
3.	TEST : `Ensure the screen reader output matches the visual output of all list elements`

## Test Tables

1.	Press **T** to move forward through all tables, **Shift + T** to move backward through all tables
2.	Within each table press **Down Arrow** to move forward through the cells, **Up Arrow** to move backward through the cells
4.	TEST : `Ensure the screen reader output the first 2 rows of a table and announces each column`

## Test Error Messages

1. Trigger all form errors
2. TEST : `Ensure the screen reader output every visual error message` without swiping

## Test Screen Activity

1. Trigger significant screen change (only relevant for Single Page Applications)
2. TEST : `Ensure the screen reader output all significant page activity (ajax spinner icon etc)`
