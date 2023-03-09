# Octave_NetCDF
Useful commands of Octave's netcdf module

data  = ncread('test.nc','mydata');
tim = ncread("m13-15.nc","scrum_time");
tim=tim+324504000;
ncwrite("m13-15.nc","scrum_time",tim);
ncwrite("m13-15.nc","time",tim);
