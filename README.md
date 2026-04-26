# nchem_antidepressants
Repository to accompany the manuscript "Pharmacodynamic profiles inform systematization, efficacy and whole-brain drug distribution profiles in 18 antidepressants" (Hänisch et al., [DOI])

# Abstract

Although empirical evidence shows that antidepressants are effective and superior to placebos in treating depressive disorders, their mechanisms of action are still unclear. In this study, we examine the multidimensional molecular affinities of 18 commonly used antidepressants. Clustering analyses consistently generate three distinct clusters, providing a broader taxonomy that groups SSRIs and SNRIs together. Correlational analyses indicate an absence of clear relationships between the strength of inhibition and the response of single receptors or transporters. Next, we generate anatomical distribution profiles of drug action strengths by combining positron emission tomography-derived maps of cerebral neurotransmitter receptor and transporter densities from an open-access repository of healthy participants with the drugs’ affinity profiles. We then relate these profiles to functional and structural neuroanatomical measures in health and disease. Our results reveal distinct, mechanistically interpretable differences between antidepressants with high 5-HTT affinity and atypical antidepressants. These differences could inform personalized drug selection and development.

# Repository description

1. `data`  contains the necessary files to reproduce analyses for Figures 1, Figure 2A&B and Figure 3A&B as well as supplementary analyses. To reproduce Figure 2C, disease-associated cortical thickness alterations can be accessed through https://enigma-toolbox.readthedocs.io/en/latest/; to reproduce Figure 3C, meta-analytical topic-based decoding maps can be accessed at https://neurosynth.org/analyses/topics/v5-topics-50/
3. `manuscript_codes.ipynb` contains the code to reproduce analyses for the manuscript's main and supplementary figures
4. `requirements_antidepressants.txt` is a requirements file we recommend to use to set up a python virtual environment into

```bash
git clone https://github.com/bhaenisch/nchem_antidepressants.git
cd nchem_raad

python3 -m venv .env

# On macOS/Linux
source .env/bin/activate

# On Windows
.env\Scripts\activate

pip install -r requirements_antidepressants.txt
