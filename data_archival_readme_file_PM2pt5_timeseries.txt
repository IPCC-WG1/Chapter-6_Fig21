# Creation date (YYYY-MM-DD): 2021-07-21 
# File created by: Steven Turnock
# email: steven.turnock@metoffice.gov.uk
# ========================
# GENERAL INFORMATION 
# 
# *Title - Future changes in regional 5-year mean surface PM2.5 from 2015 to 2100 in different shared socio- economic pathways (SSPs)
# Readme for data for Figure XXXX in the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter XXXX 
# 
# *Data creators
# Name: Steven Turnock
# Institution: Met Office Hadley Centre
# email: steven.turnock@metoffice.gov.uk
#
# *Comments
# Future response of annual mean PM2.5 concentrations across different regions over the period 2015 to 2100 from an ensemble of five CMIP6 models and the TM5-FASST model in different future CMIP6 scenarios. 
#
# ========================
# DATA & FILE OVERVIEW
#
# List of all files and subfolders
# 
# --------------------------
# Panel - all panels
#
# --------------------------
# filename 1: ‘Surf_PM2pt5_data_05_14_mean_for_IPCC_figure_V1_5mods.csv’
# -----------------------
#
# N° of columns: 14
# Column headings: Year, Scenario, Type, Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
#        
#
# column_name 1: Year
# long_name: year
# units: year
# missing_value: 
# type (int/float/char): int
# comments: year for annual mean
#
# column_name 2: Scenario
# long_name: scenario
# units: 
# missing_value: 
# type (int/float/char): char
# comments: CMIP6 future scenario for which annual mean concentrations are calculated
#
# column_name 3: type
# long_name: type_of_metric
# units: 
# missing_value: 
# type (int/float/char): char
# comments: identifying whether it is an annual mean or standard deviation that has been calculated
#
# row_name 1: multi-model mean 
# long_name: multi-model_annual_mean_surface_PM2pt5_concentration
# units: micro-gram m-3
# missing_value: Nan 
# type (int/float/char): float
# comments: annual mean surface PM2.5 concentrations calculated over the period 2005 to 2014 across different regions from an ensemble of 5 different CMIP6 models
#
# row_name 2: Standard deviation 
# long_name: standard_deviation_of_the_multi-model_annual_mean_surface_PM2pt5_concentration
# units: micro-gram m-3
# missing_value: Nan 
# type (int/float/char): float
# comments: standard deviation in the annual mean surface PM2.5 concentrations calculated over the period 2005 to 2014 across different regions from an ensemble of 5 different CMIP6 models
#
# --------------------------
# filename 2: ‘Surf_PM2pt5_data_fut_mean_for_IPCC_figure_V1_5mods.csv’
# -----------------------
#
# N° of columns: 13
# Column headings: Year, Scenario, Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
#        
#
# column_name 1: Year
# long_name: year
# units: year
# missing_value: 
# type (int/float/char): int
# comments: year for annual mean
#
# column_name 2: Scenario
# long_name: scenario
# units: 
# missing_value: 
# type (int/float/char): char
# comments: CMIP6 future scenario for which annual mean concentrations are calculated
#
# column_name 3: Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
# long_name: change_in_annual_mean_surface_PM2pt5_concentration
# units: micro-gram m-3
# missing_value: Nan
# type (int/float/char): float
# comments: annual mean change in surface PM2.5 concentrations calculated across different regions from an ensemble of 5 different CMIP6 models across different CMIP6 future scenarios 
#
# --------------------------
# filename 3: ‘Surf_PM2pt5_SD_data_fut_mean_for_IPCC_figure_V1_5mods.csv’
# -----------------------
#
# N° of columns: 13
# Column headings: Year, Scenario, Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
#        
#
# column_name 1: Year
# long_name: year
# units: year
# missing_value: 
# type (int/float/char): int
# comments: year for annual mean
#
# column_name 2: Scenario
# long_name: scenario
# units: 
# missing_value: 
# type (int/float/char): char
# comments: CMIP6 future scenario for which annual mean concentrations are calculated
#
# column_name 3: Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
# long_name: standard_deviation_of_change_in_annual_mean_surface_PM2pt5_concentration
# units: micro-gram m-3
# missing_value: Nan
# type (int/float/char): float
# comments: standard deviation in the annual mean change in surface PM2.5 concentrations from an ensemble of 5 different CMIP6 models calculated across different regions in different CMIP6 future scenarios 
#
# --------------------------
# filename 4: ‘Regional_annual_mean_surface_PM2pt5_resp_values_CMIP6_Fut_Scens_from_TM5_FASST_on_AR6_reg_receptors_INCL_GLOB_2015_2100.txt’
# -----------------------
#
# N° of columns: 13
# Column headings: Year, Scenario, Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
#        
#
# column_name 1: Year
# long_name: year
# units: year
# missing_value: 
# type (int/float/char): int
# comments: year for annual mean
#
# column_name 2: Scenario
# long_name: scenario
# units: 
# missing_value: 
# type (int/float/char): char
# comments: CMIP6 future scenario for which annual mean concentrations are calculated
#
# column_name 3: Africa, Asia-Pacific Developed, Eastern Asia, Europe, Eurasia, Latin America and Carribean, Middle East, North America, Southern Asia, South-East Asia and Developing Pacific, Global
# long_name: change_in_annual_mean_surface_PM2pt5_concentration
# units: micro-gram m-3
# missing_value: Nan
# type (int/float/char): float
# comments: annual mean change in surface PM2.5 concentrations from the TM5-FASST model calculated across different regions in CMIP6 future scenarios 
#