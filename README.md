Deflating Economic Data — Nominal vs. Real
Objective

This project examines the difference between nominal and real economic values by adjusting wages and Big Mac prices for inflation using CPI data from FRED.

Methodology
Pulled CPI and average hourly earnings data from FRED.
Created a deflate_series() function to convert nominal values into constant 2020 dollars.
Compared nominal and inflation-adjusted hourly earnings over time.
Deflated US Big Mac prices using CPI to measure changes in real purchasing cost.
Built an interactive deflation explorer that allows users to change the base year and compare nominal and real values.
Key Findings

Nominal hourly earnings increased from $2.50 to $32.53, while real earnings in 2020 dollars moved from $20.92 to $25.20. This shows that the increase in purchasing power was much smaller than the increase in nominal wages.

For the US Big Mac price, the nominal price increased by 178%, while the inflation-adjusted price increased by about 43%. CPI increased by approximately 95% over the same period. These results show why adjusting for inflation is important when comparing economic values across time.
