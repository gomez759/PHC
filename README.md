### CMF-Dashboard 
CMF dashboard visualizes the impact from the Prop 56 grant program called CalMedForce which uses money from tobacco taxes to fund graduate medical education programs in california. To view the dashboard click on the following link https://fernandogomez759.shinyapps.io/CMF_dashboard/?_ga=2.56406187.1098680858.1646804984-501163498.1646804984

### CHC-Maps
Our sister program, called CalHealthCares, reached out to me to create maps for them visualizing the impact their program has had on the State of California since it started.
To view the maps click on the following maps, "cohort_1_physicians_top_10", "cohort_2_physicians_top_8", "cohort_3_physicians_top_8".

### Stringr Manipulation
One of my task is to download and manipulate the spreadsheet called "finance_table.csv". However, the spreadsheet containns a XML table within every cell in the "Table 1: Expenses for this Reporting Period". What I did is I manipulated the XML to remove unnecessary characters, and to delineate by line items. Once I delineated by line item I then used the "pivot_longer" function to transpose long ways to make the data easier to analyze. The final product of the spreadsheet is called "sar_financial_report.csv". The folder called "stringr manipulation" shows my steps.
