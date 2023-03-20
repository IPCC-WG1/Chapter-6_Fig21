##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is Python code to produce IPCC AR6 WGI Figure 21
# Creator: Steven Turnock, Met Office Hadley Centre, UK 
# Contact: steven.turnock@metoffice.gov.uk
# Last updated on: July 20th, 2021 
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: 
#   The script reads in pre-computed multi-model mean regional mean surface PM2pt5 values to produce a time series 
#   of future changes in PM2pt5 concentrations in different CMIP6 scenarios
# - Input data: 
#   pre-computed data files are as follows and are available for access:
#   Surf_PM2pt5_data_05_14_mean_for_IPCC_figure_V1_5mods.csv - present day multi-model regional mean values
#   Surf_PM2pt5_data_fut_mean_for_IPCC_figure_V1_5mods.csv - future multi-model surface PM2pt5 concentrations in different CMIP6 scenarios 
#   Surf_PM2pt5_SD_data_fut_mean_for_IPCC_figure_V1_5mods.csv - standard in future multi-model surface PM2pt5 concentrations in different CMIP6 scenarios
#   
#   The above input data files are available in the CEDA catalogue record: https://catalogue.ceda.ac.uk/uuid/572c9744ddab47fc8a5b938c4a4f7387
# 
- Output variables: 
#   The code plots figure 21 as in Chapter 6 of the WG1 report.
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: Python3.6
# - Landing page to access the software: https://www.python.org/downloads/release/python-360/ 
# - Operating System: N/A
# - Environment required to compile and run: No specific environment required but uses Python packages: Numpy and Matplotlib
#  ----------------------------------------------------------------------------------------------------
#
#  License: Apache 2.0
#
# ----------------------------------------------------------------------------------------------------
# How to cite:
Szopa, S., V. Naik, B. Adhikary, P. Artaxo, T. Berntsen, W.D. Collins, S. Fuzzi, L. Gallardo, A. Kiendler-Scharr, Z. Klimont, H. Liao, N. Unger, and P. Zanis, 2021: Short-Lived Climate Forcers. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 817–922, doi:10.1017/9781009157896.008.
# When citing this code, please include both the code citation and the following citation for the related report component:
########################################################################
