## Data Sources
### NASA CMR

NASA's Common Metadata Repository (CMR) is a high-performance, high-quality, continuously evolving metadata system that catalogs all data and service metadata records for NASA's Earth Observing System Data and Information System (EOSDIS) and will be the authoritative management system for all EOSDIS metadata. You can obtain any NASA owned publicly available dataset on CMR and can read further about CMR and the CMR API for downloading data using the links below.

[NASA CMR](https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/cmr)
[CMR API Documentation](https://cmr.earthdata.nasa.gov/search/site/docs/search/api.html)

### Worldview
NASA Worldview is an interactive web application that provides over 900 global, full-resolution satellite imagery observations which are updated daily. Users can also get location and time information of some earth science events such as wildfires, volcanoes, algal blooms, etc. 

### Earthdata Search

[Earthdata Search](https://search.earthdata.nasa.gov/search)

NASA’s CMR forms the backbone of a NASA data search engine called Earthdata search. Using this service, you can find satellite datasets and filter them by parameters such as science keywords, dates, platforms and instruments, data format, location, and much more. Using Earthdata search, it will be convenient to find the NASA datasets that you may wish to include for training your model for detecting your chosen phenomena. 


### AWS GOES 16/17

GOES satellites (GOES-16 & GOES-17) from the National Oceanic and Atmospheric Administration (NOAA) provide continuous weather imagery and monitoring of meteorological and space environment data across North America. GOES satellites provide the kind of continuous monitoring necessary for intensive data analysis. Since they stay above a fixed spot on the surface, they are able to provide consistent imagery for severe weather conditions such as tornadoes, flash floods, hailstorms, and hurricanes. 

The ABI sensor hosted in the satellite provides 5-minute raw observations of Continental US (CONUS). These files are stored in compressed NETCDF formats and can be accessed through AWS S3 buckets. Further information about the bucket is available [here](https://registry.opendata.aws/noaa-goes/). The raw files need to be processed for obtaining RGB images. Using the links provided, you will be able to access GOES datasets and incorporate them in your phenomena detection models.

[GOES 16/17 data on AWS](https://registry.opendata.aws/noaa-goes/)
[GOES Documentation](https://docs.opendata.aws/noaa-goes16/cics-readme.html)


### GIBS Worldview

Global Imagery Browse Services (GIBS) provides over 900 datasets of globally available NASA satellite imagery in full resolution. The satellite imagery can be rendered in your own web client or GIS application. The links below provide the extended description and a sample script to download GIBS imagery respectively.

[GIBS Satellite Image Search](https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs)
[MODIS Image Downloader](https://github.com/NASA-IMPACT/data_share/blob/master/examples/url_generator.ipynb)

### Image Labeler documentation and website

The Image Labeler is an interactive application created by the development team at NASA IMPACT designed to help users generate tagged images for machine learning. Images can be uploaded directly, or users can extract images from an interactive satellite map. Labeled images can also be downloaded for training your detection model.

[Image Labeler Tool](https://labeler.nasa-impact.net)
[Image Labeler Documentation](https://nasa-impact.github.io/image_labeler_docs/html/index.html#)


