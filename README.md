# **No Shows Appointment Data Exploration**

### BY: CHARITY DIOH

### **Dataset**
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

Here is a list of all column names on this dataset
Client ID, Appoinment ID, Gender, Scheduled day, Appointment Day, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Hipertension, Alcoholism, Handicap, SMS_received, No-show.

This dataset can be found on kaggle https://www.kaggle.com/datasets/joniarroba/noshowappointments

Before I started the exploration process, I did some data wrangling which involves; dropping columns which were not relevant to my analysis, renaming cloumns and fixing datatypes.

### **Summary of Findings**
In the exploration, I found that there was a strong relationship between Handicap, SMS Received, and Scholarship. Most persons did not receive the sms (more than 50% of the population). Less than 20% of the patient population were handicapped with 2 or more disabilities. More than 75% of the population are not beneficiaries of the Bolsa Familia scholarship program. Those with 2 disabilities received more sms, yet did not show up for their appointment. This is due to the fact that more than 70% of the level 2 population (those with 2 disabilities) are not beneficiaries of the scholarship. Patients with 3 or 4 disabilities also are not even beneficiaries of the scholarship program.  

In order to be eligible for the bolsa scholarship program, parents must ensure children attend school and get vaccinated. but for this people with more than 2 disabilities propbably could not even go to school because of their condition, hence making them not to be part of the scholarship program, this in turn deter them from showing up for their appointments.

Outside the main viariables of interest, I verified the relationship between Alcoholism, Hypertension and Diabetes. From the analysis, i could see that there was an interesting relationship between these variables and Age, the patient population above the age of 40, have a lot patients suffering from hypertension and diabetes, and also most of them were alcoholics. 
 

### **Key Insights for Presentation**

For the presentation, I focused on the influence of Scholarship, SMS Received, Handicap and Age. I started by introducing the No-show variable, plotted it on a barchart to show the distribution of patients that showed up and those that did not ahow up for their appointment. Then i filtered the dataset due to the fact that my interest lies in the patient population that did not show up for their appointment.

Afterwards I introduced each of these variables one by one. To start, I used a histogram to show their various distributions. I then explored further by looking at the pairwise and multivariate relationship between these variables
