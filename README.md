# Communications_Authority

1.  Define project
2.  Find types of Spectrums covered in the USA
3.  Find types of Spectrums covered in the Ghana
4.  Present findings


# Project Topic, Background, Audience

## Topic: Spectrum

## Background
I was having a conversation with an old colleague when he mentioned that they had loads of spectrum survey data to go through and didn't know how.  So I volunteered to help sort the data and present the survey results in Tableau.  We decided to start first with a simple project of finding what spectrum is covered internationally (represented by the US) and in Africa (represented by Ghana.)

## Audience
Possible board that decides on giving out Data Analysis contracts

## Septrun Applications

1.	Broadcasting

2.	Air band

3.	Marine band

4.	Amateur radio frequencies

5.	Citizens' band and personal radio services

6.	Industrial, scientific, medical

7.	Land mobile bands

8.	Police radio and other public safety services such as fire departments and ambulances

9.	Radio control

10.	Licensed amateur radio operators use portions of the 6-meter band in North America. Industrial remote control of cranes or railway locomotives use assigned frequencies that vary by area.

11.	Radar




### Also:
1.  Bandplan 

2.  Bandstacked 

3.  Cellular frequencies 

4.  DXing 

5.  Frequency allocation 

6.  Geneva Frequency Plan of 1975

7.  North American Regional Broadcasting Agreement

8.  Open spectrum

9.  Orbit spectrum

10.	R

11. Radio § Communication system

12. Scanner (radio)

13. Two-way radio

14. U-NII

15. Ultra-wideband

16. WARC bands

17. Tremendously low frequency (TLF) (electromagnetic radiation, frequency below 3 Hz) [18]


## Spectrum Allocation in Ghana
The National Communications Authority (NCA) has published the National Frequency Allocation Table (NFAT) for wireless communications services in Ghana.  The NFAT is one of the most important tools for effective spectrum management; It details the uses of the various frequency bands for the numerous radio communication service categories in accordance with the Radio Regulations of the International Telecommunication Union (ITU).

The objective of developing the NFAT is to maximize the efficient use of radio spectrum while assuring that spectrum is made available for new technologies and services. The table contains current uses of spectrum and those that may be used in future.


## Spectrum Applications

#### Telecommunication
1.  Telecommunications:
2.  Mobile Cellular (2G/3G)
3.  Broadband Wireless Access
4.  Fixed Licence
5.  Interconnect Clearing House (ICH)
6.  Mobile Virtual Network Operations (MVNO)
7.  International Wholesale Carrier Licence
8.  Internet/Public Data Service Provision
9.  VSAT Licences
10. Numbering (SIM, M2M, Short Codes etc.)
11. International Inbound Traffic
12. Microwave Authorisation
13. Telemetry, SCADA, Alarms
14. Maritime Radio Services
15. Aeronautical Radio Services


#### Broadcasting
1.  Television Broadcasting:
2.  Radio FM Broadcasting
3.  Amateur Radio
4.  Satellite


#### Standards
1.  Standards:
2.  Type Approval
3.  Dealership
4.  DTT Conformance Certification


#### Infrastructure
1.  Infrastructure:
2.  Infrastructure Licence (Nationwide or Metro Fibre)
3.  Submarine Cable Landing
4.  Mast & Towers


#### Other Services
1.  Other Services:
2.  Communications Managed and Support Service Licence



## Project Goal
List and Compare the covered Spectrum


## Project Factors
...

## Questions to Investigate During Project
What spectrums are licesed in the USA but not in Ghana


## Roles

John Essuman    Deputy Director of Research  -  Statement of Work

Dinah Bondzie   Data Engineer                -  Consultant / Project Lead

X role --- 
X: The member in the X role will decide which technologies will be used for each step of the project.

Square --- 
Square: The team member in the square role will be responsible for the repository.

Triangle --- 
Triangle: The member in the triangle role will create a mockup of a machine learning model.

Circle --- 
Circle: The member in the circle role will create a mockup of a database with a set of sample data, or even fabricated data.\


## Technologies Used

### Database Storage
pgAdmin - PostgreSQL

### Data Cleaning and Analysis
Juypter Notebook - Pandas

### Machine Learning Model
Google Collab Notebook

### Presentation of Findings
Tableau Public
GitHub


## Communication Protocol
...



# Data Exploration and Analysis Phases
...

## Data Exploration and Analysis Overview
...

## Datasets and Sources
...

## Description of Data Sources
[https://www.ctia.org/news/what-is-spectrum-a-brief-explainer]
!

[chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/viewer.html?pdfurl=https%3A%2F%2Ftransition.fcc.gov%2Foet%2Fspectrum%2Ftable%2Ffcctable.pdf&clen=2071133&chunk=true]
!

[http://www.ntia.doc.gov/osmhome/allochrt.html]
!

[https://en.wikipedia.org/wiki/Radio_spectrum]
!

[https://nca.org.gh/2019/02/22/nca-publishes-national-frequency-allocation-table/]
!

[https://nca.org.gh/licencing-and-authorisation/]
!
[]

# Database
...

## Steps in Building the Database

Define the fields required

Extract Data on the net into Excel

Use PGAdmin in to join the tables with SQL

List the services covered and not covered


## Data Dictionary
...

# ETL Method
...


USA Spectrum

	Application	  Type
	
1	Broadcasting: 	Television
2		FM Radio
3		Cellular Phone

4	Air band: 	VHF Radio
5		HF Radio

6	Marine band:  	Marine VHFRadio

7	Amateur radio frequencies:  	VHF Radio
8		HF Radio

9	Citizens' band and personal radio services:  	UHF CB Radio

10	Industrial, scientific, medical:  	Microwave Ovens
11		Cordless Telephones
12	Computer Networks
13	Devices
14	Garage Door Openers

15	Land mobile bands:  	Base Stations
16		Land Mobile / Portable Tranceivers
17		Business Band Radio
18		Professional Mobile Radio
19		Police Radio
20		Trunking Systems

21	Radio control:  	Radio Control
22		Unlicensed Spectrum
23		Radio Control
24		Amateur Radio
25		6-meter band
26		Railway Locomotives

27	Radar:  	Radar
28		Microwave
29		Meteorology




Ghana Spectrum

	Application	        Type
	
1	Telecommunications:	Mobile Cellular (2G/3G)
2		Broadband Wireless Access
3		Fixed Licence
4		Interconnect Clearing House (ICH)
5		Mobile Virtual Network Operations (MVNO)
6		International Wholesale Carrier Licence
7		Internet/Public Data Service Provision
8		VSAT Licences
9		Numbering (SIM, M2M, Short Codes etc.)
10		International Inbound Traffic
11		Microwave Authorisation
12		Telemetry, SCADA, Alarms
13		Maritime Radio Services
14		Aeronautical Radio Services

15	Broadcasting:	Television Broadcasting
16		Radio FM Broadcasting
17		Amateur Radio
18		Satellite

19	Standards:	Type Approval
20		Dealership
21		DTT Conformance Certification

22	Infrastructure:	Infrastructure Licence (Nationwide or Metro Fibre)
23		Submarine Cable Landing
24		Mast & Towers

25	Other Services:	Communications Managed and Support Service Licence
26		Public Radio Equipment (PRE) or Land Mobile Services
27		Value Added Services (VAS)



## Extracting the Data
...

## Transforming the Data
...

## Loading the Data
...

## Handling Missing Values
...

# Machine Learning
...

## Model Choice
...

## Code for Random Forest Model
...

# Dashboard
...

# Conclusion
...

## Results
...

## Summary
...

## Lessons Learned
...

## Future Projects
...

.
