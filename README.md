# Hacktiv8 Talent Fair Sample Test

> Hacktiv8 Academic Team
---

## Test Brief Description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Practice Skills

- Creative feature engineering
- Advanced regression techniques like random forest and gradient boosting

## Acknowledgments

The [Ames Housing dataset](http://jse.amstat.org/v19n3/decock.pdf) was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

## Dataset Description

### File descriptions

- train.csv - the training set
- test.csv - the test set
- data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
- sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

### Data fields

Here's a brief version of what you'll find in the data description file.

- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration
- LandSlope: Slope of property
- Neighborhood: Physical locations within Ames city limits
- Condition1: Proximity to main road or railroad
- Condition2: Proximity to main road or railroad (if a second is present)
- BldgType: Type of dwelling
- HouseStyle: Style of dwelling
- OverallQual: Overall material and finish quality
- OverallCond: Overall condition rating
- YearBuilt: Original construction date
- YearRemodAdd: Remodel date
- RoofStyle: Type of roof
- RoofMatl: Roof material
- Exterior1st: Exterior covering on house
- Exterior2nd: Exterior covering on house (if more than one material)
- MasVnrType: Masonry veneer type
- MasVnrArea: Masonry veneer area in square feet
- ExterQual: Exterior material quality
- ExterCond: Present condition of the material on the exterior
- Foundation: Type of foundation
- BsmtQual: Height of the basement
- BsmtCond: General condition of the basement
- BsmtExposure: Walkout or garden level basement walls
- BsmtFinType1: Quality of basement finished area
- BsmtFinSF1: Type 1 finished square feet
- BsmtFinType2: Quality of second finished area (if present)
- BsmtFinSF2: Type 2 finished square feet
- BsmtUnfSF: Unfinished square feet of basement area
- TotalBsmtSF: Total square feet of basement area
- Heating: Type of heating
- HeatingQC: Heating quality and condition
- CentralAir: Central air conditioning
- Electrical: Electrical system
- 1stFlrSF: First Floor square feet
- 2ndFlrSF: Second floor square feet
- LowQualFinSF: Low quality finished square feet (all floors)
- GrLivArea: Above grade (ground) living area square feet
- BsmtFullBath: Basement full bathrooms
- BsmtHalfBath: Basement half bathrooms
- FullBath: Full bathrooms above grade
- HalfBath: Half baths above grade
- Bedroom: Number of bedrooms above basement level
- Kitchen: Number of kitchens
- KitchenQual: Kitchen quality
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
- Functional: Home functionality rating
- Fireplaces: Number of fireplaces
- FireplaceQu: Fireplace quality
- GarageType: Garage location
- GarageYrBlt: Year garage was built
- GarageFinish: Interior finish of the garage
- GarageCars: Size of garage in car capacity
- GarageArea: Size of garage in square feet
- GarageQual: Garage quality
- GarageCond: Garage condition
- PavedDrive: Paved driveway
- WoodDeckSF: Wood deck area in square feet
- OpenPorchSF: Open porch area in square feet
- EnclosedPorch: Enclosed porch area in square feet
- 3SsnPorch: Three season porch area in square feet
- ScreenPorch: Screen porch area in square feet
- PoolArea: Pool area in square feet
- PoolQC: Pool quality
- Fence: Fence quality
- MiscFeature: Miscellaneous feature not covered in other categories
- MiscVal: $Value of miscellaneous feature
- MoSold: Month Sold
- YrSold: Year Sold
- SaleType: Type of sale
- SaleCondition: Condition of sale

## General Instruction

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable.

Make dashboard out of the data provided using Tableau, Data Studio, or your own preferred platform.

Building your ETL/data preparation flow with scheduler such as Airflow or Luigi will be the plus point.

Any use of Postgresql, Elasticsearch and Kibana will be the plus point.

Your notebook need to have the following outline:

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

## Submission

Submit your work via this [link](https://bit.ly/submitTalentFair).

## Rules

### Submission Limits

You may submit a maximum of 5 entries per day.

You may select only 1 final submission for judging.

### Competition Timeline

Start Date:

End Date:

### Competition-Specific Terms

Competition Title: Hacktiv8 Talent Fair 2022

Data Access and Use: Competition Use and Academic, Non-Commercial Use Only

> We ask that you respect the spirit of the competition and do not cheat. Hand-labeling is forbidden.

ENTRY IN THIS COMPETITION CONSTITUTES YOUR ACCEPTANCE OF THESE OFFICIAL COMPETITION RULES.

The Competition named above is a skills-based competition to promote and further the field of data science. You must register via `Hacktiv8 Career Team` to enter. Your competition submissions ("Submissions") must conform to the requirements stated on the Competition Rules. Your Submissions will be scored based on the evaluation metric described on the Competition Rules. Subject to compliance with the Competition Rules, Prizes, if any, will be awarded to participants with the best scores, based on the merits of the data science models submitted. See below for the complete Competition Rules.

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
   "Competition Data" means the data or datasets available provided by Academic Team for the purpose of use in the Competition, including any prototype or executable code provided. The Competition Data will contain private and public test sets. Which data belongs to which set will not be made available to participants.

   A. Data Access and Use. You may access and use the Competition Data for non-commercial purposes only, including for participating in the Competition, and for academic research and education. Hacktiv8 reserves the right to disqualify any participant who uses the Competition Data other than as permitted by the Competition Website and these Rules.

   B. Data Security. You agree to use reasonable and suitable measures to prevent persons who have not formally agreed to these Rules from gaining access to the Competition Data. You agree not to transmit, duplicate, publish, redistribute or otherwise provide or make available the Competition Data to any party not participating in the Competition. You agree to notify HAcktiv8 immediately upon learning of any possible unauthorized transmission of or unauthorized access to the Competition Data and agree to work with HAcktiv8 to rectify any unauthorized transmission or access.

    C. External Data. You may use data other than the Competition Data (“External Data”) to develop and test your Submissions. However, you will ensure the External Data is publicly available and equally accessible to use by all participants of the Competition for purposes of the competition at no cost to the other participants. The ability to use External Data under this Section 4.C (External Data) does not limit your other obligations under these Competition Rules.

5. SUBMISSION CODE REQUIREMENTS. <br/>
   A. Private Code Sharing. Unless otherwise specifically permitted under the Competition Specific Rules above, during the Competition Period, you are not allowed to privately share source or executable code developed in connection with or based upon the Competition Data or other source or executable code relevant to the Competition ("Competition Code"). This prohibition includes sharing Competition Code between participant. Any such sharing of Competition Code is a breach of these Competition Rules and may result in disqualification.

    B. Public Code Sharing. You are permitted to publicly share Competition Code, provided that such public sharing does not violate the intellectual property rights of any third party. If you do choose to share Competition Code or other such code, you are required to share it on github repo provided. By so sharing, you are deemed to have licensed the shared code under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such Competition Code or model containing or depending on such Competition Code.

    C. Use of Open Source. Unless otherwise stated in the Specific Competition Rules above, if open source code is used in the model to generate the Submission, then you must only use open source code licensed under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such code or model containing or depending on such code.

6. DISQUALIFICATION. <br/>
   Hacktiv8 reserves the right to disqualify any participant from the Competition if Hacktiv8 reasonably believes that the participant has attempted to undermine the legitimate operation of the Competition by cheating, deception, or other unfair playing practices or abuses, threatens or harasses any other participants, or Hacktiv8.

    A disqualified participant may be removed from the Competition.
