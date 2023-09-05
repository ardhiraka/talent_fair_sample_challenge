# Hacktiv8 Talent Fair Vol. 7 Challenge

> Hacktiv8 Team in collaboration with PT Bank Danamon Indonesia Tbk
---

_Archieve of previous Talent Fair can be found in [legacy](https://github.com/ardhiraka/talent_fair_sample_challenge/tree/main/legacy) folder._

## Challenge Brief Description

Hacktiv8 Talent Fair specially held for Hacktiv8's Data Science graduates only, which we packed in the format of competition/hackaton.

There will be other companies that will also come as participants who can see the resumes of projects that you are working on and can immediately enter the recruitment process stage (a Zoom's breakout room will be available during the event).

The Talent Fair Main Event will be held in online manner.

- Event Date: August 18, 2023. 14.00 WIB (GMT + 7)
- Online Link: **TBA**

Only FTDS Programs recent graduates are eligible to take part in the Talent Fair Event.

## Acknowledgments

For this challenge, you can find external open source financial data from `data.gov`, `Kaggle`, or any other open source data provider. You can also use your own data. If possible, please provide the dataset with with base country of **Indonesia**, Asean/India, or others as last choice.

The General theme of the challenge is **Applied Data Science in Banking**. You can choose your own case, but it has to be related to the theme and specific to the **Financial Industry**. You can consult to your buddy about the datasets.

<!-- Dataset in folder `dataset` provided by PT Bank Danamon Indonesia Tbk for analysis, profiling, predictive modelling or any other method you think suits the data well.
 -->

## Dataset Description

### File Description

N/A, you can freely choose your own datasets.

<!-- ```txt
datasets
|_ Application (primary - need to be used)
|_ Installments payment
|_ Credit bureau
|_ Previous application
|_ And etc.
``` -->

<!-- You can see sample of the data [here](https://github.com/ardhiraka/talent_fair_sample_challenge/blob/main/sample.ipynb). -->

### Data Fields

N/A, you can freely choose your own datasets.

<!-- Here's a brief version of what you'll find in the data description file.

- application_{train|test}.csv
  - This is the main table, broken into two files for Train (with TARGET) and Test (without TARGET).
  - Static data for all applications. One row represents one loan in our data sample.

- bureau.csv
  - All client's previous credits provided by other financial institutions that were reported to Credit Bureau (for clients who have a loan in our sample).
  - For every loan in our sample, there are as many rows as number of credits the client had in Credit Bureau before the application date.

- bureau_balance.csv
  - Monthly balances of previous credits in Credit Bureau.
  - This table has one row for each month of history of every previous credit reported to Credit Bureau – i.e the table has (#loans in sample _of relative previous credits_ of months where we have some history observable for the previous credits) rows.

- POS_CASH_balance.csv
  - Monthly balance snapshots of previous POS (point of sales) and cash loans that the applicant had with Home Credit.
  - This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in our sample – i.e. the table has (#loans in sample _of relative previous credits_ of months in which we have some history observable for the previous credits) rows.

- credit_card_balance.csv
  - Monthly balance snapshots of previous credit cards that the applicant has with Home Credit.
  - This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in our sample – i.e. the table has (#loans in sample _of relative previous credit cards_ of months where we have some history observable for the previous credit card) rows.

- previous_application.csv
  - All previous applications for Home Credit loans of clients who have loans in our sample.
  - There is one row for each previous application related to loans in our data sample.

- installments_payments.csv
  - Repayment history for the previously disbursed credits in Home Credit related to the loans in our sample.
  - There is a) one row for every payment that was made plus b) one row each for missed payment.
  - One row is equivalent to one payment of one installment OR one installment corresponding to one payment of one previous Home Credit credit related to loans in our sample.

- HomeCredit_columns_description.csv
  - This file contains descriptions for the columns in the various data files.

![data schema](https://storage.googleapis.com/kaggle-media/competitions/home-credit/home_credit.png) -->

## General Instruction

You can explore your own case based on dataset (you can make time series analysis, forecasting, predictive analysis, etc, it's up to you).

Provide the notebook and dashboard, and your notebook need to have the following outline:

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

You can make dashboard or apps out of the data provided using Tableau, Data Studio, Streamlit, Quicksight, or your own preferred platform.

You **HAVE TO** write your README.md file to explain your project. Your README.md file should have the following outline:

1. Full Name & Batch
2. Dashboard / Deployment Link
3. Project Title
4. Project Description
5. Conclusion

<!-- You can work on either on one of those projects or both. -->

After finishing your product, **build your deck** to present your solution to the judges with 20 slides max and 30 second **elevator pitch**.

## Submission

Submit your **work, deck, AND elevator pitch** via this [link](https://bit.ly/submitTalentFair).

## Rubric Overview

### Objective/Expected Result

1. Able to match the business objective/use case with the data source choosen.
2. Able to do data processing from preparation to execution in order to get champion result (complexity, resource allocation, potential cost, running time, etc).
3. Able to deliver the output interpretation in visualization.
4. Able to do engaging and insightful story-telling in presentation.
5. Able to give potential business impact.

### Challenge Rubrics

The rubrics below are used to assess PT Bank Danamon Indonesia Tbk challenges.

**Main Rubrics**

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Runs Perfectly 1 | Before being submitted, the assignments that were done had to be restarted and Run All by students | 1 pts |
| Runs Perfectly 2 | The execution of the task can be re-run to check for no errors or changes in results | 1 pts |
| Objective | Able to make objectives in accordance with the business case | 5 pts |
| Readability | All lines of code are well documented with Markdown for code explanation | 2 pts |
| Preparation | Able to do Data Preparations | 5 pts |
| EDA | Able to explore data by writing down the findings at each step taken | 5 pts |
| Visualization | Able to create visualizations to support the findings made | 10 pts |
| Story Telling | Able to convey the results of the analysis in a clear and concise manner | 5 pts |
| Overall Analysis 1 | EDA Analysis | 10 pts |
| Overall Analysis 2 | Mable to explain the methodology for selecting cleaning steps and data manipulation to algorithms | 5 pts |
| Overall Analysis 3 | There is a business impact, implementation, and further improvement | 10 pts |

Additional Rubrics such as model performance, model complexity, and model interpretability, deployment, etc will be assessed based on your project.

## Rules

### Submission Limits

You may submit a maximum of 5 entries per day.

You may select only 1 final submission for judging.

### Competition Timeline

Start Date: August 9, 2023

End Date: August 14, 2023 (12.59 GMT+7)

### Competition-Specific Terms

Competition Title: Hacktiv8 Talent Fair 2023

Data Access and Use: Competition Use and Academic, Non-Commercial Use Only

> We ask that you respect the spirit of the competition and do not cheat. Hand-labeling is forbidden.

ENTRY IN THIS COMPETITION CONSTITUTES YOUR ACCEPTANCE OF THESE OFFICIAL COMPETITION RULES.

The Competition named above is a skills-based competition to promote and further the field of data science. You must register via `Hacktiv8 Career Team` to enter. Your competition submissions ("Submissions") must conform to the requirements stated on the Competition Rules. Your Submissions will be scored by Judges from Hiring Partners (PT Bank Danamon Indonesia Tbk). Subject to compliance with the Competition Rules, Prizes, if any, will be awarded to participants with the best scores, based on the merits of the data science models submitted. See below for the complete Competition Rules.

### Competition-Specific Rules

In addition to the provisions of the General Competition Rules below, you understand and agree to these Competition-Specific Rules required by Hacktiv8:

1. AUTOMATED MACHINE LEARNING TOOLS (AMLT).

Individual participants and Teams may use automated machine learning tool(s) ("AMLT") (e.g., Google AutoML, H2O Driverless AI, etc.) to create a Submission, provided that the participant ensures that they have an appropriate license to the AMLT such that they are able to comply with the Competition Rules.

### General Competition Rules

1. ELIGIBILITY.

   - To be eligible to enter the Competition, you must be: (i) a registered student at Hacktiv8 FTDS Program, (ii) registered at Hacktiv8 Career Team, (iii) the older of 18 years old or the age of majority in your jurisdiction of residence.
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
