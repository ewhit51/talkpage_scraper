# talkpage_scraper

This file contains code that should scrape controversial talk pages using mwapi and mwchatter. 

Currently, errors are being thrown when parsing the talk pages for the following articles:

-1919 World Series

-Adventism

-Andrew Dice Clay

-Black hole information paradox

-Blood type

-Caligula

-Charles de Gaulle

-Domestic violence

-Environmental impact of hydraulic fracturing

-File sharing

-Game of Thrones

-Genocide

-Genocide denial

-Graeco-Armenian

-Hispanic

-Imperium (Warhammer 40,000)

-Jacques Chirac

-Jim Thorpe

-Jury duty

-LGBT

-Logging

-Mahmoud Ahmadinejac

-Margaret Cho

-Michael Vick

-Neoliberalism

-Nero

-Olivia Newton-John

-Panama Canal Zone

-Patriot Act

-Smart meter

-Sting

-Tony Blair


The error is that someone has posted without a username. This shouldn't cause an error, but seems to for some reason. The error is coming from mwchatter, although may be due to something happening in earlier code. 

I have updated the Talk Page Scraper to show examples of a parsed talk page, and a raw talk page for comparison purposes. I have also added a file called Test_Parse that simply prints out a parsed talk page, in case something strange is happening when talk pages are printed into the csv in the final step. It doesn't appear that this is the case, but the two talk pages can be compared here. 

It appears that further parsing will be needed for legibility reasons. 
