- 👋 Hi, I’m @ugonna05
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ugonna05/ugonna05 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Please I need help with this
Part 1

Encapsulate the following Python code from Section 7.5 in a function named my_sqrt that takes a as a parameter, chooses a starting value for x, and returns an estimate of the square root of a. 

while True:
     y = (x + a/x) / 2.0
     if y == x:
          break
     x = y 


Part 2

Write a function named test_sqrt that prints a table like the following using a while loop, where "diff" is the absolute value of the difference between my_sqrt(a) and math.sqrt(a). 

a = 1 | my_sqrt(a) = 1 | math.sqrt(a) = 1.0 | diff = 0.0
a = 2 | my_sqrt(a) = 1.41421356237 | math.sqrt(a) = 1.41421356237 | diff = 2.22044604925e-16
a = 3 | my_sqrt(a) = 1.73205080757 | math.sqrt(a) = 1.73205080757 | diff = 0.0
a = 4 | my_sqrt(a) = 2.0 | math.sqrt(a) = 2.0 | diff = 0.0
a = 5 | my_sqrt(a) = 2.2360679775 | math.sqrt(a) = 2.2360679775 | diff = 0.0
a = 6 | my_sqrt(a) = 2.44948974278 | math.sqrt(a) = 2.44948974278 | diff = 0.0
a = 7 | my_sqrt(a) = 2.64575131106 | math.sqrt(a) = 2.64575131106 | diff = 0.0
a = 8 | my_sqrt(a) = 2.82842712475 | math.sqrt(a) = 2.82842712475 | diff = 4.4408920985e-16
a = 9 | my_sqrt(a) = 3.0 | math.sqrt(a) = 3.0 | diff = 0.0
