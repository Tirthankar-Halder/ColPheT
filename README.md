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
      <img src="assets/assiworkflow/1.png" width="70%"/>
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



## Development - Compile from Original Packages

### Requirements

Building ColPheT and running the examples require Windows.  Other os environments will probably work but have not been tested.  

Windows users can use [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

### Building
<!-- 
Building igv.js and running the examples requires [node.js](https://nodejs.org/).


```  
git clone https://github.com/igvteam/igv.js.git
cd igv.js
npm install
npm run build
```

This creates a dist folder with the following files

* igv.js - UMDS file for script include, AMD, or CJS modules.  A script include will define an "igv" global.
* igv.min.js - minified version of igv.js
* igv.esm.js --  ES6 module 
* igv.esm.min.js --  minified version of igv.esm.js -->

### Tests

<!-- To run the tests from the command line

```
npm run test
```
 -->

### Examples

Some results
<table>
    <tr>
        <td> Original Slide </td>
        <td>Binary Slide </td>
  </tr>
  <tr>
    <td><img src="/assets/results/images/or_190.png" alt="Assignment 2 write" width="400"></td>
    <td><img src="/assets/results/images/bn_190.png" alt="Assignment 2 read " width="400"></td>
  </tr>
    <tr>
        <td> Segmented Slide </td>
        <td>Tracked Slide </td>
  </tr>
  <tr>
    <td><img src="/assets/results/images/cs_190.png" alt="Assignment 2 write" width="400"></td>
    <td><img src="/assets/results/images/tr_190.png" alt="Assignment 2 read " width="400"></td>
  </tr>
  
</table>

<video width="600" controls>
  <source src="assets/results/video/test.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


# License



 