# Assignment 5

## Topics: Strings and Arrays

* Arrays: ordered lists of items often used for sequential lists
* Strings: sequences of character data.

### Required tasks

**Strings**

- [x] Read String Questions in Interviews.
  - Using a few sentences, describe what you've learned.
    - Strings are immutable so when we add a character to a string, the string is destroyed and re-created.
    - StringBuffer class is mutable
    - The generating all permutations of a given String of size n always results in a O(n!) time
    - Usually topics of string: Reversing, substring, deletion and replacements.
- [ ] Watch [Memoization and Dynamic Programming](https://www.youtube.com/watch?v=P8Xa2BitN3I) video
  - Using a few sentences, describe what you've learned.
- [x] Watch [Anagram Problem Solution](https://www.youtube.com/watch?v=3MwRGPPB4tw) video
  - Using a few sentences, describe what you've learned.
    - Anagram is two strings which have same extract characters, same number of each characters without order matching. Anagram Problem Solution count how many characters we will delete in two string so that they can be anagram.
    The steps are:  
      + Count how many times each character of string apears and store it to a array
      + Sub two array by index (array1[i] - array2[i]) and sum all values we get into a variable.
      + The variable is the number character we need to delete.
**Arrays**

- [x] Read Sorting Algorithms
  - Can you memorize one algorithm? What is it?
    - Quicksort is a divide and conquer algorithm. Quicksort first divides a large array into two smaller sub-arrays: the low elements and the high elements. Quicksort can then recursively sort the sub-arrays.

    The steps are:

      + Pick an element, called a pivot, from the array.
      + Partitioning: reorder the array so that all elements with values less than the pivot come before the pivot, while all elements with values greater than the pivot come after it (equal values can go either way). After this partitioning, the pivot is in its final     position. This is called the partition operation.
      + Recursively apply the above steps to the sub-array of elements with smaller values and separately to the sub-array of elements with   greater values.
      + The base case of the recursion is arrays of size zero or one, which never need to be sorted.

      + The pivot selection and partitioning steps can be done in several different ways; the choice of specific implementation schemes greatly affects the algorithm's performance.
- [x] Watch [Introduction to Sorting](https://www.youtube.com/watch?v=pkkFqlG0Hds) video
  - Using a few sentences, describe what you've learned.
    - Sort is arranging elements in a list or collection in increasing or decreasing order of some property.
    - With the sorted list / collection, the searching element is fast (binary search vs linear search)
    - Sort classification:
      - time complexity
      - space complextiy or memory usage
      - stability
      - internal sort (all records in memory) and external short (all records in storage)
- [ ] Watch [Merge Sort](https://www.youtube.com/watch?v=KF2j-9iSf4Q) video
  - Using a few sentences, describe what you've learned

**Coding**

- [x] Set up `exercism` and complete at least 2 exercises using `exercism submit`.

### Optional tasks

- [ ] Do more tasks on exercism
- [ ] Set up an account on Interviewbit.com and start the [Programming course](https://www.interviewbit.com/courses/programming/)
- [ ] Finish [Time Complexity chapter](https://www.interviewbit.com/courses/programming/topics/time-complexity) in Level 1 of Interviewbit
- [ ] Finish [Arrays chapter]((https://www.interviewbit.com/courses/programming/topics/arrays/)) in Level 2 of Interviewbit
- [ ] Finish [Math chapter](https://www.interviewbit.com/courses/programming/topics/math/) in Level 2 of Interviewbit.

Optional
