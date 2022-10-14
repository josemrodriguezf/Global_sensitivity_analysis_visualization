This repository has an example to plot Sobol First Order, Total Order, and Second Order sensitivity indices in a chord diagram plot and using heat map. In this example I obtained the indices using SAlib python library (Herman et al, (2017), SALib: An open-source Python library for Sensitivity Analysis, Journal of Open Source Software, 2(9), 97, doi:10.21105/joss.00097), which can be downloaded at https://salib.readthedocs.io/en/latest/. 

This code was used to visualize the results from the paper _"Global Sensitivity Analysis of a Coupled Hydro-Economic Model and Groundwater Restriction Assesment"_ that you can referene as: Rodríguez-Flores, J.M., Valero Fandiño, J.A., Cole, S.A. et al. Global Sensitivity Analysis of a Coupled Hydro-Economic Model and Groundwater Restriction Assessment. Water Resour Manage (2022). https://doi.org/10.1007/s11269-022-03344-5

Available at: https://link.springer.com/article/10.1007/s11269-022-03344-5  

### Follow the example in the Rmarkdown file using the files in the repo, change it and use your own results they can be from SALib or any output that has the same format as in the example.

The visualization follows the next layout, where the Second order index (S2) are the ribbons of the diagram, First Order (S1) and Total order (ST) are depicted as circular rectangles for each variable. If you want more information on how to interprepate the results look at Andrea Saltelli's books and papers (http://www.andreasaltelli.eu/Articles)

![](https://github.com/joserdgz8/Global_sensitivity_analysis_visualization/blob/main/chord_diagram_legend.png)

### Example: 

![](https://github.com/joserdgz8/Global_sensitivity_analysis_visualization/blob/main/EXAMPLE.png)



