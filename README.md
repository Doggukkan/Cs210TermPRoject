# Cs210TermPRoject
The aim of this project is to analyze my studying patterns such as my class attandences, time I spend on IC, and my break patterns when studying.
# Code
All of my code is in GPXData_Project.ipnyb in this repo.
# Presentation Method
My presentation is in the .mp4 file in this repo
# Summary

## Motivation
My motivation for this project was to detect my studying habbits and see what I am succesfull at and what I need improvements on.
## Data Source
My data came from a gpx logger app which loggs my coordinates when there is gps signal
## Data Analysis
### Extracting Features
This was the hardest part of this project because the buildings do not have GPS signals when you are inside them. There are some rare points in the buildings where you can get a GPS signal; therefore, it was very difficult to determine the times when I was in the buildings and when I was out of them. I used some algorithms to filter out small gaps of time when I was inside the building and only kept the larger ones, which meant that I was actually doing something in the building and not just passing by. Another challenge was that the GPS app logged data at different frequencies when the app was on battery saver mode, so I had to create an algorithm that could reconcile both sets of data. However, in the end, I was somewhat successful in gathering information about which classes I attended, my study times at the IC, my break patterns, and some of my leisure time at the Uni center.
## EDA
I used exploratory data analysis techniques to visualize my various studying patterns and gain insights from them.
## Major Findings
  - Found that my break time decreases as I take more breaks
  - My participations to classes drop at exam periods
  - I participate in CS204 the most
## Limitations and Future Work
The biggest limitation was not knowing whether I was actually attending a class or just inside a building during class times. Consequently, I had to assume that I was attending the classes when I was inside the building at the scheduled class times. I do not plan on to work with this project any further I believe the daa I have has very great Limitations and the future potential is very low.
