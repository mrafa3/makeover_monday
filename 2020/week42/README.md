# Makeover Monday  
Repo for Makeover Monday exercise, Week 42 (2020).

[Original post](https://data.oecd.org/healthres/health-spending.htm)

[data.world site](https://data.world/makeovermonday/2020w42)

**Source metadata**: 
>>Health spending measures the final consumption of health care goods and services (i.e. current health expenditure) including personal health care (curative care, rehabilitative care, long-term care, ancillary services and medical goods) and collective services (prevention and public health services as well as health administration), but excluding spending on investments. Health care is financed through a mix of financing arrangements including government spending and compulsory health insurance (“Government/compulsory”) as well as voluntary health insurance and private funds such as households’ out-of-pocket payments, NGOs and private corporations (“Voluntary”). This indicator is presented as a total and by type of financing (“Government/compulsory”, “Voluntary”, “Out-of-pocket”) and is measured as a share of GDP, as a share of total health spending and in USD per capita (using economy-wide PPPs).

## Notes  

Some highlights:

*  I chose to replicate the graphic with some small design adjustments (and to highlight the out-of-pocket healthcare costs).  
*  I used the `countrycode::` package to gather the full name for each country. The source data uses the iso3 code only.  

Further development:  

*  Because the data are longitudinal, I could do a lollipop plot showing the change in expenditure by country over time. I began working on this, but the wrangling for this is somewhat complex and I ran out of time

## Visualization  

**Original visualization**:

*  By showing this in total amount per capita, you can see where in the world the cost varies most significantly. The story of the runaway costs in the US is there, but it seems to be lost by this choice of visualization.  
*  If the scale showed the proportions of out-of-pocket vs. government/compulsory, there would be other interesting stories (it appears that South Africa and Cyprus have greater out-of-pocket expenses).  
*  The x-axis is difficult to see because of the angled labels.  
*  A scatterplot with GDP per capita would be an interesting way to show how countries may be outliers given their levels of development.  

![](https://media.data.world/bflpGloGRpSN4rv23cRM_Screen%20Shot%202020-10-18%20at%202.48.13%20pm.png)

**Alternatives developed**:

![](https://github.com/mrafa3/makeover_monday/blob/master/2020/week42/graphics/healthexp_bar_viz.png)

![]()

![]()

**Example(s) to learn from**:  

![]()
