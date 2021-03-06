---
category: ''
datasets_used:
- agency: Australian Bureau of statistics data
  name: 'NATIONAL DATASET: Australian Bureau of statistics data'
  url: http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/4430.02012?OpenDocument
- agency: Hospital Statistics
  name: 'NATIONAL DATASET: Hospital Statistics'
  url: http://data.gov.au/dataset/australian-hospital-statistics-2012-13
- agency: SA Health
  name: 'SA DATASET: Emergency Department Admissions'
  url: https://data.sa.gov.au/data/dataset/admissions-from-emergency-departments
- agency: SA Department of Community and services
  name: 'SA DATASET: South Australian Community Services Directory'
  url: https://data.sa.gov.au/data/dataset/south-australian-community-services-...
event: adelaide
gid: digihealth-plus
hackerspace_url: https://2016.hackerspace.govhack.org/node/1686
image_url: https://2016.hackerspace.govhack.org/sites/default/files/field/image/logo_17.png
jurisdiction: sa
prizes-entered:
- australia-that-thing-we-all-need
- australia-creative-humanities-hack
- australia-data-intelligence-hack
- australia-innovative-ideas-hack
- australia-inspired-by-research-hack
- australia-community-resilience-hack
- australia-no-boundaries-data-hack
- sa-smart-lifestyles
project_title: DigiHEALTH Plus
project_url: ''
repo:
  name: source code demo - digiHEALTH Plus
  type: github
  url: https://github.com/mishra123/git-github.com-mishra123-digitalhealthplus
team_name: DigiHACK
video:
  type: youtube
  url: https://www.youtube.com/watch?v=Uqo4-n0fHpE
---

Problem Statement​​​​​​​

Australia’s population aged 75 or more is expected to rise by 4 million by 2060, increasing from about 6.4 to 14.4 per cent, according to a 2012 population projection report generated by the Australian Bureau of Statistics.  
It also means that there is an increase in the trips made by the elderly population to the GP/ Health care facility for regular check-ups.  This puts pressure on the health system in cases when unnecessary trips could be avoided. This is also in line with the South Australian Government’s health initiative which says ‘Emergency systems are for emergencies only’.   
 
Solution 
The app will see elderly people to have the ability to share vital health parameters on, like blood sugar, blood pressure and Body Mass Index (BMI), via an automated telephone service thus avoiding frequent trips to the health service providers.
The information thus gathered is stored on a database in a cloud environment for interpretation and analysis using Amazon Web Services.  This is then analysed, and presented in the form of a dashboard on an app which can be accessed by the health service providers, carers, family members, and the patients as well.  The infrastructure to set up this system is very cost effective and minimal.  With current transformations in digital technology, health information can be stored securely in compliance with the current legislations in place.
 
Objectives
Monitor and provide highest level of health care to the elderly in the comfort of their home.  Using digital technology for the wellbeing of the community and reducing frequent trips to the health service providers without compromising on the health of the elderly.
 
Functionality

Users download the app and register using the Medicare number and email address.  An auto generated PIN is sent to the registered email address.  For security purposes and to maintain confidentiality, a combination of Medicare and PIN is used to provide access to the health data.  
Carers/Doctors can register for multiple patients using their respective Medicare numbers.  A separate PIN is generated for each Medicare number.  
On Sign up, users/carers can log-in to the app using the Medicare number and the unique PIN supplied.  They would then be presented with a dashboard with the latest readings.  Users can then look into the history by selecting any of parameters shown.
 
Data Set Re-use

NATIONAL DATASET: Australian Bureau of statistics datahttp://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/4430.02012?OpenDocument
Used to identify older persons data from ABS - Disability, Ageing and Carers, Australia: older persons table.  Also used for getting statistics about trips to the health care providers by people aged 65 and above for general consultation. 
NATIONAL DATASET: Hospital Statisticshttp://data.gov.au/dataset/australian-hospital-statistics-2012-13 
SA DATASET: Emergency Department Admissionshttps://data.sa.gov.au/data/dataset/admissions-from-emergency-departmentsDataset used for analysing Emergency Department performance.
SA DATASET: South Australian Community Services Directoryhttps://data.sa.gov.au/data/dataset/south-australian-community-services-...
This dataset is used to identify health care services, their location, and hours of operation and contact details.
 
Technologies used

App Development:
iOS, Android and Windows programming
HTML5/JavaScript/CSS
Font Awesome, jQuery Mobile, Ajax, JSON/XML
 
Web API:
ReST Web Services  using JAX-WS 
Amazon Web Services – Amazon EC2, Amazon RDS 
Oracle 
 
Project Management Tools:
OneNote 2013 (Used to Manage Project Tasks and Information)
Used Agile methodology for the process of Project Management. 
 
Proof of concept repository URL - Code repository, source material:

https://github.com/mishra123/git-github.com-mishra123-digitalhealthplus
​​​​​​​Video URL:
https://www.youtube.com/watch?v=Uqo4-n0fHpE