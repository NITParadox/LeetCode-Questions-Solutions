# explanation of the search algorithm

# Linear search

Linear search is the simplest search algorithm. It is a brute force algorithm that
iterates over all the elements in the list and checks if the element is the one we are
looking for. If the element is found, it returns the index of the element. If the element
is not found, it returns -1.

# Binary search

Binary search is a divide and conquer algorithm. It works on sorted arrays. It
works by repeatedly dividing the search interval in half. Begin with an interval covering
the whole array. If the value of the search key is less than the item in the middle of
the interval, narrow the interval to the lower half. Otherwise narrow it to the upper
half. Repeatedly check until the value is found or the interval is empty.
