# Health-Data-EDA
Exploratory Data Analysis (EDA) for Brazilian Public Hospital Appointment Records


Introduction

This repository contains an exploratory data analysis (EDA) of appointment records for Brazilian public hospitals. The dataset includes various attributes of patients and indicates whether the patients showed up for their scheduled appointments. The primary goal of this analysis is to uncover trends and factors that influence patients' attendance or non-attendance at their appointments. By leveraging descriptive statistics and data visualization, we aim to answer the following question:

What factors are essential for us to know in order to predict whether a patient will attend their scheduled appointment?


Dataset Information

The dataset used in this analysis is sourced from Brazilian public hospitals and contains the following columns:

PatientId: Unique identifier for each patient.
AppointmentID: Unique identifier for each appointment.
Gender: The gender of the patient (Male or Female).
ScheduledDay: The date when the appointment was scheduled.
AppointmentDay: The date of the actual appointment.
Age: The age of the patient
Neighbourhood: The neighbourhood where the hospital is located
Scholarship: Indicates whether the patient is enrolled in the Bolsa Familia welfare program (1 for enrolled, 0 for not enrolled).
Hipertension: Indicates whether the patient has hypertension (1 for yes, 0 for no).
Diabetes: Indicates whether the patient has diabetes (1 for yes, 0 for no).
Alcoholism: Indicates whether the patient has alcoholism (1 for yes, 0 for no).
Handicap: Indicates the level of handicap (0 for no handicap, 1-4 for different levels of handicap).
SMS_received: Indicates whether the patient received an SMS reminder for the appointment (1 for yes, 0 for no).
No-show: Indicates whether the patient showed up for the appointment (Yes if they did not show up, No if they showed up).
Research Questions

In the course of this EDA, we will address the following research questions:

What is the overall attendance rate for appointments in the dataset?
What is the distribution of gender among the patients? Is there a gender-related difference in attendance rates?
How does age impact appointment attendance? Are there age groups more likely to miss appointments?
Do patients with specific medical conditions (hypertension, diabetes, or alcoholism) have different attendance patterns?
Does enrollment in the Bolsa Familia program affect appointment attendance?
Is there any correlation between receiving an SMS reminder and appointment attendance?
Are there specific neighbourhoods or hospital locations associated with higher or lower attendance rates?


Methods

The analysis will be conducted using Python and various libraries such as Pandas, Matplotlib, and Seaborn for data manipulation, visualization, and statistical analysis. Descriptive statistics such as mean, median, and standard deviation will be used to summarize numerical data, while counts and proportions will be used to summarize categorical data. Visualization techniques, including histograms, bar plots, and heatmaps, will be employed to provide visual insights.


Repository Structure

The repository is structured as follows:

data/: Directory containing the dataset CSV file
notebooks: Jupyter notebooks with the step-by-step analysis
README.md: This document provides an overview of the analysis.


Conclusion

Through this exploratory data analysis, we aim to gain insights into the factors that influence patient attendance at Brazilian public hospitals. By answering the research questions and conducting a thorough examination of the dataset, we hope to provide valuable insights that can be used to predict whether a patient will attend their scheduled appointment. The results of this analysis can potentially aid healthcare providers in improving appointment attendance rates and resource allocation.


Disclaimer: The dataset used in this analysis is historical and does not reflect real-time or current data. The insights derived from this analysis are based on the available dataset and should be used for informational purposes only.
