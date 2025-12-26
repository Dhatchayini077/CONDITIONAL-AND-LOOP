# CONDITIONAL-AND-LOOP
course=input("enter course name:")
print("\nenter marks out of 100:\n")
s1=int(input("language:"))
s2=int(input("english:"))
s3=int(input("java:"))
s4=int(input("operating system:"))
s5=int(input("computer networks:"))


total=s1+s2+s3+s4+s5
percentage=total/5
if percentage >=90:
    grade ="A+"
elif percentage>=80:
    grade="A"
elif percentage>=70:
    grade="B+"
elif percentage>=60:
    grade="B"
elif percentage>=50:
    grade="C"
else:
    grade="fail"

print("\n==========STUDENT MARKSHEET==========")
print("name :",name)
print("roll number:",roll)
print("course :", course)
print("-------------------------------------")
print("language:",s1)
print("english:",s2)
print("java:",s3)
print("operating system:",s4)
print("computer networks:",s5)
print("-------------------------------------")
print("total marks:",total)
print("percentage:",percentage,"%")
print("grade :",grade)
print("=============================================")

Output:
enter student name:dhatchayini
enter roll number:23
enter course name:computer science

enter marks out of 100:

language:90
english:85
java:80
operating system:79
computer networks:82

==========STUDENT MARKSHEET==========
name : narmatha
roll number: 23
course : computer science
-------------------------------------
language: 90
english: 85
java: 80
operating system: 79
computer networks: 82
-------------------------------------
total marks: 416
percentage: 83.2 %
grade : A
