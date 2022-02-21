# Schoolmanagement
---
## screenshots
### Homepage
![homepage snap](https://github.com/yash-g101/SEEDS/blob/main/static/screenshots/dashboard1.png?raw=true)

### Admin Dashboard
![dashboard snap](https://github.com/yash-g101/SEEDS/blob/main/static/screenshots/admin_dashboard.png?raw=true)

### Admin Manage Registrar
![invoice snap](https://github.com/yash-g101/SEEDS/blob/main/static/screenshots/admin_reg_section.png?raw=true)

### Admin Student Section
![doctor_snap](https://github.com/yash-g101/SEEDS/blob/main/static/screenshots/admin_student_section.png?raw=true)

### Registrar Dashboard
![doctor snap](https://github.com/yash-g101/SEEDS/blob/main/static/screenshots/registrar_dashboard.png?raw=true)

### Registrar Student Section 
![doctor snap](https://github.com/yash-g101/SEEDS/blob/main/static/screenshots/registrar_student_section.png?raw=true)

---

## Functions
### Registrar
First the Registrar will apply for job, if he/she gets selected there accounts will be made and approved by the admin, after approval only Registrar can access their dashboard.
Registrar can also publish/announce notice to students regarding fees etc.

## Student
First student will take admission/signup.
When their account is approved by admin, only then the student can access their dashboard.
After account approval by admin the student can view their details on the dashboard.
Students can also be added by Registrar. 

### Admin
First admin will signup for a account.
After login they can see how many student/teacher wants to get job/admission in their school.
They can approve or delete/cancel the request.
They can update any student/registrar details.
Admin can announce notice also.


## Drawbacks
- Anyone can become Admin
- Registrar is not fully functional yet.

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :

``` python -m pip install -r requirements. txt ```


- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in your browser installed on your PC
```
http://127.0.0.1:8000/
```

## Disclaimer
This project is developed for demo purpose and it's not ready to be used in real application.

