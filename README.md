# Shiny
Shiny Pokemon are an alternate colour variation that have a very low encounter rate. The chances of finding a shiny on any given encounter is 1/8192. This has led to community of "Shiny hunters" who take on the task of repeatedly encountering the same Pokemon for hours on end in hopes of finally finding that alternate colour variation. This program was created to help automate that process on static encounters. Static encounter pokemon are generally more rare and less likely to be shiny as there is only one chance of catching them per save file.

The Python application uses a webcam and OpenCV to detect alternate colour values of Pokemon. Depending on the colour values detected, the program will send serial data to an arduino to either reset the game and encounter the pokemon again, or will terminate the program to indicate a shiny has been found.   

The first succesful test for this application found a shiny just after 2000 resets, and took over 16 hours to complete (30s/reset). 
