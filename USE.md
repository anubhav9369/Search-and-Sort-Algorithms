# How to Use:
Clone the repository:
git clone https://github.com/anubhav9369/Search-and-Sort-Algorithms.git
cd Search-and-Sort-Algorithms

# Run the script and test the search functions:
python search_sort.py

# Example usage 
# Searching
search_obj = Search()
arr = [10, 20, 30, 40, 50]
print(search_obj.linear_search(arr, 30))  # Output: 2

# Sorting
sort_obj = Sort([5, 3, 8, 1, 2])
sorted_arr = sort_obj.insertion_sort()
print(sorted_arr)  # Output: [1, 2, 3, 5, 8]
