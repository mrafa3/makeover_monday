# Makeover Monday  
Repo for Makeover Monday exercise, Week 40 (2020).

[Original post](https://www.visualcapitalist.com/3d-map-the-u-s-cities-with-the-highest-economic-output/)

[data.world site](https://data.world/makeovermonday/2020w40-the-us-cities-with-the-highest-economic-output)

[Source metadata](https://www.bea.gov/data/gdp/gdp-county-metro-and-other-areas)

## Notes  

Some highlights:

*  Used `ggtext::element_markdown()` in my ggplot labels for having a horizontal y-axis label for better legibility.  
*  Used `lead()` and `zoo::rollmean()` to calculate a moving average to show a smooth historical line plot.  

Further development:  

*  Could do which metro faired the worst in the 2008 financial crisis (maybe a dumbbell plot to show the largest falls).  
*  Original analysis appears to have connected counties to produce the analysis. It would be interesting to replicate that method, because it does change the conclusions.  
*  This dataset provides a way to explore the question, "what growth rates are possible to see at smaller geographies"? This is a question that came up in the context of our work in Northeast Nigeria.  

## Visualization  

**Original visualization**:

*  The spike shows the relative magnitude of NYC well, but not much else.  
*  If you just look at the placement of the spikes, it does illustrate the concentration in California and on the east coast. However, I don't think that mapping this is very effective. Given that this is data on metro areas, there is going to be lots of unused space, and I don't think the map is the clear takeaway.  


![us-metro-areas-by-gdp.png](https://www.visualcapitalist.com/wp-content/uploads/2020/09/us-metro-areas-by-gdp.jpg)

**Alternatives developed**:

![](https://github.com/mrafa3/makeover_monday/blob/master/2020/week40/graphics/ma3_top3_viz.png)

![](https://github.com/mrafa3/makeover_monday/blob/master/2020/week40/graphics/top3_over_time_viz.png)

![]()

**Example(s) to learn from**:  

![]()
