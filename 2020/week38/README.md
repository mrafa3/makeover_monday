# Makeover Monday  
Repo for Makeover Monday exercise, Week 38 (2020).

[Original post](https://ec.europa.eu/eurostat/en/web/products-eurostat-news/-/EDN-20200422-1)

[data.world site](https://data.world/makeovermonday/2020w38)

[Source metadata](https://ec.europa.eu/eurostat/cache/metadata/en/prc_hicp_esms.htm)

Some highlights:

*  Using `httr::` and `readxl::` packages to pull down data from data.world.
*  Using the `zoo::as.yearmon()` function to convert into a date format.  
*  Experimenting with some small multiples techniques (inspired by kjhealy's COVID-19 visualzation: https://github.com/kjhealy/covid).  
*  Mapping the data to show divergent story from most recent data, which 

Further development:  
*  Creating `year_month` using an intermediate step, but could have used `stringr::` and `lubridate::` for more direct approach.  
*  Mapping (and the mapped story) is preliminary.  
*  Tried to implement `RColorBrewer::` in the map, but had some challenges and moved on.  

![Original visualization](/2020/week38/graphics/yvxBGUv9Q9GJCt6g6pAZ_Price develpment of books in the EU.png)

![](/2020/week38/graphics/eu_ts_viz.png)

![](/2020/week38/graphics/map_viz/png)

![](/2020/week38/graphics/sm_viz.png)

