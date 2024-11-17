# Project: Operating a Food Truck

You are planning to open a food truck.  Your plan is simple.  Make one food item very well.  This food item will have only four ingredients (I know this is unrealistic, but it will work for the sake of the simulation).

The files associated with this simulation are in the projects folders with the naming convention 02-FoodTruck.

The project will be broken up into 4 parts and each part will be turned in separately.  They may also be turned in together at the end, but each portion will go into the gradebook at set times.

## Part 3 - Simulate Second Month of Operation (30)

Now that you have operated for a month, you can make adjustments to your amount of inventory you plan to sell each week.  But to be on the safe side, make sure not to increase your inventory more than 15% of your greatest inventory from the first month.  Your cost of goods sold will still be determined by the number of items you have decided to sell (my number was 250) and the cost of your item.  The formula is repeated below:

```
CoGS = (PriceIngredient1 + PriceIngredient2 + PriceIngredient3 + PriceIngredient4 + PriceIngredient5) * NumberOfProducts
```

If there are more ingredients in your recipe, you will have more ingredients in your formula.  Remember that order of operations is important.  You must add all the costs together before multiplying by the number of products you are planning to sell.  You could also name that variable DailyInventory or something like that.  The CoGS in the formula is the total cost of the goods for that single day.

The cost of goods sold will be the same each day of any particular week.  In other words, you should not change the number of products you will try to sell during the days of the week.  Keep them constant for at least one week.  Then, after a week, you can change the number of products you plan to sell as long as you can justify it through your data.

Your income will be determined based on the [Daily Sales](https://github.com/MichaelTMiyoshi/AppliedMathWithMiyoshi/blob/main/AppliedAlgebra2/Projects/02-FoodTruck-DailySales-Month2.md) as listed in the linked page.  Note that the page has 28 days.  Days 7, 14, 21, and 28 will not be used as sales days, so you can ignore them for your income.

You will have some other things happen in this third phase.  You will have various good and bad things happen.  These are on the linked page as well.  Note that you will have some flexibility with these happenings.  For instance, if you get ill, you will decide whether you are going to reduce your income or hire somebody to take your place (which increasses your payroll).

Points:  Points will be earned by filling in the proper amounts for each day of the month on each of the various worksheets (15 points) and making graphs of your income or number of items sold (10 points) and justifying your changes (or no changes) in your inventory plan for the weeks (5 points).  Several of the worksheets will have the same or similar numbers in them each day, but they must still be filled out properly.  This includes the chance happenings that will occur each week.  Sums for each week must be completed as well.  Graphs of the sales for one week, two weeks, three weeks, and four weeks (make sure to include all the weeks when creating the graphs beyond the first week of data) must be done.  Look at the graphs and write down reasons based on those graphs as to why you would want to change the daily inventory for the next week.

The other formulas for daily amounts that you will need are repeated below:

```
CoGS = (PriceIngredient1 + PriceIngredient2 + PriceIngredient3 + PriceIngredient4 + PriceIngredient5) * NumberOfInventoryProducts
Payroll = Rate * HoursPerDay
MonthlyOverhead = TruckPayment + Utilities + Licensing
DailyOverhead = MonthlyOverhead / DaysWorking
Income = NumberOfProductsSold * ConsumerPrice
Net = Income - (CoGS + Payroll + DailyOverhead)
```
