
## Python Chapter 1-2

```python
# Playing around with ages
>>> your_age = 27
>>> double_your = your_age * 2
>>> double_your_age
54
>>> decades_old = your_age // 10
>>> decades_old
4
>>> # Henry's Candy Scandle
>>> cost_of_bag = 3
>>> candies_in_bag = 30
>>> revenue_per_candy = .25
>>> bags_per_week = 5
>>> cost_per_candy = cost_of_bag / candies_in_bag
>>> cost_per_candy
0.1
>>> profit_per_candy = revenue_per_candy - cost_per_candy
>>> profit_per_candy
0.15
>>> profit_per_bag = profit_per_candy * candies_in_bag
>>> profit_per_bag
4.5
>>> profit_per_week = profit_per_bag * bags_per_week
>>> profit_per_week
22.5
>>> # Monthly Budget
>>> # based on quicken article:
>>> # https://www.quicken.com/home-budget-cost-living-reality-check
>>> salary = 50000
>>> paycheck = salary / 12 # 1 check per month
>>> paycheck
4166.666666666667
>>> monthly_expenses = 0
>>> monthly_expenses += 634 # rent
>>> monthly_expenses += 211 # utilities
>>> monthly_expenses += 317 # food
>>> monthly_expenses += 211 # transportation
>>> monthly_expenses += 211 # debt repayment
>>> monthly_expenses += 106 # saving
>>> monthly_expenses += 106 # clothing
>>> monthly_expenses += 106 # entertainment
>>> monthly_expenses += 106 # miscellaneous
>>> monthly_expenses
2008
>>> paycheck - monthly_expenses
2158.666666666667
```