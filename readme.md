# Data description

Hi Claudia,

You can ignore the Severity0-16 because they are just arbitrary disease severity grouping according to the greenness of the turfgrass after pathogen inoculation.

Please see the following for variable explanation:
Type: sample type - rhizosphere soil
Severity0-16_Raw: % turfgrass greenness remained on 0 to 16 days after inoculation of pathogen.
Severity0-16: Categorization of disease severity by arbitrarily two-level grouping according to the % turfgrass greenness.
Peak_AVG_raw: average  % turfgrass greenness over the peak disease development stage (4-10 days after inoculation)
SeverityPeak: Categorization of disease severity during the peak disease development stage. The rule to categorize was according to the "Severity4-10" where the medium sample was due to inconsistent three-level severity categorization during the peak disease development stage.   
pH until N: Bulk soil chemical properties. LOI can be deleted as it's just another measurement of OM (organic matter content).

Please let me know if you have any questions.

Thanks,
Ming-Yi



# Paul's data

## Emails

Hi Claudia-
I've copied Ming-Yi here on to this email so the three of us can talk rather than me be the middle man. Please see his response to me forwarding your email to him below.

We have two data sets that might work, I will briefly explain the treatments and then Ming-Yi can let you know exactly what kind of data we have to share:
A study we call 'Dollar spot (DS) disturbance'. The goal of this study was to see how different kinds of fungicides 'disturb' the resident microbial community, with the thinking being that high toxicity fungicides will control the pathogen but also injure the surrounding microbial community. Then, once the fungicide wears off, the disease will rebound to worse than it was before. This is a small set of treatments, just 4. There is a non-treated control, a high toxicity fungicide (chlorothalonil), and low toxicity fungicide (propiconazole), and a rotation of the two. These products were applied in the field at regular intervals throughout 2019, and disease ratings and soil samples were collected several times in 2019 and again a couple times so far in 2020. What we found in the field is that yes, the high toxicity fungicide leads to a rebound of disease much higher than the non-treated once the impact of the pesticide wears off. So far, we haven't found much in the high throughput sequencing data (16s) to indicate what microbial shifts are leading to this phenomenon.
Lily's main project is looking at how the soil 16s community shifts at different times of the season, and then how those shifts impact breakdown of a common pesticide. The treatment list is again pretty small: just treated or non-treated at two different time points, May and July.
Both studies have 4 reps and multiple samplings over time, and Lily's project was sampled at two different locations in the Madison area. Please let us know what specific questions you have and then myself or (more likely) Ming-Yi will do our best to answer them.

Ming-Yi, anything I missed above that you want to share with Claudia?

Hopefully we have something useful to share!

Paul

------------------------

Thanks, Claudia!
Nice to meet you Paul and Ming-Yi. Sounds like cool data sets! I think we can deal with relative abundance data using models I am currently playing with.

I do have a biology question for you regarding DS: what will happen with no treatment after the rebound of disease rather than altering? Will it go back to be similar to no treatment or keep having the disease?

I ask this question because the rebound can have different nature, it can be either a situation of relaxation (i.e. on its way going back to the equilibrium hopefully no disease after the treatment disturbance) or meta-stable (i.e. there are multiple possible equilibria while the rebound disease is one of them and treatment actually push the system to this bad one). The later one can be common in complex multi-body interacting systems and can be worse than the first case as it is kinda stable.

Nice to meet you all again!!

Best,
Yunyi


-----------------------

Hi Yunyi-
Thanks for the email, and also very nice to meet you.

Dollar spot is a foliar disease of turf that infects during warm, humid conditions. On a non-treated plot the disease typically goes up and down throughout the summer as conditions warm up and cool down, and then in the fall as temperatures cool down the plot typically recovers completely and there is no disease by the time winter arrives. What we have noticed in the 'DS Disturbance' study is that in the plots where we applied a particular, broadly toxic fungicide...in the NEXT YEAR (ie many months after the last fungicide had been applied) we notice increased disease relative to the non-treated area. This is what makes us think the 'rebound' is due to disturbance of natural competitors.

Let me know if that doesn't answer your question or if you have any follow up questions...and thank you!

Paul


------------------------

Hi Yunyi,

Happy connecting via email!

I don't quite understand your question but maybe I can provide a bit more context and hopefully that answers part of it. 

This study was done in a golf course turf so the whole research plot has been intensively managed with all kinds of agrochemicals in the past decades. Plus, it's near-monocultured turf so the ecological elasticity is low by default. The so-called none treated control here was merely a year (or two) without pesticide, or you can also say that it's a year in advance in pesticide alteration recovery (aka in the process of reaching soil, turf, microbial stability) comparing with the other treatments. The pathogen that causes dollar spot is always presents in the turf-soil interface and their growth and development is highly dependent on the soil and air conditions such as humidity and temperature. And now we suspect that microbial environment has much impact as well. The pesticide programs only suppress the pathogen density and activity to a certain extent but do not kill it all. What we have observed this year so far was that when the environment favored the growth of the disease, turf received highly toxic chlorothalonil from last year got a lot more disease than turf that had one year of rest without receiving pesticide. 

If I understood you correctly, you might be right about that pesticide programs per se can determine both the path and the final state of equilibrium if the study was done in a virgin land without pesticide history. Unfortunately, the experimental plot must have received all kinds of pesticides including everything used in this study in the past already (Paul may know his better than me), so the final equilibrium state was somewhat determined a long time ago since the damages were already done (i.e. rare microbial species being wiped out or fragile food web being distorted). I guess the theories you mentioned were more applicable to the land conversion, human intervention in natural environment, or under dramatic change of land use?

Your question resonate with one of my thoughts for a followup study, which is to find out what the actual microbiome equilibrium state is and how long does it take to reach such a state using a predictive model. Knowing this plausible microbial community and function will help guiding the management strategy i.e. restoring the ecological function instead of using expensive cultural practices to achieve certain goals.

Hope this helped.

Cheers,

Ming-Yi