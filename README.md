# Hacktiv8 Talent Fair Vol. 3 Challenge

> Hacktiv8 Team in collaboration with Kalbe and ARIA Indonesia
---

## Challenge Brief Description

Hacktiv8 Talent Fair specially held for Hacktiv8's Data Science graduates only, which we packed in the format of competition/hackaton. The winner of this Talent Fair will be processed in a `fast-track` manner by the company's judges (Kalbe and ARIA Indonesia).

The open positions at Kalbe are Data Scientist and ARIA Indonesia currently looking for Data Scientist.

There will be other companies that will also come as participants who can see the resumes of projects that you are working on and can immediately enter the recruitment process stage (a Zoom's breakout room will be available during the event).

There will be 2 datasets provided and you have to work on both datasets. Because there are several open positions available, you can work on both datasets and give the judges either data pipeline solutions, machine learning model solutions, or even both.

The Talent Fair Main Event will be held in hybrid manner.

- Event Date: February 24, 2023. 14.00 WIB (GMT + 7)
- Offline Venue: **Campus Hacktiv8 Pondok Indah** - Jl. Arteri Pd. Indah No.7, RT.5/RW.9, Kby. Lama Sel., Kec. Kby. Lama, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12240
- Online Link: **TBA**

All FTDS Programs Alumni are very welcome to take part in the Talent Fair Offline Event.

## Acknowledgments

Dataset in folder `1` provided by Kalbe for forecasting, or any other method you think suits the data well. Dataset in folder `2` provided by ARIA Indonesia for predictive modeling, and any other method you think suits the data well also.

## Dataset Description

### File Description

```txt
datasets
|_ aria_data.csv - dataset from ARIA
|_ kalbe_data.xlsx - dataset from Kalbe

```

You can see sample of the data [here](https://github.com/ardhiraka/talent_fair_sample_challenge/blob/main/sample.ipynb).

### Data Fields

Here's a brief version of what you'll find in the data description file.

`kalbe_data.xlsx`

- **day:** contained information about day on sold product.
- **category:** contained information about product category. There are 2 categories used in this dataset, A and B.
- **product:** contained information about product name. There are 4 products used in this dataset, A1, A2 and B1, B2.
- **sales:** contained information about product sold.

`aria_data.csv`

- **target** contained information to predict plant nutrition
- **V1 - V8** contained information about variable to predict plant nutrition
- **sample_type** contained information about 2 different labs sample obtained

## General Instruction

Download the file needed from [here](https://github.com/ardhiraka/talent_fair_sample_challenge/tree/main/datasets).

Build a model to handle each dataset provided by Hiring Partner. You can explore your own case based on each dataset (you can make time series analysis, forecasting, predictive analysis, etc, it's up to you).

Provide the notebook, and your notebook need to have the following outline:

1. Title <br/>
   Write your project title and short description of your work
2. Introduction <br/>
   Write down your name and your brief description for our Judges
3. External Link <br/>
   Provide the judges with external link needed such as Deployment link, Tableau/Data Studio Link, or any other link
4. Working Area <br/>
   This is where you handle the task
5. Conclusion / Overall Analysis <br/>
   Write your findings, conclusion, and/or overall analysis here.

You can also make dashboard or apps out of the data provided using Tableau, Data Studio, Streamlit, or your own preferred platform.

You can work on either on one of those projects or both.

After finishing your product, **build your deck** to present your solution to the judges with 15 slides max.

## Submission

Submit your **work AND your deck** via this [link](https://bit.ly/submitTalentFair).

## Rubric Overview

### Objective/Expected Result

`kalbe dataset`

1. Able to forecast every products and categories from Kalbe's dataset.
2. Your working model able to reach a good Accuracy Rate.
3. Able to explain the methodology used for every step, algorithm, data manipulation, data cleansing, etc.
4. Able to provide chart or any other measureable methods to prove your inferences.

`aria dataset`

1. Able to create a prediction model of plant nutritional data that has been obtained from the test lab.
2. Able to explore and analyze the datasets.
3. Able to explain how to evaluate the model.
4. Able to explain the methodology used for every step, algorithm, data manipulation, data cleansing, etc.
5. Able to provide further improvement plan.

### Challenge Rubrics

The rubrics below are used to assess both of the Kalbe and ARIA datasets.

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| EDA | Mampu melakukan eksplorasi data dengan menuliskan temuan di setiap langkah yang dilakukan | 5 |
| Modeling 1 | Mampu membuat forecast products hingga 14 hari kedepan dengan akurasi yang cukup bagus | 3 pts |
| Modeling 2 | Mampu membuat forecast categories hingga 14 hari kedepan dengan akurasi yang cukup bagus | 2 pts |
| Modeling 3 | Mampu membuat dan memilih model terbaik untuk prediksi nutrisi tanaman | 5 pts |
| Runs Perfectly 1 | Pengerjaan tugas sebelum dikumpulkan telah dilakukan Restart notebook dan Run All oleh student | 2 pts |
| Runs Perfectly 2 | Pengerjaan tugas dapat dilakukan run ulang untuk mengecek tidak adanya error atau perubahan hasil | 2 pts |
| Readability | Semua baris kode terdokumentasi dengan baik dengan Markdown untuk penjelasan kode | 5 pts |
| Model Analysis 1 | Penggunaan metrics yang tepat terhadap problem yang dihadapi | 3 pts |
| Model Analysis 2 | Penjelasan mengenai performa model yang didapat | 5 pts |
| Model Analysis 3 | Penjelasan mengenai kelebihan dan kekurangan model | 5 pts |
| Model Analysis 4 | Keterkaitan dengan domain business yang dihadapi | 5 pts |
| Overall Analysis 1 | EDA Analysis | 5 pts |
| Overall Analysis 2 | Mampu menjelaskan metodologi pemilihan langkah cleaning dan manipulasi data hingga algoritma | 10 pts |
| Overall Analysis 3 | Adanya further improvement plan | 3 pts |

> Total: 60 Points

## Rules

### Submission Limits

You may submit a maximum of 5 entries per day.

You may select only 1 final submission for judging.

### Competition Timeline

Start Date: February 15, 2023

End Date: February 20, 2023 (12.59 GMT+7)

### Competition-Specific Terms

Competition Title: Hacktiv8 Talent Fair 2023

Data Access and Use: Competition Use and Academic, Non-Commercial Use Only

> We ask that you respect the spirit of the competition and do not cheat. Hand-labeling is forbidden.

ENTRY IN THIS COMPETITION CONSTITUTES YOUR ACCEPTANCE OF THESE OFFICIAL COMPETITION RULES.

The Competition named above is a skills-based competition to promote and further the field of data science. You must register via `Hacktiv8 Career Team` to enter. Your competition submissions ("Submissions") must conform to the requirements stated on the Competition Rules. Your Submissions will be scored by Judges from Hiring Partners (Kalbe and ARIA Indonesia). Subject to compliance with the Competition Rules, Prizes, if any, will be awarded to participants with the best scores, based on the merits of the data science models submitted. See below for the complete Competition Rules.

### Competition-Specific Rules

In addition to the provisions of the General Competition Rules below, you understand and agree to these Competition-Specific Rules required by Hacktiv8:

1. AUTOMATED MACHINE LEARNING TOOLS (AMLT).

Individual participants and Teams may use automated machine learning tool(s) ("AMLT") (e.g., Google AutoML, H2O Driverless AI, etc.) to create a Submission, provided that the participant ensures that they have an appropriate license to the AMLT such that they are able to comply with the Competition Rules.

### General Competition Rules

1. ELIGIBILITY.

   - To be eligible to enter the Competition, you must be: (i) a registered alumni at Hacktiv8 FTDS Program, (ii) registered at Hacktiv8 Career Team, (iii) the older of 18 years old or the age of majority in your jurisdiction of residence.
   - Unless otherwise stated in the Specific Competition Rules above or prohibited by internal policies of the Competition Entities, employees, interns, contractors, officers and directors of Competition Entities may enter and participate in the Competition, but are not eligible to win any Prizes. "Competition Entities" means the Competition Partner, Hacktiv8, and their respective companies, subsidiaries and affiliates. If you are such a participant from a Competition Entity, you are subject to all applicable internal policies of your employer with respect to your participation.

2. COMPETITION PERIOD.<br/>
   For the purposes of Prizes, the Competition will run from the Start Date and time to the Final Submission Deadline (such duration the "Competition Period"). The Competition Timeline is subject to change, and Competition partner may introduce additional hurdle deadlines during the Competition Period. Any updated or additional deadlines will be publicized by Career Team. It is your responsibility to check to Career Team regularly to stay informed of any deadline changes. YOU ARE RESPONSIBLE FOR DETERMINING THE CORRESPONDING TIME ZONE IN YOUR LOCATION.

3. COMPETITION ENTRY. <br/>
   NO PURCHASE NECESSARY TO ENTER OR WIN. To enter the Competition, you must register by Career Team prior to the Entry Deadline, and follow the instructions for developing and entering your Submission. Your Submissions must be made in the manner and format, and in compliance with all other requirements, stated by Career Team (the "Requirements"). Submissions must be received before any Submission deadlines stated by Career Team. Submissions not received by the stated deadlines will not be eligible to receive a Prize.

    Submissions may not use or incorporate information from hand labeling or human prediction of the validation dataset or test data records.

    If the Competition is a multi-stage competition with temporally separate training and/or test data, one or more valid Submissions may be required during each Competition stage in the manner described by Career Team in order for the Submissions to be Prize eligible.

    Submissions are void if they are in whole or part illegible, incomplete, damaged, altered, counterfeit, obtained through fraud, or late. Hacktiv8 reserves the right to disqualify any entrant who does not follow these Rules, including making a Submission that does not meet the Requirements.

4. COMPETITION DATA. <br/>
   "Competition Data" means the data or datasets available provided by Academic Team and Hiring Partner for the purpose of use in the Competition, including any prototype or executable code provided. The Competition Data will contain private and public test sets. Which data belongs to which set will not be made available to participants.

   A. Data Access and Use. You may access and use the Competition Data for non-commercial purposes only, including for participating in the Competition, and for academic research and education. Hacktiv8 reserves the right to disqualify any participant who uses the Competition Data other than as permitted.

   B. Data Security. You agree to use reasonable and suitable measures to prevent persons who have not formally agreed to these Rules from gaining access to the Competition Data. You agree not to transmit, duplicate, publish, redistribute or otherwise provide or make available the Competition Data to any party not participating in the Competition. You agree to notify Hacktiv8 immediately upon learning of any possible unauthorized transmission of or unauthorized access to the Competition Data and agree to work with Hacktiv8 to rectify any unauthorized transmission or access.

    C. External Data. You may use data other than the Competition Data ("External Data") to develop and test your Submissions. However, you will ensure the External Data is publicly available and equally accessible to use by all participants of the Competition for purposes of the competition at no cost to the other participants. The ability to use External Data under this Section 4.C (External Data) does not limit your other obligations under these Competition Rules.

5. SUBMISSION CODE REQUIREMENTS. <br/>
   A. Private Code Sharing. Unless otherwise specifically permitted under the Competition Specific Rules above, during the Competition Period, you are not allowed to privately share source or executable code developed in connection with or based upon the Competition Data or other source or executable code relevant to the Competition ("Competition Code"). This prohibition includes sharing Competition Code between participant. Any such sharing of Competition Code is a breach of these Competition Rules and may result in disqualification.

    B. Public Code Sharing. You are permitted to publicly share Competition Code, provided that such public sharing does not violate the intellectual property rights of any third party. If you do choose to share Competition Code or other such code, you are required to share it on github repo provided. By so sharing, you are deemed to have licensed the shared code under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such Competition Code or model containing or depending on such Competition Code.

    C. Use of Open Source. Unless otherwise stated in the Specific Competition Rules above, if open source code is used in the model to generate the Submission, then you must only use open source code licensed under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such code or model containing or depending on such code.

6. DISQUALIFICATION. <br/>
   Hacktiv8 reserves the right to disqualify any participant from the Competition if Hacktiv8 reasonably believes that the participant has attempted to undermine the legitimate operation of the Competition by cheating, deception, or other unfair playing practices or abuses, threatens or harasses any other participants, or Hacktiv8.

    A disqualified participant may be removed from the Competition.
