##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is Python code to produce IPCC AR6 WGI Figure 20
# Creator: Steven Turnock, Met Office Hadley Centre, UK 
# Contact: steven.turnock@metoffice.gov.uk
# Last updated on: July 20th, 2021 
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: 
#   The script reads in pre-computed multi-model mean regional mean surface O3 values to produce a time series 
#   of future changes in O3 concentrations in different CMIP6 scenarios
# - Input data: 
#   pre-computed data files are as follows and are available for access:
#   Surf_O3_data_05_14_mean_for_IPCC_figure_V1_5mods.csv - present day multi-model regional mean values
#   Surf_O3_data_fut_mean_for_IPCC_figure_V1_5mods.csv - future multi-model surface O3 concentrations in different CMIP6 scenarios 
#   Surf_O3_SD_data_fut_mean_for_IPCC_figure_V1_5mods.csv - standard in future multi-model surface O3 concentrations in different CMIP6 scenarios

    The above input data files are available in the CEDA catalogue record: https://catalogue.ceda.ac.uk/uuid/022d449b91eb453eb56228c17fdce725 .

# - Output variables: 
#   The code plots figure 20 as in Chapter 6 of the WG1 report.
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
# When citing this code, please include both the code citation and the following citation for the related report component:
########################################################################
