# Final-exam-task-1 
This Java program processes two lists — one of integers and one of strings — and performs a series of operations:

Combination Step:

Each element of the integer list (list1) is used as an index to access the string list (list2).

A new list (list3) is created where each element is a combination of the string from list2 at the given index and the index itself.

Example: If list1 has value 4, and list2.get(4) is ddb, then the result is ddb4.

Error Handling:

If any value in list1 is greater than or equal to the size of list2, an error message is printed and that value is skipped.

This prevents IndexOutOfBoundsException and ensures program stability.

Filtering Step:

From the combined list (list3), the values that have the coressponding number in list 1 are deleted, however 

there will always be at least one value left.

This results in the final output.

The program is dynamic and will work correctly with any list sizes and values.

If an element in list1 is greater than or equal to the size of list2, it cannot be used as an index,

it skips them, the values that are too big are numbers above 3, and 3 itself. 
![image](https://github.com/user-attachments/assets/89144a53-51ed-483c-8e0d-03a25740fb42)
