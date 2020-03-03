# Pymaceuticals-Capomulin-Summary
# Disclaimer!:
## All data shown and used in this excersize is fake as is the purported company that ran the tests. __DO NOT__ use this information as fact, research of any kind, or medical advice. This is strictly an excercize in coding, data analysis, and statistics. 

## [Pymaceuticals.ipynb](Pymaceuticals.ipynb)
Provides a statistical overview of the data collected on a series of tests performed by Pymaceuticals Inc. to determine the effectiveness of Capomulin in the treatment of Squamous Cell Carcinoma (SCC).
### Summary Statistics
Provides an overview of the average tumor size and growth over time in the mice that survived testing for each of the SCC treatments tested. 
#### Treatments Tested
* Capomulin
* Ceftamin
* Infubinol
* Ketapril
* Naftisol
* Placebo
* Propriva
* Ramicane
* Stelasyn
* Zoniferol
### Bar Plots
Bar plots used to show the total number of data points for each Treatment tested. "Data Points" refers to each mouse at each timepoint tested. *Data summarized in this report are for mice that had data recorded at every timepoint*.
### Pie Charts
Pie charts used to show the distribution of mice per sex in the study.
### Box Plots
Box plots used to show the four best performing drug regimens based on the average final tumor size in cubic milimeters. The two plots show both the total spread of final tumor sizes for all mice in these regimens as well as the spread per regimen.
#### Four Best Drug Regimens
* Capomulin
* Ceftamin
* Infubinol
* Ramicane
## [/Images](Images)
Collection of plots created in [Pymaceuticals.ipynb](Pymaceuticals.ipynb) saved in .png format for quick reference.
* [/Barplots](Images/Barplots)
Bar plots showing the number of data points per treatment regimen tested.
  * [Pandas Barplot](Images/Barplots/barplot_pandas.png)
 Bar Plot created using Pandas.
  * [Matplotlib Barplot](Images/Barplots/barplot_matplotlib.png)
Bar plot created using Matplotlib.
* [/Piecharts](Images/Piecharts)
Pie charts showing the distribution of sexes among the test mice.
  * [Pandas Piechart](Images/Piecharts/piechart_pandas.png)
  Pie chart created using Pandas.
  * [Matplotlib Piechart](Images/Piecharts/piechart_matplotlib.png)
  Pie chart created using matplotlib.
 * [/Boxplots](Images/Boxplots)
 Box plots showing the distribution of final tumor sizes by drug regimen. *Only the four best testing drug regimens are shown*
  * [Distribution of all mice](Images/Boxplots/all_mice_boxplot.png)
  Shows the distribution of tumor sizes for all mice in the four best drug regimens.
  * [Distribution by Drug Regimens](Images/Boxplots/tumor_volume_by_regimen.png)
  Shows the distribution of tumor sizes for the mice in each drug regimen within the four best testing regimens.
## Built With
* Jupyter Notebook
* Python
* Pandas
* Matplotlib.pyplot
* Scipy.stats
## Authors
* Ryan Klueg
