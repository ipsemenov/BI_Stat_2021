# BI_Stat_2021

### Olimpic Games

This project is aimed at the analysis of the data from Olympic Games.

Project structure is the following:
* **data** - folder with initial raw files. New files can be added.
* **report** - folder with source code in .Rmd and results in .html

Data frames in raw files have the following columns:

* **ID** – Unique number for each athlete
* **Name** – Athlete's name
* **Sex** – M or F
* **Age** – Integer
* **Height** – In centimeters
* **Weight** – In kilograms
* **Team** – Team name
* **NOC** – National Olympic Committee 3-letter code
* **Games** – Year and season
* **Year** – Integer
* **Season** – Summer or Winter
* **City** – Host city
* **Sport** – Sport
* **Event** – Event
* **Medal** – Gold, Silver, Bronze, or NA

Required packages:

    if(!require(dplyr)) install.packages("dplyr")

    if(!require(psych)) install.packages("psych")

    if(!require(psych)) install.packages("tidyr")

    if(!require(ggplot2)) install.packages("ggplot2")

    if(!require(ggpubr)) install.packages("ggpubr")

    if(!require(corrplot)) install.packages("corrplot")

    if(!require(tableHTML)) install.packages("tableHTML")
