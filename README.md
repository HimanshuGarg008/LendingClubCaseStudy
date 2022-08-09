# Lending Club Case Study
EDA for defaulter in lending club.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Business Objectives


This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, 
lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount 
of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who 
default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving 
factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  
The company can utilize this knowledge for its portfolio and risk assessment. 


## Conclusions
Two ways we can reduce the risk.

By focusing on customer at time of collection.

Int_Rate :- Need to focus on collection and put more effort on customer having higher interest rate.
Grade :- Grade G have higher chances of default need to focus on these type of customer more.
Sub Grade :- F2,G1,G5,F4,G2,G3,F5 need to focus on these category while collection. As chances of default is high.
Term :- Customer taking loan for 60 Months have high chance of default. Need to focus at the time of collection.
Zip code :- Need to focus on below list of zip code as they have high chance of default.
 '871xx', '346xx', '925xx', '751xx', '630xx', '339xx', '488xx','330xx', '245xx', '207xx', '905xx', '914xx', '333xx', '331xx','234xx', '917xx', '305xx', '571xx', '628xx', '171xx', '128xx','657xx', '341xx', '148xx', '960xx', '347xx', '065xx', '446xx','633xx', '360xx', '400xx', '754xx', '816xx', '119xx', '014xx','434xx', '344xx', '279xx', '285xx', '983xx', '547xx', '616xx','172xx', '161xx', '037xx', '974xx', '984xx', '907xx', '363xx','081xx', '971xx', '856xx', '844xx', '489xx', '013xx', '312xx','271xx', '302xx', '927xx', '444xx', '265xx', '238xx', '108xx','361xx', '321xx', '349xx', '641xx', '906xx', '890xx', '623xx','259xx', '779xx', '106xx', '675xx', '325xx', '497xx', '795xx','725xx', '154xx', '135xx', '593xx', '671xx', '487xx', '635xx','484xx', '546xx', '745xx', '449xx', '392xx', '056xx', '407xx', '367xx', '976xx', '937xx', '278xx', '354xx', '445xx', '439xx','072xx', '559xx', '283xx', '308xx', '153xx', '891xx', '082xx','147xx', '206xx', '224xx', '986xx', '614xx', '711xx', '626xx','447xx', '863xx', '826xx', '158xx', '615xx', '422xx', '244xx','619xx', '997xx', '026xx', '187xx', '177xx', '570xx', '534xx','075xx', '935xx', '766xx', '807xx', '758xx', '883xx', '035xx','859xx', '638xx', '425xx', '724xx', '264xx', '713xx', '316xx','376xx', '599xx', '668xx', '406xx', '409xx', '639xx', '912xx','924xx', '253xx', '611xx', '499xx', '573xx', '755xx', '438xx','215xx', '808xx', '744xx', '719xx', '203xx', '608xx', '607xx','897xx', '413xx', '798xx', '673xx', '496xx', '416xx','685xx','746xx', '561xx', '833xx', '663xx', '385xx', '669xx', '373xx','689xx', '094xx', '999xx‘



By Changing Acquisition Score model and including below variables.

revol_util :- Customer with higher revol_util tends to do more default.
purpose :- Purpose as small business customer tends to default more.
inq_last_6mths :- Higher the number of inquire higher the chance of default.
annual income with reference to verification status :- Higher the income in both cases higher the chance of default.
homeownership :- Home ownership as Other tends to do more default.
*** Variable used in rejecting a customer are not used like amount requested, application date, loan title, risk score, DTI, zip code, State, Emp Length, Policy Code


## Technologies Used
- library pandas - version 0.25.1
- library numpy - version 1.16.5
- library matplotlib - version 3.1.1
- library re - version 2.2.1
- library scipy - version 1.3.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- References if any...
	- https://www.listendata.com/2015/03/weight-of-evidence-woe-and-information.html

## Contact
Created by [@HimanshuGarg008] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->