# COVID-19-Analysis

This is the companion code for the data scientist blog project:  

https://datalurker.wordpress.com/2020/03/08/covid-19-should-we-panic-and-when-will-it-end/

There are 3 datasets used in this project sourced from below:  

https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data

The data is downloaded as of 03/07/2020 CST  

Libraries used for this project:  
* numpy, pandas, matplotlab, scipy

Project file structure:  

* COVID-19 Analysis.ipynb : Analysis file  

* COVID-19 Analysis.html  : Analysis output  

* Data\                   : Data downloaded as mentioned above used for this analysis


This project follows the CRISP-DM process as demonstrated in the analysis flow, from business/data understanding, to data preparing/modeling, until results/deploy. 

The analysis is aiming at answering following questions of interest:

1. How many phases of infections there are in the observed virus trasimission process? 
2. Does the virus transmit similarly in different areas/states?
3. How is the situation in China now at 3 months after the outbreak? Will it get cleared soon?  
4. How long it will take to see the panic outbreak in the US and when it will clear out?

Based on this analysis, the spreading of COVID-19 generally has 3 phases, slowly growing, fast transimitting, stable plateau. Different province in China all have similar spreading trends. After 3 months, most province in China have the virus under control while Hubei still has a long way to go. Compared to China, the US is currently in the early fast transimtting phase. If following similar protocol and strategy as in China, the virus should finsh its course in the next a few months. We shall take precautious and avoid public areas in the near future. 
