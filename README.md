# NMNH data in GBIF

Pulls data from GBIF and other APIs to learn more about how NMNH data is being used
for research. The CSVs in output are used on a Tableau dashboard accessible to
Smithsonian users.

## Setup

Miniforge and git are recommended for setup.

```
git clone https://github.com/NMNH-IDSC/nmnh-gbif-metrics
cd nmnh-gbif-metrics
mamba create -f environment.yml
```

## Use

Run the notebooks to download and consolidate data. Note that the first notebook makes
a large number of requests, particularly to the GBIF API. Requests are cached but it's
an expensive operation. 

Current versions of the output tables are available to Smithsonian staff if needed.