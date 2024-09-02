# Catch Prediction on EDITO

An R Based Catch Prediction Model. Predicts the catch probabilties of Common Sole and European Plaice in the Belgian part of the North Sea.

This documentation does not describe the Model, only how to generate the proability prediction NetCDFs and how to view them using EDITO.


### Usage

After you have clicked 'Launch',  you will be able to select the amount of resources to use to run the Model.

Select at least 3000 m CPU and 4 GB of RAM.  And Launch

IMPORTANT: while the process is running, in the second paragraph 'Links for netcdf-zarr viewer...'  has the links for the NetCDF outputs created from the Model.  Copy these links for after the process is complete

The process should take roughly 30 min to complete.


### Netcdf-zarr-viewer service on EDITO

To visualize the NetCDF prediction rasters you can use the 'Netcdf-zarr-viewer' service under EDITO services [HERE](https://datalab.dive.edito.eu/catalog/All)

After clicking 'Launch' under 'Inputs' you will a default link is already filled in to visualize a dataset. 

Replace this link with one of the links you copied while the process was running to visualize the predictions: 
ex.  https://minio.lab.dive.edito.eu/oidc-USERNAME/catch-prediction-624623/SOL_predictions_2024-09-02.nc#mode=bytes


### Acknowledgements

https://github.com/itstheclyde

https://ilvo.vlaanderen.be/nl/nieuws/Vissersvaartuig-als-dataplatform-het-VISTools-project

### License

CC-BY-4.0
