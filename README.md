# NLtoPDDL Action Sequence Extraction datasets
Raw and annotated datasets used in EASDRL: windows, cooking, wikihow home and gardening

## File and Directory Structure:
1. annotated_pickles - original pickles from Fence/EASDRL
2. raw - raw files from Fence/EASDRL
3. ceasdrl_act_data.ipynb: visualize embeddings
4. *.csv - files with states (embeddings + distance + ground-truth action)
5. nltopddl_data_emb_gen.ipynb : generate states with embeddings using Flair library (the csv files). Other embeddings supported by Flair can be generated