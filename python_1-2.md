# Python Chapter 1-2

- Stay in http://pythontutor.com/live.html#mode=edit

```python
# Playing around with ages
your_age = 27
double_your = your_age * 2
decades_old = your_age // 10

# Henry's Candy Scandle
cost_of_bag = 3
candies_in_bag = 30
revenue_per_candy = .25
bags_per_week = 5
cost_per_candy = cost_of_bag / candies_in_bag
profit_per_candy = revenue_per_candy - cost_per_candy
profit_per_bag = profit_per_candy * candies_in_bag
profit_per_week = profit_per_bag * bags_per_week

# Buying ram for your computers!
ram_kits_needed = 30
dollars_per_ram_kit = 34.99
gross_total = ram_kits_needed * dollars_per_ram_kit
bulk_discount_percentage = 5
total = gross_total * ((100 - bulk_discount_percentage) / 100)

# How many hours will you code?
hours_per_week = 40
months_in_program = 11
weeks_in_month = 4
weeks_programming = months_in_program * weeks_in_month
hours_programming = weeks_programming * hours_per_week

# How much will it cost you if you buy a coke every day?
cost_of_coke = .75
months_in_program = 11
weeks_in_month = 4
days_in_week = 5
cokes = months_in_program * weeks_in_month * days_in_week
total_cost = cost_of_coke * cokes

# Monthly Budget
# based on quicken article:
# https://www.quicken.com/home-budget-cost-living-reality-check
salary = 50000
paycheck = salary / 12 # 1 check per month
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
paycheck_after_monthly_expenses = paycheck - monthly_expenses
# What errors will these lines give?
# 1 / 0
# 5 = five
# 12 + three
```
