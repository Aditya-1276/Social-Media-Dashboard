# Social-Media-Dashboard
A end-to-end social media analytics project analyzing Little Red Zombies' content performance across Instagram, LinkedIn, X, and ArtStation. Built as a portfolio exercise in data collection, cleaning, and visualization. The subject of this analysis was selected for no other reason other than my admiration of their portfolio and curiosity. This dashboard is not indented to be the basis of any qualitative judgements of the company, it's just a fun project I wanted to use to stretch my dashboarding muscles.

Data was scraped using Apify and cleaned in Python (pandas), covering ~400 posts across four platforms. Key engineering decisions include a view-estimation methodology for platforms where view counts were unavailable via scraping, and a reach-based engagement rate formula chosen over the conventional follower-based approach for more honest performance measurement.

Deliverables include a Google Sheets dashboard for high-level monitoring and a Power BI dashboard for deeper analytical exploration, covering engagement performance, posting patterns, hashtag strategy, and game-level content analysis. The raw data files have not been included.

Stack: Python · pandas · Google Sheets · Power BI · Apify
