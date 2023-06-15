A quick look at daily minimum and maximum temperatures under GeoMIP scenarios. Inspired by wondering if there is a clear signal for night-time undercooling under SAI, as might be assumed given that the SW forcing of SAI is limited to the day time, but the LW forcing of CO2 still occurs at night. 

There isn't much in the literature on night temps (daily tmnin) under SAI.

Govindasamy et al., 2003.: 
> One might expect, [...], that a geoengineered CO2-laden world would have less of a diurnal cycle
 
Lunt et al., 2008 refer to the fact they looked at the diurnal cycle and found a relatively minor effect, except in dry regions where it can be somewhat larger:
> in dry regions such as the Gobi and Sahara deserts, there are reductions in diurnal cycle up to 1.5°C.


The code here is makes a start at assessing diurnal cycle changes in the GeoMIP ensemble, but doesn't fully answer the question. 

The figures below are annual means daily tmin and tmax fiels, spatially averaged over **land only** in the region 20S to 20N, where diurnal cycle is generally large. Only UKESM-1-0-LL is shown. 



Next steps: 


* quantify residual tmin change, and its statistical significance
* make maps showing regions of change - we might expect the largest signal in dry, hot (and high altitude?) places (e.g. the tibetan plateau) which have the largest diurnal temperature range. 
* Add GLENS data or more GeoMIP models 
* Cloud cover change is likely to dominate any signal from the direct SAI SW forcing. So, any fuller treatment would need to account for this. Perhaps as a first step, look at the regional cloud cover changes under SAI and test how strongly they correlate to the local tmin variation. Also could potentially look at the tmin residual changes in only those regions that see small changees in cloud cover. 
* It might also be interesting to look at tmin during heatwaves/the hottest season. This is when human health impacts would be expected to be strongest, and also might reduce the impacts of cloud changes dominating the signal. 

Before doing this though, it would be worth chatting to others about how interesting this is, and in particular, drawing up the theory for what order of magnitude efffect size we expect given the SW forcing in these scenarios. How large an ensemble/long a simulation do we expect to need given a ball-park order of magnitude estimate of the effect size? 


It seems there may be a small signal for under-restoration of tmin in G1, but would need to investigate the statistics of change further, and look spacially to be sure. G6sulfur is difficult to interpret because there is a background tropical overcooling, which needs to be accounted for, and isn't accounted for in these plots. 

N.B Code will only run Jasmin, since it refers to the CEDA file system.  

![summary_DTR_under_SAI](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/3f2d3f7f-8c7d-4450-ab27-88bf37196e53)


![image](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/c631d073-b9e6-42a7-aa21-6e3ac68f9ece)

![image](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/7554d61c-ce68-406e-a519-d5c2aed62347)


![image](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/da8eca37-211c-4dc8-9efb-36197a7bffc8)

![image](https://github.com/alistairduffey/Night_temps_under_SAI/assets/47328986/fa1bfc49-927d-49ab-858f-356d33cf0a50)

