# Makeover Monday  
Repo for Makeover Monday exercise, Week 41 (2020).

[Original post](https://www.dataiq.co.uk/market-insight/data-assets-and-data-culture)

[data.world site](https://data.world/makeovermonday/2020w41-data-assets-and-data-culture/workspace/project-summary)

[Source metadata](https://data.world/makeovermonday/2020w41-data-assets-and-data-culture/workspace/data-dictionary)

## Notes  

Some highlights:

*  Simple and aesthetically clean visualization that uses the `jkmisc::theme_jk()` function to have a colored subtitle to allow without a legend.  
*  I have some code experimenting with `coord_polar()`, which looks cool, but I think detracts too much from a pretty clean takeaway.  
*  Experimented with creating a donut plot of the same takeaway, but it is incomplete.  

Further development:  


## Visualization  

*  Original visualization does not use color effectively. For instance, shades or blue are not related to one another. The number of colors is also well above what can be visually perceived.  
*  It also fails to use order in any meaningful way.
*  I like that the legend lines up with the start of each bar and that they show the percentages for each category.  
*  The polar coordination is aesthetically interesting, but doesn't lend anything to the analysis (or have any visual metaphor).  
*  I wonder if there might be any aggregation of categories that could make this more easy to digest.  

**Original visualization**:

![](https://learningtableaublog.files.wordpress.com/2020/10/screenshot-2020-10-10-at-17.47.16.png)

**Alternatives developed**:

![](https://github.com/mrafa3/makeover_monday/blob/master/2020/week41/graphics/respondents_plot.png)

![]()

![]()

**Example(s) to learn from**:  

![]()
