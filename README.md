# Determination of Leaf Area Index (LAI) from Hemispherical Canopy Photographs

## Project Overview

This exercise estimates leaf area index (LAI) from hemispherical canopy photographs using the Beer–Lambert law and gap-fraction integration. The workflow also includes the analysis of a set of hemispherical images using Hemisfer, where different thresholding methods and settings were tested to derive LAI values. 

## Objectives

- Calculate LAI manually using gap fractions and ring weights.
- Analyze hemispherical photographs with different thresholding settings.
- Compare LAI values across multiple canopy images.
- Interpret the impact of image quality and thresholding on optical LAI estimates. 

## Data

- Ring-wise gap fraction data for manual LAI computation
- Eight hemispherical canopy photographs
- Hemisfer output text file (`lai-result.txt`) 

## Methodology

### Manual LAI Calculation
- Applied the Beer–Lambert law of radiation attenuation.
- Integrated gap fractions over zenith-angle rings.
- Calculated effective LAI from ring-based transmissions and weights. 

### Hemispherical Photograph Analysis
- Loaded each hemispherical image into Hemisfer.
- Tested automatic and manual thresholding approaches.
- Extracted LAI values for all eight images.
- Interpreted how image conditions affect LAI estimation. 

## Main Outputs

- Manual LAI estimate
- LAI table for eight hemispherical photographs
- Threshold values and algorithm settings
- Written interpretation of image-quality effects and bias sources 

## Skills Demonstrated

- Canopy structure assessment
- Optical field measurement
- Gap-fraction based modelling
- Hemispherical image processing
- Quality control in remote sensing measurements 
