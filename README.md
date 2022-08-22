# surfs_up


**CHALLENGE OVERVIEW

This project explores the power of Advanced Data Storage and Retrieval to efficently produce an analyis of temperature trends in Oahu, Hawaii. Specifically, summary statistics of temperature data were requested for the months of June and December, in order to determine if a prospective surf and ice cream shop business can sustainably operate year-round as opposed to a seasonal business.

**FEATURES AND DATA SOURCES

Data Source: hawaii.sqlite
Programming Files: SurfsUp_Challenge.ipynb, climate_analysis.ipynb
Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, pandas, numpy
Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook
Challenge Deliverables

**Deliverable 1: Determine the Summary Statistics for June Deliverable 

<img width="194" alt="Rain in June Stats" src="https://user-images.githubusercontent.com/105955544/185818147-877d91c3-9a41-414b-b3ee-1cd1b7cac22f.png">
<img width="173" alt="Prcp in June" src="https://user-images.githubusercontent.com/105955544/185818150-8c1500f8-6b46-48b8-b76d-0965c88ac0ba.png">


**2: Determine the Summary Statistics for December Deliverable 

<img width="205" alt="December Temperatures" src="https://user-images.githubusercontent.com/105955544/185818157-0ae4b7fd-1a5a-4182-a183-4656cc1975ee.png">
<img width="165" alt="Prcp in December" src="https://user-images.githubusercontent.com/105955544/185818161-55fdfd1d-21b5-42b3-88c1-4392b1e26a61.png">

These two tables tell us about the differing weather patterns for the two monthly periods. Some takeaways:

Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

**3: A written report for the statistical analysis (README.md)

Oevrall the weather in December and June are historically very similar, although December has a wider range of results, with its high being close to June's but its low well below June's.

Additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.
