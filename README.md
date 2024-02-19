# Soil-Moisture-Prediction 

Using LSTMs. 

Data : Soil moisture remote sensing data, Forschungszentrum Julich (Germany, 2013)

Features:

* time: Timestamp of the observation.
* latitude: Latitude coordinate of the observation location.
* longitude: Longitude coordinate of the observation location.
* clay_content: Percentage of clay content in the soil.
* sand_content: Percentage of sand content in the soil.
* silt_content: Percentage of silt content in the soil.
* sm_aux: Soil moisture observation from the SMOS-ASCAT satellite (smoothed).
* sm_tgt: Soil moisture observation from the AMSR satellite.
