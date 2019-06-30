# MyATLASProject
An ATLAS tutorial using CERN ATLAS open data.
Presently, the tutorial is divided into 4 levels:
* Level 1: We learn how to read in a dataset and fill a histogram.
* Level 2: We learn how to apply basic event selections.
* Level 3: We learn to compare two datasets, "signal" and "background", by overlaying the resulting histograms on one plot.
* Level 4 is a challenge: Figure out how to calculate the mass of the parent particle based on the decay particles reconstructed in the ATLAS detector using the variables available in the datasets. You have succeeded once the mass histogram for the signal dataset forms a peak around 91000 MeV.

## Quick tips on using ROOT notebooks

* to execute a cell of code, select the cell and press \<shift\>+\<enter\>
* wait for the [*] to disappear once you've executed code. The * indicates that the code is still busy.

## Cut-based analysis exercise 

Ideally done once all levels have been mastered.
No need for any scripts in the git repository. Just follow the link. 

Lets get a feeling for applying _cuts_ on your data!

<http://opendata.atlas.cern/visualisations/analyser-js.php>

## Helpful links

### What is this, how is that defined?

Looking to learn about particle definitions, the ATLAS detector layout and the general workings of ATLAS and the LHC? Take a look here:
<http://opendata.atlas.cern/books/current/get-started/_book/>

### What datasets can I explore?

A list of dataset names:
<http://opendata.atlas.cern/extendedanalysis/datasets.php>

### What is in my root file?

This is a quick reference of all the variables you can look at in your root data files:
<http://opendata.atlas.cern/books/current/openatlasdatatools/_book/variable_names.html>


