---
layout: post
title: Characterizing Marine Heatwaves
subtitle: A Case Study for Padilla Bay, WA
gh-repo: cmurray187/cmurray187.github.io
gh-badge: [star, fork, follow]
tags: [research,heatwave,PadillaBay]
comments: true
---
## **Marine Heatwaves in the PNW**

Marine heatwaves are increasing in severity and frequency and pose a serious threat to marine life. Experimental exposures that test physiological tolerance limits can identify vulnerable taxa, but useful experiments require a robust characterization of regional heatwave dynamics. In advance of my 2020 winter experiments on Pacific herring early life-stages, I analyzed an 18 year NEERS dataset from the Ploeg Monitoring Station in [Padilla Bay, WA](https://coast.noaa.gov/nerrs/reserves/padilla-bay.html). The station is situated within a large sea grass system and is representative of typical herring spawning habitat (48°33'22.8"N 122°31'51.2"W).

<img src="https://github.com/cmurray187/cmurray187.github.io/blob/master/notebook%20images/Heatwaves/PloegChannel_map.PNG" width="300" height="300">

I used the R package [HeatwaveR](https://robwschlegel.github.io/heatwaveR/) to detect heatwave events as defined by [Hobday et al. (2016)](https://www.sciencedirect.com/science/article/abs/pii/S0079661116000057) which is an anomalous event that lasts for five or more days with temperatures warmer than the 90th percentile of a long-term seasonal climatology. The authors recommend a minimum 30-year dataset, but the longest publicly available dataset from a seagrass habitat from the Salish Sea ecosystem was 18 years. I set HeatwaverR to test daily mean temperatures from 1992-2019 (dataset deposited [here](https://github.com/cmurray187/Fish-Ecophysiology/blob/master/Heatwave%20Analysis/PadBay.xlsx)). 





## Padilla Bay Heatwave
<img src="https://raw.githubusercontent.com/cmurray187/Fish-Ecophysiology/master/Heatwave%20Analysis/figs/Padilla%20Bay%20heatwave%20events.png" width="400" height="400">{: .mx-auto.d-block :}




Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
