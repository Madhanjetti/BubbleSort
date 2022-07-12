# BubbleSort in C:
Bubble Sort is a simple sorting algorithm which repeatedly compares the adjacent elements of the given array & swaps them if they are in wrong order.
Suppose we have an array X which contains n elements which needs to be sorted using Bubble Sort. The sorting works as:

Pass 1:

 X[0] & X[1] are compared, and swapped if X[0] > X[1]
 X[1] & X[2] are compared, and swapped if X[1] > X[2]
 X[2] & X[3] are compared, and swapped if X[2] > X[3] and so on…
At the end of pass 1, the largest element of the list is placed at the highest index of the list.

Pass 2:

X[0] & X[1] are compared, and swapped if X[0] > X[1]
X[1] & X[2] are compared, and swapped if X[1] > X[2]
X[2] & X[3] are compared, and swapped if X[2] > X[3] and so on…
At the end of Pass 2 the second largest element of the list is placed at the second highest index of the list.

Pass n-1:

X[0] & X[1] are compared, and swapped if X[0] > X[1]
X[1] & X[2] are compared, and swapped if X[1] > X[2]
X[2] & X[3] are compared, and swapped if X[2] > X[3] and so on…
At the end of this pass. The smallest element of the list is placed at the first index of the list.
