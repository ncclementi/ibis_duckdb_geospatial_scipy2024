# Ibis + DuckDB geospatial: a match made on Earth 

This repo contains the demos and link to slides for the Ibis + DuckDB geospatial talk. 

How to download and cite the slides: 

**Download:** https://figshare.com/articles/presentation/Ibis_DuckDB_geospatial_a_match_made_on_Earth_Scipy_2024_/26264120

**Cite:** 
Clementi, Natalia C. (2024). Ibis + DuckDB geospatial: a match made on Earth (Scipy 2024). figshare. Presentation. https://doi.org/10.6084/m9.figshare.26264120.v1 
## Run the demos:
Create an enviornment with mamba, conda or the package manager of your choice. I used mamba, and then pip to install some nightly version of packages and upgrade some dependencies. 

 ```
$ mamba create -n ibis-geo-scipy24 python=3.11
$ mamba activate ibis-geo-scipy24
$ pip install duckdb --pre --upgrade
$ pip install 'ibis-framework[duckdb,geospatial]'
$ pip install -U geopandas
$ pip install lonboard jupyterlab
```

Launch jupyterlab and start playing around. 


## License

All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/ncclementi/ibis_duckdb_geospatial_scipy2024/blob/main/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
