# GEOG 458 Lab 2 - Martin Yuan

## Topics and parameters
My research topic is Electric Vehicles and charging, but I split it into two angles so I could compare how YouTube content differs depnding on what people care about. 
-   search-result-1: Term Used: EV review, electric car range test, EV charging at home.
    - Focused on practical, everyday questions. 
-   search-result-2: Term Used: DC fast charging, Tesla Supercharger vs CCS, charging network reliability
    - Focused on the public charging ecosystem and reliability topics. 


## Why make this comparison
EV adoption depneds on two things at the same time: 
-   Individual user experience
-   System reliability
I wanted to compare these two because they represent two different barriers to EV adoption. If the content on YouTube looks very different, that tells us the conversation if segments. People are leaning and worrying about different things depending on whether they charge mostly at home or rely on the public infrastructure.

## Word cloud comparison: Similarities and differences
Wordcloud picture 1
![wordcloud-1](/img/wordcloud-1.png)
Wordcloud picture 2
![wordclout-2](/img/wordcloud-2.png)

### Similarities
Both word clouds strongly feature EV, electric, charging, and charger, which confirms both datasets are inside the same overall topic. So it confirms that the crawler isn't pulling irrelevant content. 

### Differences
-   Word cloud 1: 
    - The biggest word include charger, charge, home, electric, and practical iterms like install, homeowner, level, electrician, cost, guide. 
    - The overall feeling is about buying decisions and home setup.
-   Word cloud 2:
    - The biggest word include Tesla, Network, Reliable, Charger, Electric, and a lot of public infrastructure terms such as public, company, area, fast, supercharger, EVgo, IONNA. 
    - The overall feeling is about system level discussion and reliability debates. 

## Possible reasons for the pattern
1. Search intent drives YouTube's recommendation ecosystem. 
Home setup and private charging keywords naturally pull out evergreen contents such as guides and how-to videos. Network reliability keywords usually pulls out more news and analysis content.
2. Different audiences create different language.
Home charging content is aimed at new EV owners and homeowners, so you see words like install, homwowner, electrician. As for network content, it is aimed at road trippers, enthusiasts, and industry watchers, so we can see network, reliable, public and company. 

## How this research can be improved in the future
-   Control the timeframe: compare only videos from the same time window. Otherwise, one group may include older guides while the other includes newer updates.
-   Collect more results per keyword: YouTube search results can be noisy, while larger samples can reduce randomness.
-   Add engagement variables such as likes and comments in the videos, and do sentiment or topic modeling. 

## What was different from my expectation
Before the exercise, I expected the Network reliability group to be more popular overall because the public charging reliability is such a common conplaint online. However, the data I got surprised me. The network group included many low view videos, which pulled down the median views a lot.

File down load link: 
[Download search-result-1.csv](assets/search-result-1.csv)
[Download search-result-2.csv](assets/search-result-2.csv)