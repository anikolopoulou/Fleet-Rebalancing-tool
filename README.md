# Fleet-Rebalancing-tool

The Static Bike sharing Rebalancing tool determines
(a) the route of each vehicle performing bike repositioning operations, and 
(b) the number of bikes to load or unload at each station visited by one vehicle,
aiming to minimize the total routing costs and the total penalty of unsatisfied demand.

The employed solution method was coded in Python 3.11.7. Each instance is solved on a computer server equipped with an Intel(R) Xeon(R) E-2356G CPU @
3.20GHz and 16 gigabyte of RAM under Windows Server 2022 Standard edition.

**Datasets**
The input data used in this research is retrieved by the work of Sartori and Buriol (2020). These problem instances consider realistic configurations using data
publicly available on the Internet. The instances were generated from real, publicly available locations in the cities of Barcelona (Spain), Berlin (Germany), New York City (United States of America), and Porto Alegre (Brazil). Moreover, the penalty of unmet demand is introduced as p and the value assigned to it is 1500 and the routing costs are calculated based on the euclidean distance between the stations. 

**Data Set I**
To assess the algorithmic performance, a set of small-scale problem instances is introduced (Data Set I), generated from the benchmark instances provided in
the work of (Sartori and Buriol, 2020). These problem instances consider realistic configurations using data publicly available on the Internet. The instances were generated from real, publicly available locations in the cities of Barcelona (Spain), Berlin (Germany), New York City (United States of America), and Porto Alegre (Brazil).
Data Set I consists of graphs where the total number of bike stations was taken from the set O = {5, 8, 10}. The bike stations’ locations were randomly selected from the Random class set of instances of (Sartori and Buriol, 2020), involving cases where the locations are randomly distributed. One vehicle is available for the repositioning of the bikes.

**Data Set II**
To assess the solution quality with respect to the geographic distribution of bike-sharing stations, a set of problem instances is introduced (Data Set II). These are generated from the benchmark instances provided in the work of (Sartori and Buriol, 2020). Data Set II consists of graphs where the total number of bike stations was taken from the set O = {12, 15, 20}. We consider a homogeneous vehicle fleet with two vehicles available for the repositioning of the bikes. Finally, different distribution network classes are examined with respect to the geographical distribution of the bike stations. In particular, we distinguish among three geographic distribution classes: i) Random (R), ii) Random-Clustered (RC ), and iii) Clustered (C ).
Regarding the R class, the locations are randomly selected from a set of locations L. For the RC class, a number of locations are clustered, whereas the remaining are random as suggested by Sartori and Buriol (2020). Ultimately, for the C class, the stations are selected from a set L in a way that creates clusters, following the logic of Uchoa et al. (2017). In addition, the depot has been selected to be located at central positions of the examined geographic regions.


