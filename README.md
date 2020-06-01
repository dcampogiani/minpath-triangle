# Minimum / Maximum triangle paths

I saw [this repo](https://github.com/azanin/minpath-triangle) from my friend [azanin](http://azanin.github.io/), and I've tried to implement it in Kotlin.

My implementation may not be the best, but I wanted to build my data structure from a text file, and then traverse it to find the desired value.

Taken directly from his README.md:

    *Consider the following triangle of numbers*
    
```
    7
   6 3
  3 8 5
11 2 10 9
```
    
    *A path through the triangle is a sequence of adjacent nodes, one from each row, starting from the top. So, for instance,
     7 → 6 → 3 → 11 is a path down the left-hand edge of the triangle.
     A minimal path is defined as one whose sum of values in its nodes is no greater than for any other
      path through the triangle.
      In this case, 7+6+3+2 = 18 is the minimal path.*
      
 ### Run Tests
 `./gradlew test`
 
 ### Run application
 `./gradlew run`
