# program-89# Sum of digit until it reduces to single digit

# Reading number
number = int(input(&quot;Enter number: &quot;))

# Finding sum
total_sum = 0
step = 1

condition = True

while condition:

while number:
total_sum += number%10
number //= 10

print(&quot;Step-%d Sum: %d&quot; %(step, total_sum))
number = total_sum
total_sum = 0
step += 1
condition = number &gt; 9
Output
Enter number: 99999999999
Step-1 Sum: 99
Step-2 Sum: 18
Step-3 Sum: 9
