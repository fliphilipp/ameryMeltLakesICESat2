# Revisiting surface melt on Amery Ice Shelf, East Antarctica, with ICESat-2

## Data availability:
- The estimated depths for all algorithms and the manual method are compiled in [this CSV file](https://raw.githubusercontent.com/fliphilipp/ameryMeltLakesICESat2/master/data/allCompiledDepthData.csv). 
- The ICESat-2 ATL03 and ATL06 data is available at [NSIDC](https://nsidc.org/data/icesat-2/data-sets).
- Sentinel-2 Imagery used for the plots is accessible through the [Copernicus Open Acces Hub](https://scihub.copernicus.eu/) or [Amazon Web Services S3](https://registry.opendata.aws/sentinel-2/). 

---

## Figures:
![area map with ICESat-2 ground track and ATL03/06 data](https://github.com/fliphilipp/ameryMeltLakesICESat2/blob/master/figs/Fig1_amery_melt_map_photons.png)
*Left: Sentinel-2 image over Amery Ice Shelf, 2 January 2020 showing ICESat-2 ground track 0081 acquired on the same day. The magnified areas show the four melt lakes considered in this study. Right: ATL03 data for the four melt lakes on the left, with each photon colored by it’s confidence level for being a land-ice surface signal. ATL06 surface elevations are shown in orange.*

---

![comparison between different algorithms](https://github.com/fliphilipp/ameryMeltLakesICESat2/blob/master/figs/Fig2_amery_melt_comparison.png)
*Left: ICESat-2 ATL03 photon data over the meltwater lakes used in this study, with median depth estimates from the ICESat-2 algorithms at each location shown in red. Above each plot are the corresponding Sentinel-2 images, with the ICESat-2 ground track segment. Right: Comparison of depth estimate retrievals for each lake. To aid visual comparison, image-based estimates have been multiplied by refractive index, and background topography has been removed.*
