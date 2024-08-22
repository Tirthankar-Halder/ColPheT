# ColPheT - Colony Phenotype Tracking 
<!-- ![build](https://github.com/igvteam/igv.js/actions/workflows/ci_build.yml/badge.svg)
[![](https://img.shields.io/npm/dw/igv.svg)](https://www.npmjs.com/package/igv)
[![](https://img.shields.io/github/last-commit/igvteam/igv.js.svg)](https://github.com/igvteam/igv.js)
[![](https://img.shields.io/npm/l/igv.svg)](LICENSE)
[![](https://data.jsdelivr.com/v1/package/npm/igv/badge)](https://www.jsdelivr.com/package/npm/igv) -->

ColPheT is an embeddable interactive command-line visualization component developed by the 
 [](https://.org) team. 

## Citing ColPheT

T. Halder, , Sk. Arif Ahmed, J. Hira, ColPheT: an embeddable python 
implementation of the Integrative command-line tool , Bioinformatics,,  ,  , 
, https://doi.org/**/bioinformatics/
 
Below are examples and a quickstart guide.  See the [developer documentation](https://igv.org/doc/igvjs) for more documentation.  

<!-- # Examples
 
***[Alignments](https://igv.org/web/release/3.0.2/examples/cram-vcf.html)***

***[Interactions](https://igv.org/web/release/3.0.2/examples/interact.html)***

***[Copy number](https://igv.org/web/release/3.0.2/examples/copyNumber.html)***

***[Multiple regions](https://igv.org/web/release/3.0.2/examples/multi-locus.html)***

***[Mutation Annotation Format (MAF)](https://igv.org/web/release/3.0.2/examples/maf-tcga.html)***

***[Variant color options](https://igv.org/web/release/3.0.2/examples/variant-colors.html)***

***[More](https://igv.org/web/release/3.0.2/examples/)***

  -->
# Quickstart
## Workflow

<p align="center">
      <img src="/assets/assets/workflow/1.png" width="70%"/>
</p>

# Prerequisites
ColPheT consists of a single python-based exe file with no external dependencies.  
Before you begin, ensure you have met the following requirements:

- **Operating System:** Linux, macOS, or Windows
- **Python:** Version 3.8 or higher
- **pip:** Python package manager (comes with Python 3)
- **Git:** Version control system for cloning the repository

### Installation Instructions

1. **Python:**
   - Install Python 3.8 or higher from the [official website](https://www.python.org/downloads/).
   - Verify the installation:
     ```bash
     python3 --version
     ```

### Additional Configuration

- **Environment Variables:**
  - Set up the following environment variables:
    <!-- - `API_KEY`: Your API key for accessing the external service. -->
    <!-- - `DB_CONNECTION_STRING`: The connection string for your database. -->

### Optional Prerequisites

- **Docker:** Required if you plan to run the application in a containerized environment.
- **Redis:** Required if you want to enable caching features.




## Usage

### Clone the GIT repositorty
```bash
git clone https://github.com/Tirthankar-Halder/ColPheT.git
```

### Run the program


## Development - Compile from Original Packages

### Requirements

Building ColPheT and running the examples require Windows.  Other os environments will probably work but have not been tested.  

ColPheT provides customisable packages for modification as per requirement.

### Building
```bash
git clone https://github.com/Tirthankar-Halder/ColPheT-packages.git
```


This creates a dist folder with the following files structure:
```
 BacColonyV3.mp4
├── Classification
│   ├── classification.ipynb
│   └── Logistic Regression Practical Implementation.ipynb
├── classification.ipynb
├── ColpheT.py
├── features.pkl
├── MVI_5585.MP4
├── MVI_66245.MP4
├── P3.MP4
├── packages
│   ├── BoxTracker.py
│   ├── ColpheTN.py
│   ├── detGenerater.py
│   ├── export.py
│   ├── func.py
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── BoxTracker.cpython-39.pyc
│   │   ├── ColpheTN.cpython-39.pyc
│   │   ├── detGenerater.cpython-39.pyc
│   │   ├── export.cpython-39.pyc
│   │   ├── func.cpython-39.pyc
│   │   ├── __init__.cpython-39.pyc
│   │   └── tracker.cpython-39.pyc
│   └── tracker.py
├── pklGenerator.ipynb
├── prediction.ipynb
├── RES_MH_Control_enhanced.mp4
├── ResOrginal.mp4
├── ResSpecial.mp4
├── starter.py
├── threshValGenerator.ipynb
└── Vanco_Res_enhanced.mp4


```
### Compilation

### Tests


### Examples

Some sample results:
<table>
    <tr>
        <td> Original Slide </td>
        <td>Binary Slide </td>
  </tr>
  <tr>
    <td><img src="/assets/results/images/or_190.png" alt="Slide" width="400"></td>
    <td><img src="/assets/results/images/bn_190.png" alt="Slide" width="400"></td>
  </tr>
    <tr>
        <td> Segmented Slide </td>
        <td>Tracked Slide </td>
  </tr>
  <tr>
    <td><img src="/assets/results/images/cs_190.png" alt="Slide" width="400"></td>
    <td><img src="/assets/results/images/tr_190.png" alt="Slide" width="400"></td>
  </tr>
  
</table>
<!-- 
<video width="600" controls>
  <source src="./assets/results/video/test_90.avi" type="video/avi">
</video> -->

![Demo](/assets/results/video/test_90.gif)

[Download the full video](./assets/results/video/test_90.mp4)
# License



 