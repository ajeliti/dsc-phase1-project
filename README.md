# Aircraft Accidents Analysis to Determine The Most Viable Aircrafts for Purchase
## Business Understanding

### Objective
The purpose of this analysis is to look at previous aircraft accidents, so as to come up with an informed decision of the type of aircraft to purchase.

### Key Questions
1. Which aircraft make/models have more accidents, and which have less?
2. What is the type of damage that occurs when the accidents happen?
3. Does the type of damage affect number of injuries?
4. What's the most common accident by purpose of flight?
5. Which phase of flight is more prone to accidents?
6. Which weather condition is affected most?

## DataUnderstanding and Analysis
The data was derived from [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) which is a database of the NTSB(national transport and safety board) that has informartion about selected incidents within the United States and in International waters.

The data set has the following information:
- Event Details : ID, Accident Number, Event Date, Location, Country, - - Airport information
- Aircraft details: Registration number, Make, Model, Number of engines, Engine type, Schedule, Purpose of flight Type of damage.
- Injuries: Fatal injuries, Serious injuries, Minor injuries, Uninjured
- Weather condition
- Report status
- Publication date

## Visualizations
### 1. Aircraft Make
We'll first look at the top ten aircrafts involved in the accidents.

<img width="470" alt="Top ten aircraft" src="https://github.com/user-attachments/assets/05df61ab-60ca-41c6-ba0e-e7d291441486">

### 2. Engine Type
<img width="378" alt="Engine type" src="https://github.com/user-attachments/assets/6f1defb4-22f3-4b35-b94b-a2c1968f48d0">

This is in tandem with the make of aircraft. Most Cessnas and Pipers are small aircrafts which use small engines(reciprocating)

### 3. Purpose of flight

<img width="296" alt="Top ten purpose of flight" src="https://github.com/user-attachments/assets/0e7ce742-f621-4863-a0fb-cf74a724679e">


### 4. Phase of flight

<img width="407" alt="Phase of flight" src="https://github.com/user-attachments/assets/6a54e382-e9da-4444-8e39-e3b96a9c316a">


### 5. Weather Condition

<img width="310" alt="Accidents by Weather" src="https://github.com/user-attachments/assets/223c8d1a-f693-4be4-bffc-c3c5416cc511">

VMC - Visual meteorological Condition
IMC - Instrument meteorological Condition 
VMC is higher because in this condition, the pilot uses visual cues either to take off, or land the plane. 

## Conclusion
From the data analysis, we can see that the most planes involved in accidents are Cessna, Piper and Beech. The majority of these planes have reciprocating/piston engine, again shown from the analysis. One might say that it is not recommended to buy these planes, however the data does not suffice. We could say those are the most common airplanes hence the reason for the popularity in data. Other factors like price of airplanes, maintenance cost were not put into consideration which can be crucial in the purchase. Therefore, I recommend further analysis from other sources, so as to make a better decision.
