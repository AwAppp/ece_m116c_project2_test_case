### Here are two python scripts to help us test our project 2 for ECE m116c 21F

##### the result.py is for testing the a specific test case. For example, we can test the professor's debug.txt by running

`python3 result.py debug.txt`

##### the case.py is for creating a test case. I make the lines of the test case 1st line of the scripts, so it can be easily changed.

When use these two scripts, I recommend to do

`python3 case.py > test.txt`

to redirect the test case to test.txt, then

`python3 result.py test.txt`

to check the answer, and then run your code

`./memory_driver test.txt 0(or 1, 2)`

check the answer of the result.py and your code to see whether there is a disagreement.



**I did several tests including the test cases provided by professor and test cases generated by the case.py. They are all same with my memory_driver result. However, the scripts may have some bugs that I have not discovered.  But anyway, I want to share these two scripts to make it easier to debug and get the result for my peers. Also, they have some limitations. For example, they can only simulate the replacement behavior of the cache controller but cannot provide what actually is in the cache line. Since I have not finish the bonus part, I will finish the bonus part first and probably update some functionality later. I hope everyone have a good winter break.  :D**