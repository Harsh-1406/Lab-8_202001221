# Lab-8_202001221

# Name : Shah Harsh Sudarshan

# SID : 202001221


1. Created a new Eclipse project with name "Lab_8", and within the project created a package name "my_package".

![image](https://user-images.githubusercontent.com/84762507/233316958-2f4d0cf6-7312-43a0-a9f8-a0104aa3498d.png)

2. Created a class with name "Boa" and then added the given code inside it.

![image](https://user-images.githubusercontent.com/84762507/233319176-acf44214-a086-4a95-b06d-02f4b3861de8.png)

3. Then created a JUnit test file for the Boa Class with name BoaTest

![image](https://user-images.githubusercontent.com/84762507/233322793-a39d046f-ecaf-4f7d-ae8b-e04c6ae0f9d5.png)

4. Then modified the setUp method to initialize the variables.

5. Then implemented tests for the given two functions testIsHealthy() and testFitsInCage().

![image](https://user-images.githubusercontent.com/84762507/233327226-a6759c31-9926-405e-9ee7-cc144266de02.png)

It is not necessary to develop tests for both ken and jen objects in order to test the fitsInCage() method because the function is the same for both, and the results of test cases depend only on whether the specified length is greater than, less than, or equal to the actual length of the object.In both situations, the behaviour will be comparable.

6. Then ran the Junit test file and all the tests are passed.There are no red bars in the output.

![image](https://user-images.githubusercontent.com/84762507/233328519-116eaa5f-b4c1-4e83-90b4-0be98f4d471a.png)

It can be seen that 2 out of 2 test cases have been passed.

7. Then added a new method to the Boa class with name lenghtInInches() to get the length in inches. 

![image](https://user-images.githubusercontent.com/84762507/233330844-764e5f32-2e34-4800-ac4d-85c47bd27632.png)

As the length of the Boa is given in feet, to convert it into inches, I had multiplied length with 12 and returned the value.

8.I then created a second test case for this new method and combined the three test cases.

![image](https://user-images.githubusercontent.com/84762507/233332122-49ad0da9-c1c8-4455-a585-046961e4ccc8.png)

As a result, test cases have been created for the specified Boa class, and the necessary Junit test cases have been used to test all three methods.


