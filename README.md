# Investigating-a-DataSet
This project was done to hone my skills in investigating the contents of a dataset and express my findings. I used a dataset called No_show_appointments whose features are described briefly below:

## Introduction
This dataset has information on 110.527 medical appointments in Brazil. The main focus is to know whether certain features play a part in patients showing up for appointments or not.
Below are the features of this dataset:

**PatientId** indicates the id that identifies each patient.

**AppointmentID** indicates the id that identifies each appointment.

**Gender** indicates the patient's gender (Female 'F' or Male 'M').

**ScheduledDay** tells us on what day the patient set up their appointment.

**AppointmentDay** when will the appointment take place.

**Age** tells how old is the patient.

**Neighborhood** indicates the location of the hospital.

**Scholarship** indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

**Hipertension** the patient has hipertension or not.

**Diabetes** the patient is with diabetes or not.

**Alcoholism** the patient consumes alcohol or not.

**Handcap** the patient is handicapped or not and the number of disabillities the have.

**SMS_received** the patient received a SMS or not.

**No-show** Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

Checking the data in this dataset, checking the features to see which I will use in my analysis and which I may end up dropping

The questions, I would like to explore are:
1. Does the waiting period play a part in a patient showing up?
2. Does gender play a part on whether a patient shows up?
3. Does sending an SMS to patients increase the chances of them showing up?
4. Does having a scholarship affect whether a patient shows up?
