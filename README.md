# CA-Wildfires-2010-2017
A closer look at California Wildfires and their causes from 2010-2017

This project used data from Cal Fire's Redbooks. The data was only available for indivudual years in a pdf format so I used a python library to convert the pdf to a csv file and had to do some additional cleaning. Then each year was merged into a single dataframe for analysis. 

I used a seperate python library to get geocodes for each fire district using only the zipcode. 

I created a map to see where most fires happened in the state throughout the period. The map also displays power lines using shapefiles from the state energy commission.

You can explore the map here:
https://jason-dorman.github.io/CA-Wildfires-2010-2017/

<iframe width="100%" height="520" frameborder="0" src="https://nbcuniversal.carto.com/u/nbc-sandiego/builder/4461c79f-d3da-4258-912c-d1dc7031ff79/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

<iframe title="WILDFIRES CAUSED BY POWER LINES" aria-label="Interactive line chart" id="datawrapper-chart-rtmSt" src="//datawrapper.dwcdn.net/rtmSt/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>
