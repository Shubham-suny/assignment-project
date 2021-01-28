# assignment-project
# Python-Project-by-shubham


**1st Problem statement: 

ANS:

myList=[10,30,50,40]                         
                                                 
total=0                                           

for i in range(0,len(myList)):
    total=total+myList[i]
    
    
print("sum of all elements:",total)  


**2nd Problem statement:
ANS:

thisdict={
    
    1 : "shubham",
    2 : "praful",
    3 : "pallavi",
    4 : "omkar"}

thisdict2={
    
    1:50,
    2:60,
    3:70}
    
    
    
highest=max(thisdict2,key=thisdict2.get)
userid=max(thisdict2.values())
print("highest:",highest,"number:",userid)
        
        
        
        
 **3rd Problem Statement:
 
 ANS:
 
 arr=[0,0,0,1,1,1,0,0,0,1,1,0,1,1,1,1,0,0,1,1]

count=0 
result=0    
 
n=len(arr)

for i in range(0,n):
    if (arr[i]==0):
        count=0
        
    else:
        count+=1
        result=max(result,count)                                
	
print(result)        



**4th Problem Statement:
ANS:

DATABASE STRUCTURE: 
        
        USER

Srno	    Username	  Password
1	     Shubhk1	   Xyza
2	     Prafugs2	   Cvbhy
3	     Pallbyu3	   Dftrb
4	     Labst4	   Bhtrsa
5	     Taken5	   Jatrsd

	                              ADDRESS
SrNo	      Street	      Pincode	   Country	    State	       Phone No
1	      Banglore road   560069	    India	    Karnataka	       6693214587
1	      Wax wagon	      895448          US            Kalifornia	       4425151566
2	      Nanded road     431513	    India	    Maharashtra	       9921359172
3	      Jammu road      469875        India           Hariyana           8975412356
5	      Jalandhar road  897547	    India	    Panjab	       9874561235

After Creating tables:
 JOIN two table:
 
 SELECT Username,Password,Street,Pincode,Country,state,Phone No
 from USER u
 INNER JOIN ADDRESS a ON s.SrNo;
 
 
Update an address of Sr.1 who has two address:
 UPDATE ADDRESS
  SET
    Street= "CV raman road"
  WHERE
      SrNO=1 AND Street="Banglore road";
  
  here is we can change the address of Street as like this we can change or add address. 
 


 

