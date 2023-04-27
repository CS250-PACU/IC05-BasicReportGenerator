# IC05-BasicReportGenerator

For the activity, you will create a new class to read an unknown number of Hourly and Salaried employees into a vector of Employee *. The class will dynamically allocate objects of the appropriate type to be placed into the vector.

1. Create a class called ReportGenerator. This class will have a private data member that is a vector of Employeee *.
2. Create a constructor. The constructor accepts an istream reference to a file that has already been opened. Fill the vector with the employees found in the file. Remember that employees are of one of two forms:
<pre>
H Smith 123456789 22.5 40
S Jones 987654321 10000.00
</pre>
3. Add a destructor that cleans up the vector of dynamically allocated memory.
4. Add a function that will return the total number of employees in the company.
5. Add a function that will return the company’s total monthly payroll, which is the sum of the salaries.
6. Add a function that will display all the employees to the screen.
7. Modify the code in main so that it calls the functions above.

Follow the UML diagram attached here.
