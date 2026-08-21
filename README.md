## A repo with code and data for Techniques in Marine Science 1 (MB5370) - R for Marine Science


The overarching concepts of "Module 2: Data Science in R", were set out in such a way that it helped us, the students gain a much broader perspective on the process of data wrangling while using a tool such as RStudio. The workshops in play were conducted using real-world ecological datasets to illustrate how raw and imperfect data can be transformed into a publication worthy format. The module begins with a baseline foundation on the use of various in-built packages, also known as tidyverse-grammar.


The module begins with the application of the Palmer Penguins dataset, where each and every line of code that was ran, gave us a better understanding of the selection,  sorting, mutating and summarizing processes for the data which were produced. This was carried out in tandem with the practicing of creating a clear structure such as the developing of version control from where the knitted html file could be committed to a public platform like GitHub, into specific repositories and understanding the need of having data stored on disk versus data that was held within an active session space, which in itself is accessible from any system that you come across.


Building on the fundamentals which were attained from "Workshop 1" of "Module 2", "Workshop 2" addressed issues that people face in real-time in the form of data wrangling challenges using a former PhD's model, which stimulated a Ross River estuary fish survey. Working with a dataset which consistently went overboard with a lot of inconsistencies in the form of text and date-time formatting, along with long and wide formats, required the use of packages such as lubridate and stringr. The key takeaway from an exercise such as this was trying to handle the complete absence of data, distinguishing gaps from sensor errors to zero-observations and mathematically undefined values .

	

	Together, these two workshops reflect a series of progressive steps that were carried out compared to the work that was done during the previous module's workshops.



  Workshop 1- Foundations of Data Science


  Simple Data Wrangling:

Across the development of the entire workshop, I worked with an entirely "AI-Off" environment and this practice helped build a foundational fluency with the usage of a variety of packages for various different purposes, from "tidyverse" to "PalmerPenguins". This case study signified the use of both ecological and morphological factors for three different species of penguin found across the Antarctic archipelago, Palmer. 


Here, I practiced the use of core "dplyr" grammar such as "select(), arrange(), mutate(), group_by() and summarise()",  for the isolating, sorting and aggregating of different biological features of three separate penguin species; the Adelie, Gentoo and the Chinstrap, such as body mass, bill length, bill size and differentiation of the different species based on island groupings.


Other functions learned included the use of pipe operations together, for the structuring and gathering of a more readable workflow. Essential pieces of the puzzle were also learnt, from the need of having a reproducible project structure set up to understanding the difference between disk storage and session memories to the recognition of tibbles as a safe working environment.




Workshop 2- Complex Data Wrangling



Major Objectives:

The main aim of this particular workshop was to figure out the usage of foundational "dplyr" skills towards the reshaping and interjection of a multi-source ecological dataset. This learning involved the use of a variety of functions such as "pivot_longer()" and "pivot_wider()" for the tidying of datasets, "separate()" and "unite()"  for splitting and recombining columns, along with the standardization of texts and timeframes such as the format of dates that did not adhere to the case sensitive nature of RStudio using "stringr" and "lubridate". 


Each and every example that I had ran on RStudio, used a combination of functions which dealt with the processes of data cleaning, wrangling and structuring because for any data to be programmed and managed properly, the categorization of these different skills have to be adhered to, even when you are faced with difficult situations such as classification of data that are invalid or missing.


Two different exercises with two different outcomes were ran and studied: 

(i) Palmer Penguin dataset was used yet again and here I looked at the completion of steps 1, 2 and 3, as per the workbook provided by the professors for class "MB5370: Techniques In Marine Science 1" .


(ii) Keystone species differentiation, which looked at the presence of different species of fish across the Ross River estuary gradient, with key environmental variables to be accounted for such as salinity, turbidity and temperature.


	Steps followed: 

1) Cleaning the metadata which involved the cleaning of information within the "island_name" column using two "stringr" operations.


2) Polishing the two tables that we had in our hands and matching the data with the metadata. 	This was deemed necessary because if it hadn't been caught, then the "NA" values would have persisted, since the "join_by()" fucnction gets matched with one another based on string equality rather than case-insensitivity.


3) Creation of a wide summary matrix: This outlook helped me understand the switch from "mean()" to max()".

	Even though, it was just a small change in code, the table that was formed produced the number of individual penguins, all the way from a typically small/medium sized to the largest recorded penguin across different islands while also differentiating it based on its individual species.






                                                                            Keystone Species



This exercise, due to it being conducted in conjunction with skills that were developed during the learning and structuring phase of  "Workshop 1", the session shifted from an "AI-Off" phase to an "AI-On" phase project management tool and this helped me tackle the actual challenge of extracting important ecological and biological information from a messy, real-time dataset.


The dataset that we looked at was based on a simulated fish survey project, conducted by a former PhD student, along the Ross River estuary gradient in Townsville. 


Since the project had a lot of inconsistencies, it constantly challenged the case sensitive nature of RStudio and these roadblocks paved a pathway for me to use a variety of functions and arguments, which helped me standardize the data and then producing a publication ready fish abundance dataset along the estuary's salinity gradient.
