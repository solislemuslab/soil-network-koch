# Soil microbiome under fungicide treatments

## Data description

We have two data sets that might work, I will briefly explain the treatments and then Ming-Yi can let you know exactly what kind of data we have to share: A study we call 'Dollar spot (DS) disturbance'. The goal of this study was to see how different kinds of fungicides 'disturb' the resident microbial community, with the thinking being that high toxicity fungicides will control the pathogen but also injure the surrounding microbial community. Then, once the fungicide wears off, the disease will rebound to worse than it was before. This is a small set of treatments, just 4. There is a non-treated control, a high toxicity fungicide (chlorothalonil), and low toxicity fungicide (propiconazole), and a rotation of the two. These products were applied in the field at regular intervals throughout 2019, and disease ratings and soil samples were collected several times in 2019 and again a couple times so far in 2020. What we found in the field is that yes, the high toxicity fungicide leads to a rebound of disease much higher than the non-treated once the impact of the pesticide wears off. So far, we haven't found much in the high throughput sequencing data (16s) to indicate what microbial shifts are leading to this phenomenon. Lily's main project is looking at how the soil 16s community shifts at different times of the season, and then how those shifts impact breakdown of a common pesticide. The treatment list is again pretty small: just treated or non-treated at two different time points, May and July. Both studies have 4 reps and multiple samplings over time, and Lily's project was sampled at two different locations in the Madison area.


Please see the following for variable explanation: 
- Type: sample type - rhizosphere soil Severity0-16_Raw: % turfgrass greenness remained on 0 to 16 days after inoculation of pathogen. 
- Severity0-16: Categorization of disease severity by arbitrarily two-level grouping according to the % turfgrass greenness. 
- Peak_AVG_raw: average % turfgrass greenness over the peak disease development stage (4-10 days after inoculation) 
- SeverityPeak: Categorization of disease severity during the peak disease development stage. The rule to categorize was according to the "Severity4-10" where the medium sample was due to inconsistent three-level severity categorization during the peak disease development stage.
- pH until N: Bulk soil chemical properties. LOI can be deleted as it's just another measurement of OM (organic matter content).

## Steps to clone the repo locally
1. In the terminal, go to the folder where you want to put the local repository using `cd`

2. Type:
```
git clone https://github.com/solislemuslab/potato-lankau.git
```

3. Inside this folder, create a subfolder called `data` where you will put the data. This folder is ignored in the `.gitignore` file, so nothing inside this folder will be pushed to github