# Meal Split Calculator
A simple webpage that helps calculate how to split the cost of a meal with other people.

1. [Overview](#overview)
1. [How to Use](#how-to-use)

[Go to Meal Split Calculator here](MealSplitCalculator.html) or [the GitHub Pages hosted one here](https://rkanter.github.io/MealSplitCalculator/MealSplitCalculator.html).

### Overview
Typically, we know how much each dish costs, but things get more complicated when there's taxes, fees,
discounts, tips, and other shared expenses on top.  
The calculator basically figures out the percentage of the total cost that each dish/person contributed,
and then scales the overall total by that amount, to ensure that each person pays their fair share of
the shared expenses.

Here's an example to better illustrate things:

<img src="/screenshot.png" width="50%" />

You can play with it live [here](MealSplitCalculator.html?total=123.45&row=Phillip%7C21.17&row=Leela%7C17.22&row=Bender%7C44&row=Zoidberg%7C0&row=Amy%7C18.21)
or [here on GitHub Pages](https://rkanter.github.io/MealSplitCalculator/MealSplitCalculator.html?total=123.45&row=Phillip%7C21.17&row=Leela%7C17.22&row=Bender%7C44&row=Zoidberg%7C0&row=Amy%7C18.21).

### How to Use:
1. Enter the total cost of the meal in the "Overall Total" box at the top
1. In the table, enter each person's name and cost of their individual dish
   - You can add additional rows with the "Add row" button
   - You can remove a row by clicking the "X" button next to it
1. Once everything is entered, the "Top Pay" column indicates how much each person should pay.
   - You can verify that the "Cost" in the "Totals" row matches the subtotal on your bill
   - You can also verify that the "Taxes, Fees, Discounts, Tips, etc" amount matches your bill
   - Note that there may be some slight rounding, but that's okay because we're talking about a cent or two and you can't realistically pay partial cents anyway

If you want to share this calculation with other people, simply click the "Copy Link" button at the
bottom of the page to get a link to a pre-filled out version of this page that you can paste anywhere.
