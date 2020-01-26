# Wuhan Outbound Flights Analysis
### Analyzing outbound flights from Wuhan Tianhe airport WUH ZHHH of a single day

### Data
Each record is a receiver message json row
Data contains only messages received on 2 Jan 2020

### Exploratory analysis
*flights outbound of Wuhan*
- Top flight counts to destination countries
- Top flight counts to domestic destinations (in China)
- Number of flights to SG
- Operator and model of flights to SG
- Estimated number of passengers from Wuhan to SG
- ... (more)

*flights inbound to Singapore from domestic chinese states*
- Top domestic state to SG with most number of flights
- Top operating airline to SG
- Top model of airplanes to SG
- ... (more)

### Simulation Model
The model employed is a SEIR epidemic model without vitals where S stands for susceptible, E for exposed, I for infected and R for recovered

#### Model conclusions
By 13 March, if the spread of virus is not controlled, the model suggests a total of almost 1 million patients infected with Wuhan virus in SG.

Limitations: The SEIR model includes imported infections that are from flights that are currently still in operation. In addition, these flights miss out on others connecting or direct routes from cities affected with Wuhan virus.
