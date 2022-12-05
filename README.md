# rainfall_analysis
This repository contains an analysis of average rainfall (mm) in Oxford (UK) and Melborne (Aus) from 1855 to 2015.

The two files of data found in 'data' were combined using the Rscript combine-data.R found in 'src'. 
This combined data can be found in the file average-rainfall.csv in 'combined_data'.

To run this analysis use the following command:

'''
Rscript src/make-plot.R
'''

The input data is in 'combined_data' and the results are in 'out'.
