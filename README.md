# mc-dre
* The original 2018 n2c2 dataset were drawn from the MIMIC-III (Medical Information Mart for Intensive Care III) clinical care database[1], The original CADEC dataset can be downloaded at: https://data.csiro.au/collection/csiro:10948?v=3&d=true.


Step 1. Please transfer the original dataset into 'sample.json'.


Step 2. Use 'obtain_embedding.ipynb' to obtain the embedding file, like 'dev_pubmedbert_ins_gs.h5'.


Step 3. Use 'main.ipynb' as the main model file.


Step 4. Use [2] to get the evaluation result.



Reference:
[1] Johnson AE, Pollard TJ, Shen L, et al. MIMIC-III, a freely accessible critical care database. Sci Data 2016; 3: 160035    
[2] https://github.com/kaivamannam/clinicalnlp-ade/blob/master/misc/Track2-evaluate-ver4.py
