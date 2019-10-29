# Data-Analytics-with-R
This Repository discusses the modeling tools and the methods of data mining. I used this time R which requires the user to write out simple instructions.

Data analytics should be viewed as a "process". As with all good statistical analyses, one needs to be clear about the purpose of the analysis. Just to "analyse and mine data" without a clear purpose, without an appreciation of the subject area, and without a modeling strategy will usually not be successful.

The data analysis process involves several interrelated steps:
- Efficient data storage and data preprocessing steps are very critical to the success of the analysis.
- One needs to select appropriate response variables and decide on the number of variables that should be investigated.
- The data needs to be screened for outliers, and missing values need to be addressed (with missing values either omitted or appropriately imputed through one of several available methods).
- Data sets need to be partitioned into training and evaluation data sets. In very large data sets, which cannot be analyzed easily as a whole, data must be sampled for analysis.
- Before applying sophisticated models and methods, the data need to be visualized and summarized. It is often said that a picture is worth a 1000 words. Basic graphs such as line graphs for time series, bar charts for categorical variables, scatter plots and matrix plots for continuous variables, box plots and histograms (often after stratification on useful covariates), maps for displaying correlation matrices, multidimensional graphs using color, trellis graphs, overlay plots, tree maps for visualizing network data, and geo maps for spatial data are just a few examples of the more useful graphical displays. In constructing good graphs, one needs to be careful about the right scaling, the correct labeling, and issues of stratification and aggregation.
- Summary of the data involves the typical summary statistics such as mean, percentiles and median, standard deviation, and correlation, as well as more advanced summaries such as principal components.
- Appropriate methods from the data mining tool bag need to be applied. Depending on the problem, this may involve regression, logistic regression, regression/classification trees, nearest neighbor methods, k-means clustering, and so on.
- The findings from these models need to be confirmed, typically on an evaluation (test or holdout) data set.
- Finally, the insights one gains from the analysis need to be implemented. One must act on the findings and spring to action. This is what W.E. Deming had in mind when he talked about process improvement and his Deming (Shewhart) wheel of “plan, do, check, and act” (Ledolter and Burrill, 1999).

Data preparation often takes a lot more time than the eventual modeling. The subsequent modeling is usually only a small component of the overall effort; quite often, relatively simple methods and a few well-constructed graphs can tell the whole story.
