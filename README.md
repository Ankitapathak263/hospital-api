
  # Hospital Rest-API
## Description
 We’re going to design an API for the doctors of a Hospital which has been allocated by the
govt for testing and quarantine + well being of COVID-19 patients
- There can be 2 types of Users
- Doctors
- Patients
- Doctors can log in
- Each time a patient visits, the doctor will follow 2 steps
- Register the patient in the app (using phone    number, if the patient already exists, just
return the patient info in the API)
- After the checkup, create a Report
- Patient Report will have the following fields
- Created by doctor
- Status (patient status like:- fever , malaria etc):

The Routes here used in project
- /doctors/register → with username and password
- /doctors/login → returns the JWT to be used
- /patients/register
- /patients/:id/create-report
- /patients/:id/all_reports → List all the reports of a patient oldest to latest
- /reports/:status → List all the reports of all the patients filtered by a specific status
  
## Tech stack
 Node.js , Express , Mongo-DB , passport-JWT
 
 # ScreenShot- ![Screenshot (53)](https://github.com/Ankitapathak263/hospital-api/assets/73652228/12dac8c9-8a98-4559-9c7f-d79cdeffeb7a)
![Screenshot (54)](https://github.com/Ankitapathak263/hospital-api/assets/73652228/ad480cde-4f04-45e9-ad29-50bad98b9829)
![Screenshot (55)](https://github.com/Ankitapathak263/hospital-api/assets/73652228/0db07d38-0634-4d8c-9b16-4b5278dd05d2)
![Screenshot (56)](https://github.com/Ankitapathak263/hospital-api/assets/73652228/36998cf2-bb94-49ea-a57b-6378747b18b2)
![Screenshot (57)](https://github.com/Ankitapathak263/hospital-api/assets/73652228/4a7658f8-1bc9-49da-9ea2-21dbf3de5ff1)
![Screenshot (58)](https://github.com/Ankitapathak263/hospital-api/assets/73652228/ef420f23-97e2-438d-8ac9-a902460102eb)

  
