# CSharp_Algorithms

A console app demonstrating algorithms of all levels for strings, numbers, arrays, searches, pyramids, and more ...

---

### [Codewars](https://www.codewars.com/)

|Challenge|Description|Code|
|---------|-----------|----|
|[Vasya-Clerk -> Ticket Line](https://www.codewars.com/kata/vasya-clerk/train/csharp)|Determine if the correct change can be given to a line of cinema goers|[Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/CodeWars/Vasya_Clerk.cs)|

---

### [Codility](https://codility.com/programmers/)

####Iterations
|Challenge|Description|Code|
|---------|-----------|----|
|[BinaryGap](https://codility.com/programmers/lessons/1-iterations/)|Determine the longest sequence of zeros in a binary value|[Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/Codility/Iterations/BinaryGap.cs)|

####Arrays
|Challenge|Description|Code|
|---------|-----------|----|
|[CyclicRotation](https://codility.com/programmers/lessons/2-arrays/cyclic_rotation/)|Rotate an array to the right by a given number of steps| [Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/Codility/ArrayLessons/CyclicRotation.cs)|
|[OddOccurrencesInArray](https://codility.com/programmers/lessons/2-arrays/odd_occurrences_in_array/)|Find value that occurs in odd number of elements| [Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/Codility/ArrayLessons/OddOccurrencesInArray.cs) |

####Time Complexity
|Challenge|Description|Code|
|---------|-----------|----|
|[FrogJmp](https://codility.com/programmers/lessons/3-time_complexity/frog_jmp/)| Count minimal number of jumps from position X to Y. | [Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/Codility/TimeComplexity/FrogJmp.cs) |
|[PermMissingElem](https://codility.com/programmers/lessons/3-time_complexity/perm_missing_elem/)| Find the missing element in a given permutation| [Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/Codility/TimeComplexity/PermMissingElem.cs) |
|[TapeEquilibrium](https://codility.com/programmers/lessons/3-time_complexity/tape_equilibrium/)| Minimize the value (A[0] + ... + A[P-1]) - (A[P] + ... + A[N-1]) | [Here](https://github.com/Apollo013/CSharp_Algorithms/blob/master/CSharpAlgorithms/Codility/TimeComplexity/TapeEquilibrium.cs) |

---

### [LeetCode](https://leetcode.com/problemset/algorithms/)
|Context No.|Name|Difficulty|
|-----------|----|-----------|
|389|[Find The Difference](https://leetcode.com/contest/2/problems/find-the-difference/)|Easy|
|390|[Elimination Game](https://leetcode.com/contest/2/problems/elimination-game/)|Medium|

---

###Math / Number Algorithms

| Algorithm | Comment |
| --------- | ------- |
| Fibonacci | Uses ThreadPool, ManualResetEvent & recursion to calculate the fibonacci spiral of 10 numbers |
| Armstrong | Demonstrate 2 ways to determine if a number is an armstrong number (number is equal to the power of all it's digits)
| Factorial | Shows 2 ways to calculate the factorial of a number using a while loop and recursion |
|Mean & Standard Deviation | Uses PLINQ's Aggregate Function to calculate the mean and Standard deviation for a set of numbers |
| Is Prime Number | Algorithm for checking prime numbers |

---

###String Algorithms

| Algorithm | Comment |
| --------- | ------- |
| Dupes | Finds and calculates the number of times a letter is duplicated in a string |
| Reverse | Shows 3 ways to reverse a string using an array, a while loop and recursion |
| Sentence Permutations | Shows an iterative approach to determining word permutations in a sentence |

---

###Search Algorithms

| Algorithm | Comment |
| --------- | ------- |
| Binary | Demonstrates the builtin c# feature and a custom divide and conquer method for performing a binary search|
| Linear | Searches sorted and unsorted lists and outputs the number of lookups it took to complete the process  |

---

###Pyramid Algorithms
#####No 1
         1
        2 2 
       3 3 3 
      4 4 4 4 
     5 5 5 5 5 
    6 6 6 6 6 6 

#####No 2
         1 
        1 2 
       1 2 3 
      1 2 3 4 
     1 2 3 4 5 
    1 2 3 4 5 6 

#####No 3
         * 
        * * 
       * * * 
      * * * * 
     * * * * * 
    * * * * * * 


#####No 4
                1 
              1 2 1 
            1 2 3 2 1 
          1 2 3 4 3 2 1 
        1 2 3 4 5 4 3 2 1 
      1 2 3 4 5 6 5 4 3 2 1 

#####No 5
      1 2 3 4 5 6 5 4 3 2 1 
        1 2 3 4 5 4 3 2 1 
          1 2 3 4 3 2 1 
            1 2 3 2 1 
              1 2 1 
                1 
                
