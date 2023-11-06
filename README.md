# Go Geomatics Workshop 2023
Calgary, Alberta

## Setup

Im using conda to manage dependencies in this workshop. Feel free to use whatever dependancy management tool you are comfortable with. The notebooks use the `!pip install` magic function in them for convinience. Running everything in conda will produce the most repeatable results.

```bash
conda env create -n gogeomatics-workshop --file environment.yml 
conda activate go
```

The following notebooks present different parts of a cloud native geospatial architecture.
 - [PDAL and COPC]("./pdal_copc.ipynb")
 - [STAC]("./stac.ipynb")
 - [ARD]("./ard.ipynb")