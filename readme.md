# Baltimore area 2018 population by demographic characteristics analysis

## The data

The following raw data files were downloaded from the U.S. Census Bureau and pre-proccessed in "processing" notebook [`01_processing.ipynb`](https://nbviewer.jupyter.org/github/baltimore-sun-data/population-estimates-race-2018/blob/master/01_processing.ipynb) prior to analysis:

**For the 2010-18 period (all counties downloaded)**
- [**Vintage 2018 county population estimates by demographic characteristics**](https://www.census.gov/data/tables/time-series/demo/popest/2010s-counties-detail.html)

**For the 2000-10 period (only Maryland counties downloaded)**
- [**County Intercensal Datasets: 2000-2010**](https://www.census.gov/data/datasets/time-series/demo/popest/intercensal-2000-2010-counties.html)

**For the 1990-99 period (all counties downloaded)**
- [**State and County Intercensal Datasets: 1990-2000**](https://www.census.gov/data/datasets/time-series/demo/popest/intercensal-1990-2000-state-and-county-characteristics.html)

## Baltimore Sun analysis

By [Christine Zhang](mailto:czhang@baltsun.com)

The Baltimore Sun conducted an analysis of county-level population estimates by age, sex and race/ethnicity analysis for a story published June 19, 2019 titled ["Baltimore's white population swells with millennials, resembling D.C., Brooklyn"](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-census-estimate-population-race-20190619-story.html).

The Sun's findings and analysis are available in the "analysis" notebook in this repository: [`02_analysis.ipynb`](https://nbviewer.jupyter.org/github/baltimore-sun-data/population-estimates-race-2018/blob/master/02_analysis.ipynb). The pre-processing code is in the "processing" notebook in this repository: [`01_processing.ipynb`](https://nbviewer.jupyter.org/github/baltimore-sun-data/population-estimates-race-2018/blob/master/01_processing.ipynb).

The raw datasets are saved in the `input` folder.  The cleaned files are saved in the `output` folder. Note that these files are compressed as `input/inputdata.zip` and `output/outputdata.zip` and will need to be unzipped prior to analysis.

https://twitter.com/baltsundata

## Community Contributions

There are many angles to explore with this data, beyond just the ones we looked into for our story. 

**Have a question or something to contribute?** Send us a pull request or contact us on Twitter [@baltsundata](https://twitter.com/baltsundata) or via [email](mailto:czhang@baltsun.com).

You can also fork a copy of this repo to your own account.

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data files are available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license.

<br><br>