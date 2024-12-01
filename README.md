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

Cessna, Piper and Beech top the chart. But, it's too early to make a conclusion. We'll look at more graphs.

### 2. Engine Type
Aircrafts have different types of engines. Let's take a look at the types in our data

<img width="674" alt="Count of data by engine type" src="https://github.com/user-attachments/assets/a51d49f9-3123-4986-a402-12b841c5bedf">

Reciprocating engine takes the lead. This type of engine is also referred to a piston engine.

### 3. Purpose of flight
There are different purposes when the planes take to the skies. Let's take a look at this.

<img width="296" alt="Top ten purpose of flight" src="https://github.com/user-attachments/assets/0e7ce742-f621-4863-a0fb-cf74a724679e">

So far, from the three graphs, we can start to see a trend in the data. So far, we can presume these personal planes are Cessna, Piper, and Beech, which have reciprocating engines.


### 4. Phase of flight
Which phase of flight were these planes when the accident occurred? Let's take a look.

<img width="407" alt="Phase of flight" src="https://github.com/user-attachments/assets/6a54e382-e9da-4444-8e39-e3b96a9c316a">

Most accidents occurred during landing, take off and cruise. Next, we'll look at what weather condition theplanes were when the accident, and see if we can make a connection.
### 5. Weather Condition

<img width="310" alt="Accidents by Weather" src="https://github.com/user-attachments/assets/223c8d1a-f693-4be4-bffc-c3c5416cc511">

VMC - Visual meteorological Condition
IMC - Instrument meteorological Condition 
VMC is higher because in this condition, the pilot uses visual cues either to take off, or land the plane. This explains why most accidents happen during landing and take off as seen in the previous graph.

## Conclusion
From the data analysis, we can see that the most planes involved in accidents are Cessna, Piper and Beech. The majority of these planes have reciprocating/piston engine, again shown from the analysis. One might say that it is not recommended to buy these planes, however the data does not suffice. We could say those are the most common airplanes hence the reason for the popularity in data. Other factors like price of airplanes, maintenance cost were not put into consideration which can be crucial in the purchase. Therefore, I recommend further analysis from other sources, so as to make a better decision.
