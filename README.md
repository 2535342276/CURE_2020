# CURE_2020
# Database Accessibility Data
## What is this repository?
This repository contains data for around 90 nucleic acids research database.
## Why was it created?
There's currently a lack of study on biology database accessibility. This project aims to change that; I make collect around 100 nucleic acids research database, with detailed information about each database, available in CSV format. There are also many databases that are not well maintained and are eliminated.
I hope that this will make it easier for biologists to know the average number of years of database existence, and the tend of biology database accessibility.
## Where did you get the data?
The dataset I collect is from the Molecular Biology Database Collection, which is is an online resource listing key databases of value to the biological community. This Collection is intended to bring fellow scientists, attention to high-quality databases that are available throughout the world, rather than just be a lengthy listing of all available databases. The published papers of database provide database's specific information. https://academic.oup.com/nar/issue/28/1 I focuses on maybe 3 NAR databases issues. (2000, 2005, 2010)
## Data format
The fields include the database name(str), database description(str), database URL(str), publication DOI(str), publication date(int), accessibility(Boolean), current location(str), and citation numbers(int). 
