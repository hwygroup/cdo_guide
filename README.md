# cdo_guide
######################################################
# generate interpolating coefficients between two different grids:
cdo griddes ftp.ceda.ac.uk/badc/cmip5/data/cmip5/output1/NCAR/CCSM4/historical/mon/ocean/Omon/r1i1p1/latest/tos/tos_Omon_CCSM4_historical_r1i1p1_185001-200512.nc > pop_grid
cdo genbil,pop_grid ftp.ceda.ac.uk/badc/cmip5/data/cmip5/output1/LASG-CESS/FGOALS-g2/amip/mon/atmos/Amon/r1i1p1/latest/pr/pr_Amon_FGOALS-g2_amip_r1i1p1_197901-198812.nc test.nc
######################################################
