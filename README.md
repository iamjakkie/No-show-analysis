# No-show-analysis
Project: Investigation of no-shows dataset
You can find dataset here: [source](https://www.google.com/url?q=https://www.kaggle.com/joniarroba/noshowappointments&sa=D&ust=1532469042118000)


## Overview: this dataset describes medical appointments with 14 associated variables (characteristics). The most important one if the patient show-up or no-show to the appointment.

### Data Dictionary:
- PatientId - unique patient identificator
- AppointmentId - unique appointment identificator
- Gender - patient's gender
- ScheduledDay - the day the appointment has been registered
- AppointmentDay - day of the appointment
- Age - patient's age
- Neighbourhood - Place of the appointment
- Scholarship - check the source
- Hipertension
- Diabetes
- Alcoholism
- Handcap
- SMS_received - whether the patient has received a message
- No-show - crucial factor, determines whether the patient has shown up for the appointment or not

### Goals:

- is there any specific combination of characteristics that might increase the impact on no-shows
- which characteristics have the highest impact on patient showing up for an appointment
- to group patients into groups based on their potiential of showing up for an appointment
- if there is a person who has missed an appointment once - does it affect his/her appointments in the future?



## Conclusions:

### Outcomes
- looks like there is no one simple combination of characteristics which might help us categorise patients into more-likely to not show up for an appointment.
- Out of chosen features a flag indicating having more than one not shown up appointment looks like the one with highest impact


## Next steps:
- prepare statistical analysis
- introduce ML algorithms for classification
- Prepare visualizations