A quick look at daily minimum and maximum temperatures under GeoMIP scenarios. Inspired by wondering if there is a clear signal for night-time undercooling under SAI, as might be assumed given that the SW forcing of SAI is limited to the day time, but the LW forcing of CO2 still occurs at night. 

The code here is a start, but doesn't really answer the question. 

Next steps: 


* quantify residual tmin change, and its statistical significance
* make maps showing regions of change - we might expect the largest signal in dry, hot (and high altitude?) places (e.g. the tibetan plateau) which have the largest diurnal temperature range. 
* Add GLENS data or more GeoMIP models 
* Cloud cover change is likely to dominate any signal from the direct SAI SW forcing. So, any fuller treatment would need to account for this. Perhaps as a first step, look at the regional cloud covver changes under SAI and test how strongly they correlate to the local tmin variation. Also could potentially look at the tin residual changes in only those regions that see small changees in cloud cover. 

Before doing this though, it would be worth chatting to others about how interesting this is, and in particular, drawing up the theory for what order of magnitude efffect size we expect given the SW forcing in these scenarios. How large an ensemble/long a simulation do we expect to need given a ball-park order of magnitude estimate of the effect size? 

![image](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/da8eca37-211c-4dc8-9efb-36197a7bffc8)

![image](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/fa1bfc49-927d-49ab-858f-356d33cf0a50)

It seems there may be a small signal for under-restoration of tmin in G1, but would need to investigate the statistics of change further, and look spacially to be sure. G6sulfur is difficult to interpret because there is a background tropical overcooling, which needs to be accounted for, and isn't accounted for in these plots. 

Code to runs Jasmin, using the CEDA file system 
