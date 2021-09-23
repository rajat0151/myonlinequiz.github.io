# myonlinequiz.github.io

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## SCREENSHOTS

HOMEPAGE
![homepage](https://user-images.githubusercontent.com/76437557/134473542-752e1ae0-99c3-450c-9846-f5957ff163bc.png)

TEACHER(ADMIN) DASHBOARD
![adminhomepage](https://user-images.githubusercontent.com/76437557/134473624-65569306-672a-4b8e-b3a5-5021a2dda39b.png)

STUDENT DASHBOARD
![studenthomepage](https://user-images.githubusercontent.com/76437557/134473693-6c3f8060-9c5e-4119-ac98-ca8edf5c1622.png)

EXAM RULES PAGE
![rules](https://user-images.githubusercontent.com/76437557/134473734-7ea20191-c574-460b-bae0-4f21bacc4f45.png)

MAIN EXAM PAGE
![exam](https://user-images.githubusercontent.com/76437557/134473769-79c3726c-f1af-40ac-9087-60cccffbf0f4.png)

## Functions

### Teacher
- Create Teacher(Admin) account using command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Student
- Create account (No Approval Required By Teacher(Admin), Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
---

## FOR DEMO-USE TEACHER
- rajat(username)
- 12345(password)

## FOR DEMO-USE STUDENT
- sachin(username)
- 12345(password)
