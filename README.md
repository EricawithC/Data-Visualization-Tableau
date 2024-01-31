# Data-Visualization-Tableau

Link to get to Public Tableau to see the work: https://public.tableau.com/app/profile/erica.francalanci/viz/OlympicGamesAnalysis_17066437740920/MedalsandGDP2-2_0

Here is a preview:
![image](https://github.com/EricawithC/Data-Visualization-Tableau/assets/131587755/5bf99a56-295a-445b-9d0e-4081354524b8)

Let's go more in-depth and analyze how we made the graphs. 
First of all, one graph that needs to be explained is the one regarding the correlation. 
It is important to notice that the x-axis is expressed on a logarithmic scale for the following  reason: logarithmic scale compresses this wide range of values, making it easier to visualize and compare the economic sizes of different countries, addressing data sparsity, especially if compared with a discrete value, such as the number of medals. 

For the same reason, the model type of the trend line is logarithmic. 

Moreover, another important aspect is the variables of the Medal per Event. In here we use the calculated field named by Medal per Even, the goal of the formulation is to count just one medal per team and in individual sports. 

The decision to use a logarithmic scale on the x-axis in the correlation graph is justified to handle the wide range of GDP values, address data sparsity in the context of discrete medal counts, reduce skewness caused by extreme GDP values, ensure proportional representation for meaningful comparisons, and accommodate potential non-linear relationships between GDP and the number of medals. In summary, logarithmic scaling enhances visual clarity and facilitates accurate analysis of the correlation between GDP and medal counts across countries.

