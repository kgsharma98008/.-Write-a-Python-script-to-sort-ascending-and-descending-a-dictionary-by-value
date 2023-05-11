# .-Write-a-Python-script-to-sort-ascending-and-descending-a-dictionary-by-value

# Sample dictionary
my_dict = {'apple': 3, 'banana': 1, 'orange': 2, 'pear': 4}
# Sort dictionary by value in ascending order
sorted_dict = dict(sorted(my_dict.items(), key=lambda x: x[1]))
print(sorted_dict)
# Sort dictionary by value in descending order
sorted_dict = dict(sorted(my_dict.items(), key=lambda x: x[1], reverse=True))
print(sorted_dict)
