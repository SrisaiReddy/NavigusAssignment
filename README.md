# My NavigusAssignment

# Online Quiz
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Srisai%20Reddy-red)
## Functions
### Admin
- First it is mandatory to Create Admin account.
- You have to navigate to the location of this unzipped file through command prompt. 
- Once you are at the file location, Use the following command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Teacher
- Apply for job in System. Then Login (Approval required by system admin, Then only teacher can login).
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Student
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.

> **_NOTE:_** Teacher Profile has to be approved from the Admin, wheareas Student profile doesn't need any approval.
---


## CHANGES REQUIRED FOR CONTACT US PAGE
- In settings.py file, You have to modify your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```

## Drawbacks/LoopHoles
- Admin/Teacher can add any number of questions to any course, But while adding course, admin provide question number.

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python, else it has to done manually)
- Download This Project Zip Folder and Extract it
- Open Terminal, navigate to the file location and Execute Following Commands :
```
python -m pip install -r requirements.txt
```
- Once the required packages are installed, we are ready to migrate the changes and run the server
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
## screenshots
### Homepage
![homepage snap](https://github.com/SrisaiReddy/NavigusAssignment/blob/main/static/screenshots/Screenshot%20(3).png?raw=true)
### Admin DashBoard
![dashboard snap](https://github.com/SrisaiReddy/NavigusAssignment/blob/main/static/screenshots/Screenshot%20(4).png?raw=true)
---
