
This application is designed to help [Trafford Council's](https://www.trafford.gov.uk) officers and members better understand the needs and concerns of residents who use Twitter.

**Method**    
The following search terms are used for each query:

- Trafford Council: "@TraffordCouncil OR 'Trafford Council'"   
- OneTrafford: "@OneTrafford OR 'One Trafford'"      
- #ClimateEmergency: "#ClimateEmergency"   
- COVID-19: "Trafford AND coronavirus OR #coronavirus OR #CoronavirusOutbreak OR COVID19 OR COVID-19 OR #COVID19 OR #COVIDー19 OR #Corvid19uk"       

Tweets published by @TraffordCouncil, @TraffLibraries, @TPAction, or @OneTrafford are excluded from the results.

**Credits**    
This application was built by the [Trafford Data Lab](https://www.trafforddatalab.io/) using the [rtweet](https://cran.r-project.org/web/packages/rtweet) [R](https://www.r-project.org/) package to retrieve tweets and [tidytext](https://cran.r-project.org/web/packages/tidytext) to tokenise them for analysis.   