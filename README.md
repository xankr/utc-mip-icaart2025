# utc-mip-icaart2025
Source code and benchmark data for the paper authored by Andrii Nyporko, Matyáš Švadlenka, Nikolai Antonov, Mohammad Rohaninejad, and Lukáš Chrpa "Centralised Urban Traffic Routing Using Mixed-Integer Programming" published at ICAART 2025 (https://www.scitepress.org/Link.aspx?doi=10.5220/0013137100003890).

# How to work with the data
The archives contain the results, as well as the benchmark configuration files needed to generate them. The SUMO simulator is required for use and simulation.

# Running the benchmarks
sumo -c <city>/<subbenchmark>/<config>/<configname>.sumocfg --duration-log.statistics for obtaining the simulation results.
The same results could be vieved or in statistics folder.

# References
SUMO simulator and the documentation about how to work with it could be found here: https://sumo.dlr.de/docs/index.html 

