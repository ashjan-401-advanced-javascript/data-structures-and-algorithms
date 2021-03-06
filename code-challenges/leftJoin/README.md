# Left Join

# Challenge Summary

Write a function that LEFT JOINs two hashmaps into a single data structure.

## Challenge Description

The first parameter is a hashmap that has word strings as keys, and a synonym of the key as values.
The second parameter is a hashmap that has word strings as keys, and antonyms of the key as values.
Combine the key and corresponding values (if they exist) into a new data structure according to LEFT JOIN logic.

## Approach & Efficiency

LEFT JOIN means all the values in the first hashmap are returned, and if values exist in the “right” hashmap, they are appended to the result row. If no values exist in the right hashmap, then a value of NULL should be appended to the result row.
The returned data structure that holds the results is an array. 

## Solution

![](../../assets/leftjoin.JPG)
