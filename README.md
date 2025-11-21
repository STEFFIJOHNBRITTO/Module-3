# EX 3
### Name: STEFFI J
### Reg no: 212224220107
# 3a. List Operations in Python: Sum of List Items

## Aim
To write a Python program that calculates the **sum of all elements** in a list.

## Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## Program
```
items=[153,147,124,102]
print(sum(items))
```
## Output

<img width="721" height="203" alt="image" src="https://github.com/user-attachments/assets/e0c8765b-3d6c-40d0-908b-e13c973c09ee" />

## Result

Thus,the Python program that calculates the sum of all elements in a list is created successfully.

 # 3b. Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## Program

```
items=['goal','new','user','sit','eat','dinner']
filtered_items=[item for item in items if 'e' not in item]
print(filtered_items)
```

## Output

<img width="688" height="207" alt="image" src="https://github.com/user-attachments/assets/53f446b5-de80-4618-b229-8faff4c73d62" />

## Result
Thus,the Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is created successfully.

# 3c. Strings-Remove Nth Index Character from a String

## Aim
To write a Python program that accepts a string and removes the character at a specified index.

## Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## Program
```
def remove(s):
    new=s[:3]+s[3+1:]
    print(new)
```
## Output

<img width="763" height="313" alt="image" src="https://github.com/user-attachments/assets/25635af5-1f3b-406a-8a53-81563012572c" />

## Result

Thus the program that accepts a string and removes the character at a specified index has been executed successfully.

# 3d. Strings-Palindrome Check in Python (Without Built-in Functions)

## Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## Program
```
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string =input()
palindrome(string)
```
## Output

<img width="667" height="192" alt="image" src="https://github.com/user-attachments/assets/5e1c5622-fd92-4a66-a758-05a0e23b0185" />

## Result

Thus the program to check whether the string "civic" is a palindrome or not has executed successfully.

# 3e. Tuple in Python: Check Element Existence

## Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## Program
```
t = ("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
print(8 in t)
print('n' in t)
```
## Output

<img width="553" height="192" alt="image" src="https://github.com/user-attachments/assets/90311dc2-724f-41c7-a79e-45895a78271f" />

## Result

Thus the program that checks if the element 'n' and the element 8 exist within a given tuple has been executed successfully.
