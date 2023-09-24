# Lab_challenge2
Python problems for my coding class

--------------------------------------------------------------------------

1. You are given a dictionary named `grades` where keys are student names and values are their respective scores out of 100. Your task is to write a Python script to convert these numerical grades to letter grades according to the following criteria:

- A grade of 90 or above is an 'A'
- A grade of 80 to 89 is a 'B'
- A grade of 70 to 79 is a 'C'
- Any grade below 70 is an 'F'

Your script should store the letter grades in a new dictionary named `letter_grades` with the same keys (student names). Finally, your script should print the `letter_grades` dictionary to the console.

Here's the `grades` dictionary you'll start with:
grades = {'Alice': 85, 'Bob': 60, 'Cathy': 90}
Expected Output:
{'Alice': 'B', 'Bob': 'F', 'Cathy': 'A'}

2. You are running a small grocery store and have an inventory system to track the number of items in stock. Your inventory is represented by a dictionary named inventory, where keys are the item names and values are the respective stock counts. You have just received a list named purchased_items representing items bought by a customer.

Your task is to write a Python script to update the inventory based on the items purchased by the customer. If an item is purchased, decrement the stock count in the inventory. If the stock count of an item goes below 0, update it to 0 as you cannot have negative stock. If a purchased item is not found in the inventory, print a message indicating the item is not in the inventory.

Here are the inventory and purchased_items you'll start with:
inventory = {'Apple': 10, 'Banana': 1, 'Orange': 7}
purchased_items = ['Apple', 'Banana', 'Apple', 'Orange', 'Banana']

Expected Output:
Banana is not in the inventory
{'Apple': 8, 'Banana': 0, 'Orange': 6} 

3. Create a Multiplication Table

You are tasked with creating a program that generates a multiplication table for the numbers 1 through 10. The program should use nested loops to calculate and print the product of each pair of numbers in the range. The output should be formatted as a table, where the rows represent the multiplicands, the columns represent the multipliers, and each cell contains the product of the corresponding pair of numbers.

Your output should look like the following:
     1    2    3    4    5    6    7    8    9    10
1    1    2    3    4    5    6    7    8    9    10   
2    2    4    6    8    10   12   14   16   18   20   
3    3    6    9    12   15   18   21   24   27   30   
4    4    8    12   16   20   24   28   32   36   40   
5    5    10   15   20   25   30   35   40   45   50   
6    6    12   18   24   30   36   42   48   54   60   
7    7    14   21   28   35   42   49   56   63   70   
8    8    16   24   32   40   48   56   64   72   80   
9    9    18   27   36   45   54   63   72   81   90   
10   10   20   30   40   50   60   70   80   90   100   

4. Write a program that takes two lists and returns a list that contains only the elements that are common between the lists (without duplicates). Make sure your program works on two lists of different sizes.

Example Input: [1, 2, 3, 4, 5], [4, 5, 6, 7, 8]
Example Output: [4, 5]



