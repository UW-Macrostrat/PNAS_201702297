# PNAS_201702297

This repository contains both the initial (raw) data and final time series used in Zaffos et al. 2017 Plate tectonic regulation of marine animal diversity. Proceedings of the National Academy of Sciences.

## [Raw Data](/RawData)

This directory contains static versions of the original data files used in the manuscript analyses. Dynamic versions of these data sets that are updated regularly can also be found through their respective data sources.

### [Fossil Occurrences](/RawData/RawFossilOccurrences.csv)

This is a static comma-separated-values table (CSV) of the [Paleobiology Database](https://paleobiodb.org) fossil occurrences used in these analyses. 

Dynamic versions of this data (i.e., equivalent but periodically updated versions of the data) can also be accessed through the Paleobiology Database data service using this [URL](https://paleobiodb.org/data1.2/occs/list.csv?base_name=Bivalvia,Gastropoda,Anthozoa,Brachiopoda,Trilobita,Bryozoa,Nautiloidea,Ammonoidea,Crinoidea,Blastoidea,Edrioasteroidea&interval=Cambrian,Pleistocene&show=coords,paleoloc,phylo&limit=all) or by using the `downloadPBDB()` R function from the [velociraptr](https://cran.r-project.org/web/packages/velociraptr/index.html) R package.

### [Marine Rock](/RawData/RawMarineRock.csv)

This is a static comma-separated-values table (CSV) of the [Macrostrat Database](https://macrostrat.org) marine rock time series used in these analyses.

Dynamic versions of this data (i.e., equivalent but periodically updated versions of the data) can also be accessed through the Macrostrat Database data service using this [URL](https://macrostrat.org/api/sections?project_id=1&environ_class=marine&format=csv).

### Paleogeography

The static version of the paleogeographic files used in these analyses can be download from their original source, [EarthByte](https://earthbyte.org) using the following [URL](http://tinyurl.com/jm2s3av).

Dynamic versions of this data (i.e., equivalent but periodically updated versions of the data) can also be accessed through the Macrostrat Database data service using this [URL](https://macrostrat.org/api/paleogeography).

### [Custom Epochs](/RawData/CustomEpochs.csv)

This is a static comma-separated-values table (CSV) of the [Macrostrat Database](https://macrostrat.org) custom geologic epochs used in these analyses.

## [Final Data](/FinalData)

This directory contains static versions of the final time-series used to generate the figures in the manuscript.

### [Continuous Time Series](/FinalData/ContinuousTimeSeries.csv)

This time-series table lists the range-through genus richness, continental fragmentation index, number of marine rocks, and mean pairwise minimum distance between plates.

### [Discrete Time Series](/FinalData/DiscreteTimeSeries.csv)

This time-series table lists the in-bin genus richness and continental fragmentation index time-series.
