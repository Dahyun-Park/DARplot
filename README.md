# TheraDARPLOT 
## **TheraDARPLOT:** A high-quality visualization of three genetic models plots using genome-wide association data
The [**TheraDarplot**](https://github.com/Dahyun-Park/DARplot/) is a specialized form of scatterplot to display **genome-wide association studies (GWAS)** of three genetic models (Dominance, Additive and Recessive). 
Our results indicate that the combining methods of **three mode GWAS results** should increase the opportunity 
the significant and replicative results and reduce the substantial loss of power. Based on our study, 
we implemented a R package named 
**TheraDARPLOT** **(Dominance, Additive and Recessive combined Plot).** 

**Availability**: TheraDARPLOT is available for free (under the GNU General Public License V3) from git-hub and from the CRAN R package repository cran.r-project.org/web/packages/ TheraDARPLOT/.
#### **Contact : kyungwon.hong@theragenetex.com or dahyun.park@theragenetex.com**

## Introduction
The R package DAR-PLOT facilitates the evaluation and visualization of the highest p-values among the three genetic models.
![new_dm.png](new_dm.png)

## Installation
To install `Darplot`, use the standard R package installation command.

```{r}
# install.packages('DARplot')
```
## Usage
### Basic Darplot
To illustate its usage, let us plot the coronary artery disease GWAS based on *Deloukas et al*(2013). The original dataset provides nominal p-values. Since we want to plot the $-log_{10}(P\text{-}value)$, let us take the logarithm.  


```{r,cache=TRUE}
library(DARplot)
data(add_gwas)
cad_gwas$y=-log10(cad_gwas$pval)
head(cad_gwas)
```
## Basic Manhattan plot

```{r,cache=TRUE}
library(DARplot)
data(add_gwas)
cad_gwas$y=-log10(cad_gwas$pval)
head(cad_gwas)
```

## TheraDarplot

```{r,cache=TRUE}
library(DARplot)
data(add_gwas)
cad_gwas$y=-log10(cad_gwas$pval)
head(cad_gwas)
```

## Plotting multiple GWAS studies

## Details

## Tabling
To install `tabling`, use the standard R package installation command.
```# install.packages('DARplot')
```
