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
