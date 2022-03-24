# Case-study-6th-week


casestudy:
=========
SpringBootDataJpaRest with postman:
==================================

MobileMangaementApplication:
---------------------------------

1. create package struture 
  
      1.1 com.mobile
	  1.2 com.mobile.entity 
	  1.3 com.mobile.service 
	  1.4 com.mobile.dao 
	  1.5 com.mobile.controller 




1.1: configuration class by defalut we wil get at the time of project creation.

1.2 com.std.entity

    mobile details
	    mobileId
		mobileName
		mobileTYPE
		mobilePrice
		mobileWarenty
		mobileIMEINumber


1.3 com.std.service 

	Mobile addmobile(Mobile mobile);

	Mobile updatemobile(Mobile mobile);

	String deletemobile(int empId);

	mobile getmobile(int empId);

	List<Mobile> getAllmobiles();

 
1.4 com.std.dao 
	

	Mobile addmobile(Mobile mobile);

	Mobile updatemobile(Mobile mobile);

	String deletemobile(int empId);

	mobile getmobile(int empId);

	List<Mobile> getAllmobiles();	
										 
1.5 com.std.controller

    create a controller class with service methods 	 
	 
	 
	 
	 
2. Use POSTMAN TO ENTER THE mobile DETAILS  
