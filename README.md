# Medical-Appointment-No-Shows-Dataset-Analysis

In this notebook, I will use the [Medical Appointment No Shows](https://www.kaggle.com/joniarroba/noshowappointments) dataset. The dataset has more than 100K medical appointments in Brazil through 2016. It focuses on answering whether the patient will show up for his/her appointment or not.

|  Index |     Feature    |                                             Description                                            |
|:-:|:-:|:-:|
|    0   |    PatientID   |                                          ID of the patient                                         |
|    1   |  AppointmentID |                                        ID of the appointment                                       |
|    2   |     Gender     |                                        Male (M) / Female (F)                                       |
|    3   |  ScheduledDay  |                               The date of scheduling the appointment                               |
|    4   | AppointmentDay |                                 The date of the actual appointment                                 |
|    5   |       Age      |                                       The age of the patient                                       |
|    6   |  Neighbourhood |                         The neighbourhood where the appointment takes place                        |
|    7   |   Scholarship  | [Financial Aid](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia) Available ? True (1) / False (0) |
|    8   |  Hipertension  |                   **Hypertesnion** aka high blood pressure ? True (1) / False (0)                  |
|    9   |    Diabetes    |                                   Diabetes ? True (1) / False (0)                                  |
|   10   |    Alcholism   |                                        True (1) / False (0)                                        |
|   11   |     Handcap    |                                 No. of disabilities in the patient                             |
|   12   |  SMS_recieved  |                                        True (1) / False (0)                                        |
| **13** |   **No-show**  |                                      **True (1) / False (0)**                                      |

## Possible Questions ?

I'll try to find answers to the following questions:
* Is the age considered to be a barrier for not showing for appointments? What are these specific ages (Kids, Adults, Old)?
* Are there neighbourhoods that has high percentage of not showing for the appointments ?
* What do the people in Brazil suffer from the most ? Can we improve the medical services for these cases ?
* Is there strong coloration between not attending the appointment and the span between the appointment day and the day where it was scheduled?
* Does being enrolled in the Brazil aid program help families to go their medical appointments more and pay for them ?



To conclude answers for questions we previously asked...
* Q:  Is the age considered to be a barrier for not showing for appointments? What are these specific ages (Kids, Adults, Old)?

**A: The distribution of the ages of those showed and didn't show for the appointments look alike. The most appointment attendees are 10 years old or below. Same age region is the highest for those who didn't show. We believed at beginning that being young and being busy with school might be a problem same for adult and their work. But, this isn't the case here**


* Q: Are there neighbourhoods that has high percentage of not showing for the appointments ?

**A: Although, JARDIM CAMBURI is the highest neighbourhood in the number of total appointments and suprisingly, not the most one in percentage of didn't show cases to the total number, it was SANTOS DUMONT with 28% and SANTA CECILIA with 27%**


* What do the people in Brazil suffer from the most ? Can we improve the medical services for these cases ?

**A: The diseases were asked about in the dataset are Hypertension, Diabetes, Alcoholism, Handicap. Among more than 100K patients in the dataset, about 18.25% suffer from hypertension more than 6.65% for diabetes, 2.8% for alcholism and 2% who suffer from handicaps.**


* Is there strong coloration between not attending the appointment and the span between the appointment day and the day where it was scheduled?

**A: According to this data, No. Scheduling the appointment at the same day doesn't gurantee that patient will show or not**

* Does being enrolled in the Brazil aid program help families to go their medical appointments more and pay for them ?

**A: Indeed 80% of the poor patients who are enrolled in that program showed for their appointments with the doctors.**
