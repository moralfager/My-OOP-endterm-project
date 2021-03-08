# My-OOP-endterm-project
Java application Online Quiz Management System
## How to use
1. You need to run a "index.java"
2. You can choose sign in(for students) or sign up(for admins)
3. If you want to start quiz you need to push sign in
4. And then small fill up the form with your real answers
5. Press save and next, after that you need to read introduction part
6. You have only 10 min for 10 questions, if you completed quiz press submit, and you can see your results and this results already sended to your email from form.
7. For admins you need to push sign in and write login and password.
8. Login: admin, password: admin 
9. After you add new question, update, delete, you can see all result and all questions.
10. If you want to exit from app press the cross on the edge.

## Rights
 * copyright © 2021 all rights reserved 
 * Kuatbekov Zhumakhan and Yessilbaeva Ulana
 * SE-2013
 * Astana IT University
 * Instructor: Beibut Amirgaliyev
## SQL
create table student(id varchar(10),
name varchar(100),
fatherName varchar(100),
motherName varchar(100),
gender varchar(50),
contactNo varchar(10),
email varchar(100),
elevenSchoolName varchar(200),
elevenPercentage varchar(10),
elevenPassoutYear varchar(5),
address varchar(500),
marks varchar(5));


create table student(id varchar(10),
Fname varchar(100),
Lname varchar(100),
gender varchar(50),
contactNo varchar(12),
email varchar(100),
elevenSchoolName varchar(200),
elevenPercentage varchar(10),
elevenPassoutYear varchar(5),
address varchar(500),
marks varchar(5));

select * from question

create table question(
	id varchar(10) not null,
	name varchar(500) not null,
	opt1 varchar(500) not null,
	opt2 varchar(500) not null,
	opt3 varchar(500) not null,
	opt4 varchar(500) not null,
	answer varchar(500) not null
)

drop table question
