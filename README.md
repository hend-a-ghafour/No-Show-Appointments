# No-Show-Appointments
# Dataset Description:
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
* ***Patientid :*** The identification number of the patient.
* ***AppointmentID:*** The identification number of the appointment _Key Identifier_.
* ***Gender:*** _"M"_ for Male, and _"F"_ for Female.
* ***ScheduleDay:*** Tetells us on what day the patient set up their appointmen
* ***Age:*** The patient's age.
* ***Neighbourhood:*** I’ indicates the location of the hospit
* ***Scholaeship:*** Ip’ indicates whether or not the patient is enro in Brasilian welfare program [Bolsa Família](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Bolsa_Fam%25C3%25ADlia&sa=D&source=editors&ust=1724087817860577&usg=AOvVaw2Q_qcF1o_XPTswzKDAbl1Q) .Where, _Enrolled = 1_ and _Not Enroled = 0_.
* ***Hipertension (HTN):*** Patients with high blood pressure. Where, _True = 1_ and _False = 0_.
* ***Diabetes (DM):*** Patients with high blood sugar levels. Where, _True = 1_ and _False = 0_.
* ***Alcoholism (AUD):*** Alcohol use disorder. Where, _True = 1_ and _False = 0_.
* ***Handcap (HCP):*** an illness, injury, or condition that makes it difficult for someone to do some things that other people do. Where, _True = 1_ and _False = 0_.
* ***SMS_received:*** 1 or more messages sent to the patient. Where, _True = 1_ and _False = 0_.
* ***No-show:*** _ay_ ‘No’ if the patient showed up to their appointment,_and_‘Yes’ if they did not show up.

# Addressed Questions:
1. Do gender differences impact showing up to the appointment?
2. Does the time between the scheduled date and the appointment date impact the likelihood of showing up?
3. Does the patient's age affect their likelihood of attending their appointment?
4. What is the impact of the neighborhood on the level of commitment to showing up for appointments?
5. Is there a relationship between acquiring the Bolsa Família scholarship and the percentage of attendance?
6. Does a diagnosis of hypertension, diabetes, alcoholism, or disability impact the level of appointment attendance?
7. Does receiving messages impact patients' likelihood of attending their appointments?