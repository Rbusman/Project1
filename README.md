# Project-1-blood.batteries

Exploratory Data Analysis of the Drivers of EV
Performance and Consumer Experience & 
Behavior
Team members:  Ryan Busman, Elaine Kwan, Deb 
Peters, Nick Watkins
---------------------------------------------------------------------------------------------------------------------
--------------------
01/03/2024  Synopsis:   Finalized databases;  Began graphing “Performance”
data (see below for clarification);  Assigned continued data sourcing and 
graphics development for 01/04/2024 class  
01/04/2024  Agenda:  Review of additional work; Review of Consumer 
Reports data; Refine hypotheses and align with available data; Update 
workplan; Work session on the weekend 
1
EDA Assumptions:
We will focus on cars for this exploration:  LDV1 (passenger cars and 
sports utility vehicles)
Definition of an EV care (carandriver.com):
oBattery electric vehicles (BEVs), which run entirely on 
electricity stored in batteries.
oHybrid electric vehicles (HEVs), which use a combination of 
gasoline and electricity to run.
oPlug-in hybrid electric vehicles (PHEVs), which can be 
plugged in to charge the batteries and use electricity or gasoline 
to run.
oFuel cell electric vehicles (FCEVs), which use hydrogen to 
generate electricity and run.
Part 2:  focus:
oOther model types:  i.e., truck
oEV development correlation with lithium procurement
oSelf-driving vehicles (?):  
https://waymo.com/blog/2023/12/waymo-significantly-
outperforms.html?
utm_source=www.superhuman.ai&utm_medium=newsletter&ut
m_campaign=scientists-claim-they-ve-built-an-ai-that-can-
predict-when-people-die
oMicrogrid strategies on peak demand
oNational risk index (natural risks):  
https://hazards.fema.gov/nri/learn-more
oEnvironmental justice:
Electric Vehicle Charging and the Justice40 Initiative 
https://www.anl.gov/esia/electric-vehicle-charging-equity-
considerations
https://anl.maps.arcgis.com/apps/webappviewer/index.html?
   id=33f3e1fc30bf476099923224a1c1b3ee
CDC/ATSDR Social Vulnerability Index:  
https://www.atsdr.cdc.gov/placeandhealth/svi/index.html
2
General/Introduction Trends in EV 
Location:
oGlobe compared to US:
Frames additional explorations for US/Identifies 
opportunities for exploration later in the presentation:
Charging points
Sales
Sales share
Stock share
Electricity demand
Oil displacement
oUS:  EVs among all cars in the US
Sources:
ohttps://www.iea.org/data-and-statistics/data-tools/global-ev-data-   
explorer
oUS Census (Vehicles per household):  
https://www.census.gov/acs/www/about/why-we-ask-each-
question/vehicles/
oUS Highway Statistics (Fatalities, mileage, etc...):  
https://www.google.com/publicdata/explore?ds=gb66jodhlsaab_
  
3
EV Attributes:  
Independent variables:   Model, manufacturer, EV type (BEVs, HEVs, 
PHEVs, FCEVS) horsepower, weight, footprint/vehicle size, battery or 
engine, seating capacity
Dependent variables:  Fuel economy, CO2, Charging rate and speed
Sources:
ohttps://www.epa.gov/automotive-trends/explore-automotive-   
trends-data
ohttps://afdc.energy.gov/data_download   
Hypotheses:
1.).   
EV Performance:
Independent variables:  Model (year-over-year growth), time, state, 
fuel type, location of driving (city, highway), 
Dependent variables:   Efficiency, cost (i.e., depreciation, repairs), cost 
per mile, etc...),  Crashes, injuries and fatalities
Sources:
oInjuries and fatalities: 
 https://cdan.dot.gov/query
 https://cdan.dot.gov/
oModel type growth in EVs over the years....   
https://afdc.energy.gov/data/10304
oFuel economy by location (city, highway)
https://afdc.energy.gov/data_download
oPage 175 and after of Argonne
oPer mile costs by fuel type and model starting on page 175:  
https://publications.anl.gov/anlpubs/2021/05/167399.pdf
4
Charging Point Access:    
Independent variables:   Status (available, planned, etc...) location, 
state, time, concentration at location, credit card accepted, public 
versus private, associated ev network, charging level, ev connector 
type, and others...see below.
Dependent variables:  Peak load, power loss, charging time, vehicle 
adoption by state?  manufacturer?  model?
Sources:  
oStreetlight Data, Ryan is providing more details
ohttps://developer.nrel.gov/docs/transportation/alt-fuel-stations-   
v1/all/  
oAccess, state, facility type, fuel type, psi, opening date, hours of 
operation, accepted cc payment:  
https://afdc.energy.gov/data_download
Consumer Experience and Behavior:  Use, Sentiment, Spending
Independent variables:   "” by travel behavior and purpose (only for 
2017), household and personal characteristics, incentives
Dependent variables:  Sales, car loan, trip purpose by length, vehicle 
registration 
Sources:
oUS Census
oRegistration:  https://afdc.energy.gov/data/10962
oLight Duty EV Monthly Sales Updates:  
https://www.anl.gov/esia/reference/light-duty-electric-drive-
vehicles-monthly-sales-updates-historical-data
oConsumer data/demographics:  
https://hedgescompany.com/blog/2019/01/new-car-buyer-
demographics-2019/
oNational Household Travel Survey:  https://nhts.ornl.gov/
Federal Highway Administration (FHWA) National 
Household Travel Survey (NHTS):
NHTS is the authoritative source on the travel behavior of 
the American public. It is the only source ofnational data 
that allows one to analyze trends in personal and 
household travel.
It includes daily non-commercial travel by all modes, 
including characteristics of the people traveling,
their household, and their vehicles. National and State. Use
this data to analyze trends in personal and household 
travel
oMisery Index:     https://www.miseryindex.us/   
5
It is simply the unemployment rate added to the inflation rate. It is 
assumed that both a higher rate of unemployment and a 
worsening of  inflation both create economic and social costs for a 
country
oNew Car Loan Analysis: People have been financing higher car 
values over longer amounts of time. Explore what is driving this 
trend. Search for answers by using data collected from the 
Federal Reserve Economic Data (FRED)Links to an external site.
oIncentives:
oIncentives by state:  https://afdc.energy.gov/laws/matrix?
sort_by=tech
oIncentives by fuel type:  
https://afdc.energy.gov/data/10360
oTrip by purpose:  Oak Ridge National Laboratory:  Trip by 
purpose:  Only to 2017 https://afdc.energy.gov/data/10317
                           https://tedb.ornl.gov/data/
