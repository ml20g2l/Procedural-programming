# Procedural_programming
C language

Coursework 1

Wrote a program for a water company. The program can calculate and print water bills for different customers. 
It can also compute and print a report of the company's financial revenue, profit, and other useful statistics.

The C program, named "water.c," is designed to calculate and manage water bills for both domestic and commercial customers based on a specified pricing structure. The program incorporates a menu system with options to compute individual customer bills and quarterly summaries. Key features include:

Billing Calculation:

Domestic customers pay a fixed fee of £10 per quarter for surface water processing.
An incremental pricing system is applied to fresh water consumption, with varying unit prices across consumption bands.
Waste water is charged at £0.25/m³, and a daily standing charge of £0.10 is applied.
For commercial customers:

They are charged the maximum tariff (band 5) for all consumption.
Additional charges include waste water processing (£2/m³), a surface water processing charge of £50 per quarter, and a daily standing charge of £1.30.
VAT at a rate of 20% is applied to the total bill for commercial customers, while domestic customers are exempt from VAT.

Quarterly Summaries:

Total fresh water consumption by all customers is calculated.
Total fresh water consumption by domestic customers is determined.
Total revenue is computed (excluding VAT, as it must be forwarded to the government).
The total cost of providing water, assuming an average cost of £1 per cubic meter, is determined.
The profit or loss is calculated as the difference between revenue and cost.
Income tax payable to the government is computed at a rate of 25%.
The average and maximum values of domestic bills are determined.
Implementation Details:

The program includes a menu system with options to compute individual bills and quarterly summaries.
It utilizes a specified pricing table for consumption bands and associated unit prices.
The program accounts for VAT application for commercial customers.
Calculation of quarterly summaries involves aggregating data from individual bills.
The program aims to provide comprehensive financial insights into the water company's operations, including revenue, costs, profits, and tax obligations.


Write the code in standard C. It complies with gcc on Linux and Windows. 
