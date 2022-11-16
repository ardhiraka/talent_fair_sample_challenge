# Hacktiv8 Talent Fair Vol. 2 Challenge

> Hacktiv8 Team in collaboration with MNC Portal and Sinarmas Land
---

## Challenge Brief Description

Hacktiv8 Talent Fair specially held for Hacktiv8's Data Science graduates only, which we packed in the format of competition/hackaton. The winner of this Talent Fair will be processed in a `fast-track` manner by the company's judges (Sinarmas Land and MNC Portal). The open positions at Sinarmas Land are Data Analyst Intern and MNC Portal currently looking for Data Scientist and Data Engineer.

There will be other companies that will also come as participants who can see the resumes of projects that you are working on and can immediately enter the recruitment process stage (a Zoom's breakout room will be available during the event).

There will be 2 datasets provided and you have to work on both datasets. Because there are several open positions available (DE, DS, DA), you can work on both datasets and give the judges either data pipeline solutions, machine learning model solutions, or even both.

## Acknowledgments

Dataset in folder `1` provided by MNC Portal for content tagging, text classification, and any other method you think suits the data well. Dataset in folder `2` provided by Sinarmas Land for risk modeling, segmentation, and any other method you think suits the data well also.

## Dataset Description

### File Description

```txt
1
|_ Dataset Dictionary.docx - contains columns explanation for final_dataset.csv
|_ final_data.csv - dataset from MNC Portal

2
|_ IndonesiaCreditData.xlsx - dataset from Sinarmas Land (columns explanation included)
```

### Data Fields

Here's a brief version of what you'll find in the data description file.

`final_data.csv`

- **viewers_id:** contained information about viewers_id. There are several ids using UN- and using dynamic number generated
- **content_id:** contained information about content_id. The ids are using dynamic number generated
- **hit_timestamp:** contained information describes the time viewers carry out the process of reading per one article
- **user_type:** describe user type based on registered user and anonymous user or unregistered
- **category_id:** contained information about category_id. The ids are using dynamic number generated
- **tagging:** describe the tagging per content_id
- **creator_id:** describe content owner
- **category_name:** describe the category name
- **viewers_birthdate:** describe the birthdate of viewers
- **viewers_gender:** describe the gender of viewers
- **viewers_region:** describe the region of viewers

`IndonesiaCreditData.xlsx`

- **Age** (numeric)
- **Sex** (text: male  female)
- **Job** (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
- **Housing** (text: own rent or free)
- **Saving accounts** (text - little moderate, quite rich, rich)
- **Checking account** (numeric in DM - IDR)
- **Credit amount** (numeric in IDR)
- **Duration** (numeric in month)
- **Purpose**(text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others
- **Risk** (Value target - Good or Bad Risk)

## General Instruction

Download the file needed from [here](https://drive.google.com/drive/folders/14mi_spce8E45ByC2ugDgjEtJF1VHPaTs?usp=sharing).

### For DE

Build a blueprint for your data pipeline or data flow solutions. You can propose your own database design, ETL schema, warehouse design, scheduler/automation tools, and visualization platform. Present your design and your reasoning behind every tools used.

### For DS or DA

Build a machine learning model to handle each dataset provided by Hiring Partner. You can explore your own case based on each dataset (you can make text classification, tagging, risk model, segmentation, etc, it's up to you).

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

You can also make dashboard out of the data provided using Tableau, Data Studio, or your own preferred platform.

You can work on either on of those projects (DE or DA/DS) or even both. For DE and DA/DS projects, we expect you to build a full data pipeline from the raw data provided, cleaned using ETL you build, and your ML model should consume from your cleaned version of data.

## Submission

Submit your work via this [link](https://bit.ly/submitTalentFair).

## Rules

### Submission Limits

You may submit a maximum of 5 entries per day.

You may select only 1 final submission for judging.

### Competition Timeline

Start Date: November 19, 2022

End Date: November 21, 2022 (15.00 GMT+7)

### Competition-Specific Terms

Competition Title: Hacktiv8 Talent Fair 2022

Data Access and Use: Competition Use and Academic, Non-Commercial Use Only

> We ask that you respect the spirit of the competition and do not cheat. Hand-labeling is forbidden.

ENTRY IN THIS COMPETITION CONSTITUTES YOUR ACCEPTANCE OF THESE OFFICIAL COMPETITION RULES.

The Competition named above is a skills-based competition to promote and further the field of data science. You must register via `Hacktiv8 Career Team` to enter. Your competition submissions ("Submissions") must conform to the requirements stated on the Competition Rules. Your Submissions will be scored by Judges from Hiring Partners (MNC Portal and Sinarmas Land). Subject to compliance with the Competition Rules, Prizes, if any, will be awarded to participants with the best scores, based on the merits of the data science models submitted. See below for the complete Competition Rules.

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
