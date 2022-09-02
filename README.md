# Investigation-of-No-Show-Medical-Appointment-Dataset

# Table of Contents

Project title
About the Project
Prerequisites
dataset
Credit


# Project title:
Investigation of No-Show Medical Appointment Dataset

# About the project:
This project is an analyis Performed on a dataset gathered from a Medical Aappointments history. 
It's a data from different patient that scheduled an appoinment with the doctor, receives all the instructions, but does not show up on the appointment day.

what could be the cause of their absence?

The purpose of this project is to investigate which of all variable(s) in the dataset could be the reason the patient does not show up on the appointment day.

Investigating your dataset has been the most important approach to before your start your analysis. This will give you an insight on what on how to clean Up Your Data, Identify the Right Questions, Visualize the Data and eventually Use the Data to Answer Your Questions.

In this project, i investigated the dataset called No-Show Appointment

During the cleaning process, the following was carried:

Deleting columns that are not required.
Handling zero values
Checking and droping Null values.
Checking and Removing duplicates.
Changing the format of release date into DateTime format.
Handling columns with pipes
Checking datatype of columns

At the end of Cleaning, analysis and visualisation was perform.

The following are the questions were answered:

What is the basic reasons some patients do not show up on the appointment day?

It could be that most patient do not showup rather scheculed their appointment in towards weekend Probably the patient that do not show up did not recieve SMS also may be patient that do not show up not on scholarsip

Which day of the week do patients scheduled their appoint?

According to the analysis, It was deduced that We have more appointments schecduled in the part of the week(Monday, Tuesday, Wednesday) and less was scheduled towards the week end

What Age group have most Appontments Scheduled?

The Analysis shows Infant in age bracket 0-1 have the highest appointment scheduled. of Adult, Age above 40 are more noticeable

Aside Answering those questions, i also found out that:

There are more patient without scholarships than we have for those with scholarships

There are 88726 patients with Hypertension while 21801 without.

65% of Female and 35% of Male booked appointment respectively

In count, 71840 Female and 38687 Male booked appointment respectively

Of 81 Neighbourhood, Most appointments are booked with the doctors by patient in the JARDIM CAMBURI Neighbourhood

There are more Diabetic patients than we do not have

107167 Alcoholic patients and 3360 Non-alcoholic patient book Appointment with the doctors

Of all scheduled Appointment, Only 35482 patients recieved an SMS while 75045 patients do not

There are more scheduled appoinment in the month of May than the rest of the month

Eventually, Of all scheduled Appointments, Only 88208 (79.8%) patients Showedup while 22319(20.2%) do not

# Dataset:

The dataset we are using is 'Medical appointment no show up' provided by Udacity. This can also be found on kaggle website.

The dataset consist of about 14 variables (characteristics). These are:

1 - PatientId - Identification of a patient
2 - AppointmentID  -Identification of each appointment
3 - Gender - Male or Female . 
4 - ScheduledDay - The day of the actuall appointment, when they have to visit the doctor.
5 - AppointmentDay - The day someone called or registered the appointment, this is before appointment of course.
6 - Age - How old is the patient.
7 - Neighbourhood - Where the appointment takes place.
8 - Scholarship - True of False .
9 - Hipertension - True or False
10 - Diabetes - True or False
11 - Alcoholism -True or False
12 - Handcap -True or False
13 - SMS_received - 1 or more messages sent to the patient.
14- No-show - True or False.

0 represent False
1 reprensents True

Prerequisites for this project:
- Integrated Development Environment (IDE)
- python 3
- Installed python packages
- Dataset

# Dataset:

Find the dataset here https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv&sa=D&ust=1532469042118000

# Credit:
- Stackoverflow
