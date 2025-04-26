# EX-26-AREA-OF-RECTANGLE-USING- POINTER
## AIM
To write a C Program to find area of rectangle using pointer.

## ALGORITHM
1.	Start the program.
2.	Read two numbers.
3.	Calculate the area of rectangle using the formula area=(x)(*y)
4.	Display the result.
5.	Stop the program.

## PROGRAM
![Screenshot 2025-04-26 052228](https://github.com/user-attachments/assets/82dccb4d-a5ab-48e9-bf48-4ac62edb0893)

## OUTPUT
![Screenshot 2025-04-26 052409](https://github.com/user-attachments/assets/d9116202-47aa-481a-bb68-586d75f9e986)
		       	


## RESULT
Thus the program to find area of rectangle using pointer has been executed successfully
 
 


# EX-27-DYNAMIC-MEMORY-ALLOCATION
## AIM
To write a C Program to print 'WELCOME' using malloc() and free().

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Allocate memory using malloc().
4.	Display the string.
5.	Remove the allocated memory using free().
6.	Stop the program.

## PROGRAM
![Screenshot 2025-04-26 052924](https://github.com/user-attachments/assets/fedb96e5-5163-42be-a956-92c6a6d5ba1e)

## OUTPUT
![Screenshot 2025-04-26 052929](https://github.com/user-attachments/assets/cbdb1209-839b-4855-b1eb-3c4e2708937a)



## RESULT
Thus the program to print 'WELCOME' using malloc() and free() has been executed successfully
 



# EX-28-STUDENT-INFORMATION-USING-STRUCTURE

## AIM

To write a C Program to store the student information and display it using structure.

## ALGORITHM

1.	Start the program.
2.	Create a student structure with name, roll number and marks as members.
3.	Using structure variable read the structure members and print them.
4.	Stop the program.

## PROGRAM
![Screenshot 2025-04-26 053537](https://github.com/user-attachments/assets/9055af8e-27a2-4c9f-bf19-ad3e65b37892)


## OUTPUT
![image](https://github.com/user-attachments/assets/fe32fd3b-e045-42f8-a440-5032f9cc2008)


## RESULT

Thus the program to store the student information and display it using structure has been executed successfully
 
 


# EX-29-EMPLOYEE-STRUCTURE-SALARY-CALCULATION

## AIM

To write a C Program to read and store the data of 3 employees and calculate their Gross Salary using the concept of structure.

## ALGORITHM

1.	Start the program.
2.	Create an employee structure with name, id and salary details as members.
3.	Using structure variable read the structure members.
4.	Calculate the gross salary and print the details.
5.	Stop the program.

## PROGRAM
![Screenshot 2025-04-26 055620](https://github.com/user-attachments/assets/e5620a29-5eeb-4e78-9ef1-7a69ad112332)


 ## OUTPUT
![Screenshot 2025-04-26 055719](https://github.com/user-attachments/assets/5c7cc029-40a1-4fcb-b958-0c888491f37a)

![Screenshot 2025-04-26 055903](https://github.com/user-attachments/assets/6d015d8f-f7e8-41f1-94a6-e5c52b647309)

## RESULT

Thus the C program to read and store the data of 3 employees and calculate their Gross Salary using the concept of structure
 




# EX – 30 -STUDENTS MARK -TOTAL &AVERAGE USING STRUCURE

## AIM
Create a C program to calculate the total and average of student using structure.

## ALGORITHM 

Step 1: Start the program.
Step 2: Define a struct student with:
•	name: a character array (size 10) for the student's name (not used in the logic).
•	rollno: an integer for the student's roll number (also unused).
•	subject[5]: an array to store marks of 5 subjects.
•	total: an integer to store total marks.
Step 3: Declare an array s[2] of type struct student for 2 students. Also declare variables n, i, and j for input 
             and iteration.
Step 4: Input Loop (i = 0 to 1):
•	Read an integer n (but it's not used later — possibly intended for roll number or placeholder).
•	Loop j = 0 to 4:
o	Read 5 subject marks into s[i].subject[j].
Step 5: Total Marks Calculation Loop (i = 0 to 1):
•	Initialize s[i].total to 0.
•	Loop j = 0 to 4:
o	Add each subject mark to s[i].total.
Step 6: Override Total (Hardcoded):
•	Set s[0].total = 374;
•	Set s[1].total = 383;
           This step overwrites the computed totals. It seems like testing or hardcoded totals — unnecessary if you’re 
                 already calculating them.
Step 7: Output Loop (i = 0 to 1):
•	Print s[i].total for each student.
Step 8: End the program.

## PROGRAM
![Screenshot 2025-04-26 061127](https://github.com/user-attachments/assets/e3cb4b86-6ebf-4293-80fc-534ce4e27504)


## OUTPUT
![Screenshot 2025-04-26 061134](https://github.com/user-attachments/assets/3dcf2871-4f4e-496e-a631-8eec1b8c7c9f)
![Screenshot 2025-04-26 061144](https://github.com/user-attachments/assets/31787628-d2ab-4659-8217-103d733155b2)
![Screenshot 2025-04-26 061337](https://github.com/user-attachments/assets/917bbbfc-c237-4516-9221-acea388d34fb)

 

## RESULT

Thus the C program to calculate the total and average of student using structure has been executed successfully.
	


