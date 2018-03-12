# WindTurbineHighSpeedBearingPrognosis-Data
Dataset for "Wind Turbine High-Speed Bearing Prognosis" example in Predictive Maintenance Toolbox.

The data is sourced from http://data-acoustics.com/measurements/bearing-faults/bearing-3/.

The data is provided under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). Mathworks Inc. has obtained permission from the data owner [Eric Bechhoefer](mailto:eric@gpms-vt.com) to use the data for commercial purpose. Please contact the owner [Eric Bechhoefer](mailto:eric@gpms-vt.com) for any other commercial uses.

## Instructions
- Click **'Clone or download'** button of the repository and select **'Download Zip'**. Save the zip file in the same directory as the example live script. Then run the live script.
- Alternatively, if you have git installed, at the command line go to the folder containing the example live script and type ```git clone https://github.com/mathworks/WindTurbineHighSpeedBearingPrognosis-Data.git```. Rename the folder to ```WindTurbineHighSpeedBearingPrognosis-Data-master```. Run the live script starting from the 'Data Import' section.

## Modification of the original data
The original data is in the format of ```sensor-[timestamp].mat``` and ```tach-[timestamp].mat```. This repository has merged the two pieces of data with the same timestamp into a single mat file named in the format of ```data-[timestamp].mat```.
