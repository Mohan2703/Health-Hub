# 🏥Pharmacy Dispensing Management System || Python Django
<h2><b><i>Before getting into the project go through README file once.</i></b></h2>

   <p>This is a simple Pharmacy Management System programmed using Python Django. <br>
      The system has 5 types of users :<br>
      1. Administrator,<br>
      2. Pharmacist,<br>
      3. Doctor,<br>
      4. Clerk,<br>
      5. Patient.<br>
      This project has user-friendly functionalities.</p>

<div> <img src="https://github.com/devhasibulislam/pharmacy-management-system/blob/master/screenshot/Admin%20Login.png" width="400" height="200" />
<img src="https://github.com/devhasibulislam/pharmacy-management-system/blob/master/screenshot/Pharmacist.png" width="400" height="200" />
</div>
<div> <img src="https://github.com/devhasibulislam/pharmacy-management-system/blob/master/screenshot/Doctor%20Login.png" width="400" height="200" />
<img src="https://github.com/devhasibulislam/pharmacy-management-system/blob/master/screenshot/Receptionist%20Login.png" width="400" height="200" />
    <img src="https://github.com/devhasibulislam/pharmacy-management-system/blob/master/screenshot/Patient%20login.png" width="400" height="200" />
</div>

## Run these Commads
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
  
### Administrator Main Features
     - Manage Admissions/Patients
     - Manage System Users
     - Manage Patient's Prescription
     - Manage Medicinal Drugs Categories
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Personal Account

### To Create own Admin/Superuser
#### run these commands in terminal.
    python manage.py createsuperuser
Username : admin<br>
Password : 1234<br>

------------------------------------------------------------------------------------
### Patient Login:
- Username: patient
- password: 1234

        Patient Main Featues
     - Manage his/her medications
     - Feedback Pharmacist incase of dispensing issue
     - Manage Personal Account
      
 
-----------------------------------------------------------------------------------
### Pharmacist Login:
- Username: pharmacist
- password: 1234

        Pharmacist  Main Features
     - Manage Medicinal Drugs
     - Manage Stocks
     - Dispense Medicinal Drug
     - Manage Patient Feedback messeges
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
        
        Doctor Main Featues
     - Manage Patient's Prescription
     - Manage Personal Account
   
-----------------------------------------------------------------------------------

N/B: When adding New patient there are some validations in filling the forms 
     For easy filling of forms use fake filler extension in chrome 
     Fake Filler Extension Chrome link:https://chrome.google.com/webstore/detail/fake-filler/bnjjngeaknajbdcgpfkgnonkmififhfo

--------------------------------------------------------------------------------------
# pharmacy-management-system-main
