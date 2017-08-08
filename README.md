# Big O Assessment

 ### O Boy! It's time to evaluate your understanding of Big O Notation!

 ##

  PART ONE: Please answer the following questions:

 1. Describe the purpose of Big 0.

    > The purpose of Big O is to estimate the efficiency of a particular algorithm.

---


 2. What 2 things does it measure?

    > time (speed of algorithm) and space (memory footprint of algorithm)

---


 3. Which of the following shows Big O time complexity in order?

    a) O(1), O(n log n), O(log n), O(n), O(n^2)

    b) O(1), O(log n), O(n), O(n log n), O(n^2)

    c) O(1), O(log n), O(n log n), O(n), O(n^2)

    > b

---



4. Which of these algorithm(s) run in O(log n) time?

   Binary Search

   Bubble Sort

   Quick Sort (average case)

   Linear Search

   > binary search

---



5. Select the best time complexity that even the most efficient sort algorithm can have.

    O(log n)

    O(n log n)

    O(n)

    O(n^2)

    > O(log n)

---


 6. Describe what sets these these 3 complexities apart from each other: O(1), O(n) and O(n^2)

    > O(1) is a constant time algorithm. It runs at same speed regardless of inputs. O(n) is linear time algorithm. It takes longer as inputs increase, but at a linear rate. O(n^2) is an exponential time algorithm, where the speed changes as an exponential function of the inputs.

---


7. How would you recognize O(log n) and O(n log n) time complexities in a function?

    > a log n function would decrease number of possible cases each time the loop ran by half.

    > n log n would be like that, but have an added linear function included.

---

  ##

  PART TWO: In a new file, write examples of algorithms/functions for each of the Big O complexities below.
    Upload your file to your repository when complete and submit in Learn --> Exercises.

    1. O(1)

    function doSomething(){
      for(let i = 0; i < 25; i++){
        console.log(i);
      }
    }

    2. O(n)

    function doSomethingElse(array){
      for(let i = 0; i < array.length; i++){
        console.log(array[i]);
      }
    }

    3. O(n^2)

    function doSomethingElser(array){
      for(let i = 0; i < array.length; i++){
        for(let j = i; j < array.length; j++){
          if(array[i] > array[j]){
            console.log(array[i]);
          }
        }
      }
    }
