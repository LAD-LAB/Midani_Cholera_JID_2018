# Human Gut Microbiota Predicts Susceptibility to Vibrio cholerae Infection
FS Midani, AA Weil, ... , LA David, and Regina LaRocque. *Journal of Infectious Diseases*. 2018. </br>
https://doi.org/10.1093/infdis/jiy192

**Background** Cholera is a public health problem worldwide and the risk factors for infection are only partially understood.
**Methods** We prospectively studied household contacts of cholera patients to compare those who were infected with those who were not. We constructed predictive machine learning models of susceptibility using baseline gut microbiota data. We identified bacterial taxa associated with susceptibility to Vibrio cholerae infection and tested these taxa for interactions with V. cholerae in vitro. **Results** We found that machine learning models based on gut microbiota predicted V. cholerae infection as well as models based on known clinical and epidemiological risk factors. A ‘predictive gut microbiota’ of roughly 100 bacterial taxa discriminated between contacts who developed infection and those who did not. Susceptibility to cholera was associated with depleted levels of microbes from the phylum Bacteroidetes. By contrast, a microbe associated with cholera by our modeling framework, Paracoccus aminovorans, promoted the in vitro growth of V. cholerae. Gut microbiota structure, clinical outcome, and age were also linked.**Conclusion** These findings support the hypothesis that abnormal gut microbial communities are a host factor related to V. cholerae susceptibility.

---

# Overview

    |- README               # description of content
    |
    |- generate_data        # code for running classifiers
    |  |- input_data        # raw data
    |    |- onset           # 
    |    |- susceptibility  # 
    |  |- output_data       # output of previously run classifiers
    |
    |- generate_figures     # code for generating several figures in paper
    |  |- figs              # 
    |
    |- generate_tables      # code for generating most of the tabulated data in paper
    |  |- tables            #
    |
    |- generated_clusters   # results of sparcc clustering 
