
Udemy cousre [JavaScript Algorithms and Data Structures Masterclass](https://www.udemy.com/course/js-algorithms-and-data-structures-masterclass/)

Notes:

- 2. Big O notation
    - Objectives 
        - Motivate the need for something like Big O Notation
        - Describe what Big O Notation is
        - Simplify Big O Expressions
        - Define "time complexity" and "space complexity"
        - Evaluate the time complexity and space complexity of different algorithms using Big O Notation
        - Describe what a logarithm is
    - Big O Notation is a way of comparing algorithms. It compares them by calculating how much memory is needed and how much time it takes to complete. The Big O Notation is often used in identifying how complex a problem is, also known as the problem's complexity class. [wikipedia](https://simple.wikipedia.org/wiki/Big_O_notation#:~:text=From%20Wikipedia%2C%20the%20free%20encyclopedia,as%20the%20problem's%20complexity%20class.)
    - We say that an algorithm is O(f(n)) if the number of simple operatioins the computer has to do is eventually less than a constant times f(n), as n increases.
        - Explanation of (f(n) = n) = a function with an input of `n` has an `=n` output.
        - f(n) could be linear (f(n) = n)
        - f(n) could be quadratic (f(n) = n2)
        - f(n) could be constant (f(n) = 1)
        - f(n) could be something entirely different!
    - Rules of thumb
        1. Arithmetic operrations are constant.
        2. Variable assingment is constant.
        3. Accessing elements in an array (by index) or object (by key) is constant.
        4. In a loop, the complexity is the length of the loop times the complexity of whatever happens inside of the loop.
    - We use big O notation to analyze:
        - **Time Complexity** which is the runtime of an algorithm as the size of the inputs increases.
        - **Space complexity** which is how much additional memory we need to allocate in order to run the code in our algorithm.
        -**Auxiliary space complexity** which refers to space required by the algorithm, not including space taken up by the inputs. (Here we're going to analyze auxiliary space complexity. So we're focusing on what happens inside the algorithm).
    - Rules of thumb about **Auxiliary space complexity** in JS: 
        1. Most primitivea (booleans, numbers, undefined, null) are **constant** space.
        2. Strings require O(n) space (where n is the string length).
        3. Reference types are generally O(n) where n is the length (for arrays) or the number of keys (for objects)
    - What is a logarithm:
        - log(base2)(8) = 3 => 2 in the power of 3. Anyways we're going to ommit the 2 in log(base2)
        - The logarithm of a number roughly measures the number of times you can divide that number by 2 before you get a value that's less than or equal to one.
    - Why we should know about logarithms:
        - Certain searching algorithms have logarithmic time complexity.
        - Efficient sorting algorithms involve logarithms.
        - Recursion sometimes invloves logarithmic space complexity.
    - Recap:
        - To analyze the performance of an algorithm, we use Big O Notation.
        - Big O Notation can give us a high level understanding of the time or space complexity of an algorithm.
        - Big O Notation doesn't care about precision, only about general trends (linear? quadratic? constant?).
        - Time or space complexity (as measured by Big O) depends only on the algorithm, not the hardware used to run the algorithm.
        - Big O Notation is everwhere, so get lots of practice!
    
