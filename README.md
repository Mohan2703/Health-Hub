# 🏥Pharmacy Dispensing Management System || Python Django
<h2><b><i>Before getting into the project go through this README file once.</i></b></h2>

   <p>This is a simple Pharmacy Management System programmed using Python Django. This project has user-friendly functionalities.<br>
   ************************************<br>
   Project has 5 types of users:<br>
      1. Administrator.<br>
      2. Pharmacist.<br>
      3. Doctor.<br>
      4. Clerk/Receptionist.<br>
      5. Patient.</p>

<div>
<img src="https://github.com/Mohan2703/Health-Hub/blob/main/pharmacy-management-system-master/screenshot/login.png" width="400" height="200" />
<img src="https://github.com/Mohan2703/Health-Hub/blob/main/pharmacy-management-system-master/screenshot/admin.png" width="400" height="200" />
<img src="https://github.com/Mohan2703/Health-Hub/blob/main/pharmacy-management-system-master/screenshot/pharmacist.png" width="400" height="200" />
</div>
<div>
<img src="https://github.com/Mohan2703/Health-Hub/blob/main/pharmacy-management-system-master/screenshot/doctor.png" width="400" height="200" />
<img src="https://github.com/Mohan2703/Health-Hub/blob/main/pharmacy-management-system-master/screenshot/receptionist.png" width="400" height="200" />
<img src="https://github.com/Mohan2703/Health-Hub/blob/main/pharmacy-management-system-master/screenshot/patient.png" width="400" height="200" />
</div>

## Run these Commands in terminal
### Step 1
     pip install -r requirements.txt
### Step 2
     python manage.py migrate
### Step 3
     python manage.py runserver
-----------------------------------------------------------------------------------


### Admin Login: 
- Username: admin
- password: 1234  
  
         Administrator Main Features
     - Manage Admissions/Patients
     - Manage System Users
     - Manage Patient's Prescription
     - Manage Medicinal Drugs Categories
     - Manage Medicinal Drugs
     - Manage Stocks
     - Manage Personal Account

### To Create your own Admin/Superuser
#### Run these commands in the terminal.
    python manage.py createsuperuser
Username: admin<br>
Password: 1234<br>

------------------------------------------------------------------------------------
### Patient Login:
- Username: patient
- password: 1234

        Patient Main Features
     - Manage his/her medications
     - Feedback Pharmacist in case of dispensing issue
     - Manage Personal Account

-----------------------------------------------------------------------------------
### Pharmacist Login:
- Username: pharmacist
- password: 1234

        Pharmacist  Main Features
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Patient Feedback messages
     - Manage Personal Account

-------------------------------------------------------------------------------------
### Clerk Login:
- Username: clerk
- password: 1234

        Clerk/Receptionist Main Features
     - Manage Admissions/Patients
     - Manage Personal Account

------------------------------------------------------------------------------------
### Doctor Login:
- Username: doctor
- password: 1234
        
        Doctor Main Features
     - Manage Patient's Prescription
     - Manage Personal Account

-----------------------------------------------------------------------------------

NOTE: When adding a New patient there are some validations in filling the forms...
- For easy filling of forms use fake filler extension in chrome 
- Fake Filler Extension Chrome link:https://chrome.google.com/webstore/detail/fake-filler/bnjjngeaknajbdcgpfkgnonkmififhfo

--------------------------------------------------------------------------------------
# pharmacy-management-system
