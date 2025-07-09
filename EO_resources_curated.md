# Earth Observation (#EO) resources: a curated list

*compiled by Emil A. Cherrington, Ph.D. | last updated: 9 July 2025*

## Portals and platforms for EO data

* U.S. National Aeronautics & Space Administration (NASA)
  * [NASA EOSDIS WorldView](https://worldview.earthdata.nasa.gov/)
  * [NASA Giovanni](https://giovanni.gsfc.nasa.gov/giovanni/)
  * [NASA EarthData Search](https://search.earthdata.nasa.gov/search)
  * [NASA  OB.DAAC L3 / L4 browser](https://oceandata.sci.gsfc.nasa.gov/l3/)
  * [NASA ASF DAAC](https://search.asf.alaska.edu/#/)
  * [NASA AppEEARS](https://appeears.earthdatacloud.nasa.gov/)
* United States Geological Survey (USGS)
  * [USGS Glovis](https://glovis.usgs.gov/app)
  * [USGS ESPA](https://espa.cr.usgs.gov/)
* European Commission's Copernicus Programme + European Space Agency (ESA)
  * [Copernicus Browser](https://browser.dataspace.copernicus.eu/)
  * [Copernicus Land Monitoring Service](https://land.copernicus.eu/en)
* Commercial
  * [Maxar Discover](https://discover.maxar.com/)
  * [Planet Explorer](https://www.planet.com/explorer/)
    * [Planet Education & Research Program application](https://www.planet.com/industries/education-and-research/#apply-now)

## Hyperspectral data resources
* Missions
  * NASA missions
    * [EO-1 Hyperion, 2001-2017](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-earth-observing-one-eo-1-hyperion)
      * [EO-1 data in GEE](https://developers.google.com/earth-engine/datasets/catalog/EO1_HYPERION)
    * [Earth Surface Mineral Dust Source Investigation (EMIT), 2022-present](https://earth.jpl.nasa.gov/emit/)
      * [EMIT data in GEE](https://developers.google.com/earth-engine/datasets/catalog/NASA_EMIT_L2A_RFL)
    * [Plankton, Aerosol, Cloud, ocean Ecosystem (PACE), 2024-present](https://pace.oceansciences.org/)
    * [Surface Biology & Geology (SBG), proposed](https://sbg.jpl.nasa.gov/)
  * EOportal.org [hyperspectral mission list](https://www.eoportal.org/other-space-activities/hyperspectral-imaging)
* GitHub code repositories
  * [BzGEO's PACE OCI toolkit (2025)](https://github.com/BzGEO/pace_oci_toolkit)
    * [GEE code repo](https://bit.ly/gee_repo_pace_oci)
  * [BzGEO's Hyperspectral toolkit (2025)](https://github.com/BzGEO/hyperspectral_toolkit)
    * [GEE code repo](https://bit.ly/gee_repo_hyperspectral)
  * []()

## Spotlight: Hyperspectral data from NASA's PACE
* [PACE mission page](https://pace.oceansciences.org/)
  * [Ocean Color Instrument (OCI)](https://pace.oceansciences.org/oci.htm)
* Data access
  * [NASA  OB.DAAC L3 / L4 browser](https://oceandata.sci.gsfc.nasa.gov/l3/)
  * [NASA EarthData Search: PACE OCI](https://search.earthdata.nasa.gov/search?fi=OCI&as[platforms][0]=Space-based%20Platforms%3AEarth%20Observation%20Satellites%3A%3APACE&as[instrument][0]=OCI&fpb0=Space-based%20Platforms&fpc0=Earth%20Observation%20Satellites&fps0=PACE)
* PACE data products
  * [PACE data products list](https://pace.oceansciences.org/data_table.htm)
  * [Data description: Surface reflectance](https://oceancolor.gsfc.nasa.gov/data/10.5067/PACE/OCI/L2/SFREFL/3.0)
  * [Data description: Land Vegetation Indices (LandVI)](https://oceancolor.gsfc.nasa.gov/data/10.5067/PACE/OCI/L2/LANDVI/3.0)
  * [PACE: Terrestrial products slides (Dec. 2024)](https://pace.oceansciences.org/docs/03-c-Huemmrich_PACE_Terrestrial.pdf)
* PACE Applications
  * [PACE: Applications workshop (Dec. 2024)](https://pace.oceansciences.org/event_archive/2024-PACE-Applications-Workshop.htm)
* PACE Early Adopters / Applications Partners
  * [PACE: Early Adopters projects](https://pace.oceansciences.org/app_adopters.htm)
  * [PACE: UAH Early Adopters project](https://pace.oceansciences.org/people_ea.htm?id=127)
    * [PACE: Early Adopters projects application form](https://forms.gle/ZxUeqDJDZu47SEzD8)
* Calendars for products
  * [8-day calendar](https://bit.ly/pace_oci_8d_cal)
  * [Julian day calendar (non-leap year)](https://satcorps.larc.nasa.gov/safari/JulianDayChart.html)
* Spectral bands from various multispectral and hyperspectral platforms
  * [Hyperspectral: PACE OCI (SFREFL, v3)](https://bit.ly/pace_oci_sr_v3_bands)
  * [Hyperspectral: ISS EMIT](https://bit.ly/iss_emit_bands)
  * [Multispectral: Landsat TM / ETM+ / OLI / OLI2](https://bit.ly/landsat_bands)
  * [Multispectral: Sentinel-2 MSI](https://bit.ly/s2_bands)

## EO cloud computing: the Google Earth Engine (#GEE) platform
* [GEE Code Editor](https://code.earthengine.google.com/)
  * [GEE registration link](https://earthengine.google.com/signup/)
  * [Instructions for GEE project registration](https://courses.spatialthoughts.com/gee-sign-up.html), via SpatialThoughts.com
* [GEE tasks](https://code.earthengine.google.com/tasks)
* Google Groups
  * [GEE Developers Google Group](https://groups.google.com/g/google-earth-engine-developers)
* Data catalogs
  * [GEE public catalog](https://developers.google.com/earth-engine/datasets)
  * [Awesome GEE community catalog](https://gee-community-catalog.org/)
* GEE tutorials, etc.
  * [Book: EE Fundamentals & Applications (2022)](https://www.eefabook.org/)
   * [Accompanying videos](https://www.youtube.com/@eefabook3667/videos)
   * [Accompanying GEE code repository](https://earthengine.googlesource.com/projects/gee-edu/book)
  * [GEE Higher Education resources](https://developers.google.com/earth-engine/tutorials/edu)
  * [Tutorials from the community](https://developers.google.com/earth-engine/tutorials/community/explore)
* GEE apps
   * [Google's curated apps](https://www.earthengine.app/)
   * [BzGEO's published apps](https://bzgeo.users.earthengine.app/)
   * [SERVIR-BZ's published apps](https://servirbz.users.earthengine.app/)
   * [BZ-SDG project's published apps](https://bz-sdg.earthengine.app/)
* Other resources
  * [Colors via JavaScripter](http://www.javascripter.net/faq/colornam.htm)

## Google's Geo For Good (G4G) conferences
* Geo For Good 2024
  * [G4G 2024: Sao Paulo](https://earthoutreachonair.withgoogle.com/events/geoforgood24-saopaulo)
  * [G4G 2024: Dublin](https://earthoutreachonair.withgoogle.com/events/geoforgood24-dublin)
  * [Colab Notebook - Soy mapping](https://colab.research.google.com/drive/1Iip9Li7ZguMxKUjZ4mbcg_q1EDyAvUB2)
  * Slides
    * [Vertex AI](https://docs.google.com/presentation/d/1eNJDIoJg-ADrxC09JIzl00frjyseEc917rItTDPalGI/edit#slide=id.g303d87bcffc_0_0)
    * [Embeddings, part 1](https://docs.google.com/presentation/d/1ZfBYUNV1w377rkxc3REm5_evyzMJF6szxXGBszKC7uw/edit#slide=id.g3012811fd68_0_1316)
    * [Embeddings, part 2](https://docs.google.com/presentation/d/1azsWfeDuC-ZF5L8LNuWAEe49UOsxC-pPvqyZvSvJThk/edit#slide=id.g303d69aca51_0_197)
 
## Geospatial Machine Learning (#GeoML)

* NASA-related
  * [SERVIR Geo AI Working Group page](https://sites.google.com/uah.edu/geo-ai-working-group/home)
  * [Course - NASA ARSET: Fundamentals of Machine Learning for Earth Science (2023)](https://appliedsciences.nasa.gov/get-involved/training/english/arset-fundamentals-machine-learning-earth-science)
    * [Associated GitHub page](https://github.com/NASAARSET/ARSET_ML_Fundamentals)

* Europe-related
  * [ML4Earth Slack channel](https://ml4earthworkspace.slack.com/team)
  * [Course - EO College: Introduction to Machine Learning in Earth Observation MOOC (2024)](https://eo-college.org/courses/introduction-to-machine-learning-for-earth-observation/)

* Esri
  * [Deep Learning GitHub page w/ installers](https://github.com/Esri/deep-learning-frameworks?tab=readme-ov-file)
  * [Deep learning models / packages](https://livingatlas.arcgis.com/en/browse/#d=1&type=tool&itemTypes=Deep+Learning+Package)
  * [MyEsri.com](https://my.esri.com/)

* EAC-related
  * [GeoML doc](https://bit.ly/geoml)
  * [Deep learning experiment runs](https://bit.ly/geoml_mod_comp)
  * [Deep learning on-ramp presentation slides](https://docs.google.com/presentation/d/1e9h_LQrSyL5oriFHUMxsVyWulQ1ReO1S/edit#slide=id.p1)
    * [Deep learning on-ramp presentation recording (Oct. 2024 version)](https://www.youtube.com/watch?v=H-iAVLtkV0c)
