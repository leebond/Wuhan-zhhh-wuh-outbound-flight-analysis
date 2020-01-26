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
