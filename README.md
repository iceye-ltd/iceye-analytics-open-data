# ICEYE Natural Catastrophe Imagery

A CC-licensed dataset in the AWS Open Data Program of ICEYE Synthetic Aperture Radar (SAR) imagery covering a subset of global catastrophes.

<img src="https://github.com/iceye-ltd/iceye-analytics-open-data/blob/main/assets/iceye_snaptshot.png" width=50% >

## Data Catalog Contents

In the AWS open data archive, you will find ICEYE imagery covering certain natural catastrophe events. The table below shows the current data and event details.

| Event        | Bucket      | Contents|
| -------------|-------------|---------|
| Chilean Wildfire (near Valparaiso), February 2024  | `chilean_wildfire_event_february_2024` | `ICEYE_X25_GRD_SM_3370602_20240206T061456.tif`, `ICEYE_X25_SLC_SM_3370602_20240206T061456.h5`|

## Data Product Details

ICEYE Stripmap Ground Range Detected (GRD) geotif and ICEYE Stripmap Singlelook Complex (SLC) hdf5 are included in the bucket. Detailed ICEYE SAR SLC & GRD data product descriptions and details can be found in the online data product documentation [here](https://sar.iceye.com/5.0/).

The product filename components are shown below. The Product ID is a unique identifier of the acquired scene. Processing level is either `SM` for Stripmap or `SLC` for single look complex.

<img src="https://github.com/iceye-ltd/iceye-analytics-open-data/blob/main/assets/filename.png" width=70% >




## Attribution

ICEYE, 2024

## License

CC BY 1.0 
