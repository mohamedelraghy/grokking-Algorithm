# Grokking Algorithm

## Chapter 1 
**Recap**
- binary search is alot faster than simple search
- O(log n) is faster than O(n), but it gets alot faster once the list of items you're searching through grows
- Algorithm speed isn't measured in second 
- Algorithm times are measured in term of growth of an algorithm 
- Algorithm times are written in Big O notaino => EX:- O(n)

---

## chapter 2
**Recap**
- your computer's memory is like a giant set of drawers
- when you want to store multiple elements, use an array or a list 
- whit array, all your elements are stored right next to each other
- with a list, elements are strewn all over, and one element stores the address of the next one.
- Arrays allow fast read
- Lined list allow fast insert and deletes.
- All elements in the array should be the same type (all ints, all doubles, and so on)
---
## chapter 3
**Recap**

- Recursion is when a function calls itself
- Every recursive function has two cases : the **base** case & the **recursive** case
- A stack has two operations : push & pop
- All function calls go onto the call stack 
- The call stack can get very large, which takes up a lot of memory

---

## chapter 4
**Recap**
- D&C works by breaking a problem down into smaller and smaller
pieces. If you’re using D&C on a list, the base case is probably an
empty array or an array with one element.
- If you’re implementing quicksort, choose a random element as the
pivot. The average runtime of quicksort is O(n log n)!
- The constant in Big O notation can matter sometimes. That’s why
quicksort is faster than merge sort.
- The constant almost never matters for simple search versus binary
search, because O(log n) is so much faster than O(n) when your list
gets big.

---
## chapter 5
### hases good for:-
- Modeling relationship from one thing to another thing
- Filtering out duplicates
- Caching/memorizing data instead of making your server do work

