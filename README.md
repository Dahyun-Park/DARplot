# TheraDARPLOT 
## A high-quality visualization of three genetic models plots using genome-wide association data
The [**TheraDarplot**](https://github.com/Dahyun-Park/DARplot/) is a specialized form of scatterplot to display **genome-wide association studies (GWAS)**. 
Our results indicate that the combining methods of **three mode GWAS results** should increase the opportunity 
the significant and replicative results and reduce the substantial loss of power. Based on our study, 
we implemented a R package named 
**TheraDARPLOT** **(Dominance, Additive and Recessive combined Plot).** 

## Introduction
The R package DAR-PLOT facilitates the evaluation and visualization of the highest p-values among the three genetic models.
![new_dm.png](https://github.com/Dahyun-Park/DARplot/new_dm.png)

## Installation
To install `Darplot`, use the standard R package installation command.

```{r}
# install.packages('Darplot')
```
## Usage
### Basic Darplot
To illustate its usage, let us plot the coronary artery disease GWAS based on *Deloukas et al*(2013). The original dataset provides nominal p-values. Since we want to plot the $-log_{10}(P\text{-}value)$, let us take the logarithm.  


```{r,cache=TRUE}
library(manhattan)
data(cad_gwas)
cad_gwas$y=-log10(cad_gwas$pval)
head(cad_gwas)
```
## Basic Manhattan plot

## TheraDarplot

## Plotting multiple GWAS studies

## Details

## Tabling
