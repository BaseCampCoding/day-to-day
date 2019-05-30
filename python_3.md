# Python Chapter 3

- Stay in http://pythontutor.com/live.html#mode=edit

```python
# Playing around with ages
def double_your_age(your_age):
    return your_age * 2

def decades_old(your_age):
    return your_age // 10

nates_age = 28
double_nates_age = double_your_age(nates_age)

nates_decades_old = decades_old(nates_age)

# Henry's Candy Scandle
def profit_per_week(cost_of_bag, candies_in_bag, revenue_per_candy, bags_per_week):
    cost_per_candy = cost_of_bag / candies_in_bag
    profit_per_candy = revenue_per_candy - cost_per_candy
    profit_per_bag = profit_per_candy * candies_in_bag
    return profit_per_bag * bags_per_week

henrys_weekly_profit = profit_per_week(3, 30, .25, 5)

# Monthly Budget
# based on quicken article:
# https://www.quicken.com/home-budget-cost-living-reality-check
monthly_expenses = 0
monthly_expenses += 634 # rent
monthly_expenses += 211 # utilities
monthly_expenses += 317 # food
monthly_expenses += 211 # transportation
monthly_expenses += 211 # debt repayment
monthly_expenses += 106 # saving
monthly_expenses += 106 # clothing
monthly_expenses += 106 # entertainment
monthly_expenses += 106 # miscellaneous

def paycheck(salary):
    return salary / 12

def paycheck_after_expenses(salary):
    return paycheck(salary) - monthly_expenses

graduate_salary = 50000
graduate_paycheck_after_expenses = paycheck_after_expenses(graduate_salary)

# What happens to `mystery_number`
mystery_number = 10

def mystery_function():
    mystery_number = 5

mystery_number # ??? What is it ???

mystery_function()

mystery_number # ??? What is it ???
```
