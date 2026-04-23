Description 

This program calculates a happiness score based on whether elements of an input array belong to two predefined sets called happy and unhappy sets. The program first reads input values representing the number of elements and the size of the sets (though they are not directly required for computation). It then reads the main array of elements and two additional collections representing the happy and unhappy sets. The logic is simple: if an element from the array exists in the happy set, the happiness score increases by +1; if the element exists in the unhappy set, the score decreases by −1; otherwise, the score remains unchanged. The program uses dictionary-based membership checking to efficiently determine whether each element belongs to either set. A list comprehension is used to iterate through the array and compute the score in a compact and readable way. Finally, the total happiness score is printed as output. This implementation is efficient because dictionary membership checking takes constant time, making the solution scalable for larger inputs. The approach avoids nested loops and uses optimized Python data structures for faster lookup operations.

Algorithm

Step 1: Read input values (array size and set sizes).
Step 2: Read array elements into a list.
Step 3: Read happy set elements.
Step 4: Read unhappy set elements.
Step 5: Initialize score = 0.
Step 6: For each element in array:

if element in happy set → add +1
if element in unhappy set → subtract −1
else → add 0
Step 7: Print final happiness score.
