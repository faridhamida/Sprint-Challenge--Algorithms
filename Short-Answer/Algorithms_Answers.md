#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n),numbers ran once and doesnt change its behavior


b)O(n^2), there's a loop nested insode of an outer loop


c)O(n), recursion is being called on this function because its going to be in a linear pattern

## Exercise II
It will be 2 parameters floor and egg
we could use binary search 
divide up building floor total by 2
check the left side with a loop through each floor see if the egg breaks
if that doesnt break, then move on to the higher floors which would the right side,and see if breaks
if you found the floor that breaks the egg then return the floor breaks on and assume higher floors are included

Run time for this is O(n) because we dont know how many floors there is but if we do know it will be O(logn)


