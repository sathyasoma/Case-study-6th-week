# Case-study-6th-week

casestudy:
=========
SpringBootDataJpaRest with postman:
==================================

StudentMangaementApplication:
---------------------------------

1. create package struture 
  
      1.1 com.student
	  1.2 com.student.entity 
	  1.3 com.student.service 
	  1.4 com.student.dao 
	  1.5 com.student.controller 




1.1: configuration class by defalut we wil get at the time of project creation.

1.2 com.std.entity

    student details
	    studentId
		studentName
		studentClass
		studentmarks
		studnetSchoolName
		studentAddress


1.3 com.std.service 

	Student addStudent(Student Student);

	Student updateStudent(Student Student);

	String deleteStudent(int empId);

	Student getStudent(int empId);

	List<Student> getAllStudents();

 
1.4 com.std.dao 
	

	Student addStudent(Student Student);

	Student updateStudent(Student Student);

	String deleteStudent(int empId);

	Student getStudent(int empId);

	List<Student> getAllStudents();	
										 
1.5 com.std.controller

    create a controller class with service methods 	 
	 
	 
	 
	 
2. Use POSTMAN TO ENTER THE STUDENT DETAILS  
