# 📘 Day 27: Testing | HackerRank 30 Days of Code

This repository contains the Python solution for **Day 27** of the **HackerRank 30 Days of Code** challenge, focusing on **unit testing**, test validation, and error handling using custom test data classes.

## 🚀 Challenge Summary

- Write a function `minimum_index(seq)` that returns the index of the minimum value in the list.
  
- If the list is empty, raise a `ValueError`.
  
- Implement 3 test cases using custom data providers to validate different scenarios:
  
  - Empty array
    
  - Array with unique values
    
  - Array with exactly two minimum values

## 📝 Problem Statement

Complete the following:

1. **`minimum_index(seq)`**
   
   Returns the index of the minimum value in the list `seq`.

2. Implement 3 test classes:
   
   - `TestDataEmptyArray`: returns an empty array.
     
   - `TestDataUniqueValues`: returns an array of unique integers and its correct minimum index.
     
   - `TestDataExactlyTwoDifferentMinimums`: returns an array with exactly two minimums and its correct minimum index.

-All test functions should use `assert` statements and raise errors if any logic fails.

## ✅ Constraints

            - The arrays used in test data will have:
              
              - At least 2 elements where required.
                
              - Proper constraints for uniqueness or duplicate minimums.
                
            - The function must raise a `ValueError` for an empty list.

## 🔢 Sample/Internal Test Results

            Input: [2, 3, 1, 4] (unique values)
            
            Output: 2
            
            Input: [1, 2, 1] (exactly two minimums)
            
            Output: 0
            
            Input: [] (empty list)
            
            Output: ValueError raised

## Final Printed Output:

            OK

## 💡 Explanation

- `minimum_index()` goes through the list to find the smallest number and returns its index.
  
- If input list is empty, it throws an exception with a custom error message.
  
- Each of the test data classes implements controlled, predictable test cases to simulate edge cases.

- When all test functions pass without error, output will be:
   
  ✅ `OK`

## 🧠 Concepts Practiced

- ✅ Unit Testing
  
- ✅ Custom Test Data Classes
  
- ✅ Assertion-based Validation
  
- ✅ Exception Handling
  
- ✅ Clean Code Practices
  
- ✅ Defensive Programming

## 🛠 How to Run

Option 1: Run the script directly  

          python3 testing.py

## 🔗 HackerRank Challenge Link

          HackerRank – Day 27: Testing

🏆 Challenge Completed

✅ Problem Solved

🎯 Points Earned: 30

## 📅 Completed On:

           9th June 2025

## 🔖 Tags

#Python #HackerRank #UnitTesting #30DaysOfCode #ProblemSolving #Day27Challenge #Assertions #ExceptionHandling #CleanCode #LearningByDoing

## ✍ Author

            Harsha M
            
            GitHub: @Harshaharika7
        
            LinkedIn: Harsha M
