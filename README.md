# Samsung Health analysis enriched with geographical information
<b>Data cleaning and analysis project written in Python (Jupyter notebook, Markdown format)</b>

_**Executive Summary**_: My goal for this project was to combine both my Samung Health and Google Maps History Location data to:
* Get a full perspective on my workout activities in the past 6 years (running, hiking, swimming and dancing)
* Link geographical data to my workouts. The aim was to identify the places where I did long hikes for instance.
<br>

_**Content of the repository**_:
Because importing and cleaning the data was quite tedious for both data sources, the code has been decomposed into 3 different Jupyter Notebooks.
* Part1 : Samsung Health focus (walking and running). Actions: I imported, cleaned, analyzed and visualized 6 years of pedometer data from my Samsung Health app (source: 1 csv file)
* Part2 : Google Maps focus (dancing and swimming workouts). Actions: I imported, cleaned, enriched and analyzed 6 years of my Google Maps History Location data (source: dozens of JSON files).
* Part3: Combination of the data sources into a single database. Actions: I merged data from both Samsung Health and Google Maps History Location into a single database. The output was used for creating a comprehensive Tableau dashboard about my physical activity.
<br>

_**Final output**_: 
* The results of the 3 Jupyter notebooks were used for building an [interactive Tableau dahsboard](https://public.tableau.com/app/profile/margot.marchais.maurice/viz/SamsungHealthRevamp/SamsungHealthRevamp) that provides a comprehensive view of my workout activity over time
* A non-technical case study is also available on my [blog](https://margot-marchais-maurice.webflow.io/work/samsung-health-google-maps) to provide further explanations about the why of the project and my methodology
<br>

_**Technical learnings**_: I made this project to improve my Python coding skills as well as my ability to manipulate deep-nested JSON files. The data were very interesting to analyze because: they were not well documented and contained lots of duplicates (Samsung Health), and quite complex to manipulate (Google Maps Location History data). 
<br><br>

_Preview of the Tableau dashboard using both Samsung Health and Google Maps data_: 
<img width="662" alt="2022-12-08_19h45_18" src="https://user-images.githubusercontent.com/116331323/210272928-71451519-b558-4283-8c0c-0229788760dd.png">

