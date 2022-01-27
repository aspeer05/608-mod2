# 608-mod2
Module 02 Project

# Calculate Measures of Central Tendency - Native Python
import statistics
values = [47, 95, 88, 73, 88, 84]
values = [47, 95, 88, 73, 88, 84]
statistics.mean(values)
79.16666666666667
mean = sum(values) / len(values)
mean
mean
79.16666666666667
# same as statistics module
​
​
count = len(values)
print(f'{count}')
6
total = sum(values)
print(total)
475
 module
# 7. Calculate Measures of central tendency - with static module
import statistics  #I know I have already called the statsitcs module and set the values, but am not sure the best way to document it to show you
values = [47, 95, 88, 73, 88, 84]
statistics.mean(values)
79.16666666666667
statistics.median(values)
statistics.median(values)
86.0
statistics.mode(values)
88
# All answers are the same as the book
​
 8. Custom Central Tendency
# 8. Custom Central Tendency
kidsages = [5, 14, 12, 8, 9]
dren.')
print(f'I have {len(kidsages)} beautiful children.')
I have 5 beautiful children.
s {sum(kidsages)}.')
print(f'The sum of their ages is {sum(kidsages)}.')
The sum of their ages is 48.
:
print(f'The average age of my children is {statistics.mean(kidsages):.2f}.')
The average age of my children is 9.60.
dian
print(f'The median age of my children is {statistics.median(kidsages)}.')
The median age of my children is 9.
}.')
print(f'Since I have no twins, there is no mode of the ages of my children, but the statics module shows a value of {statistics.mode(kidsages)}.')
Since I have no twins, there is no mode of the ages of my children, but the statics module shows a value of 5.
​
​
