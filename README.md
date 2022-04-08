# HOMEChem: the molecular impact of life in an indoor environment.

Repository with pertinent files necessary to recreate main figures from HOMEChem paper (https://doi.org/10.26434/chemrxiv-2021-nk5cr)

# Figure 1
## b) & c)
Both of these panels are plotting metabolomics feature counts for 2 different annotated features (gamma-glutamyl-S-allylcysteine and tryptophan) using molecular cartography through [ili](https://github.com/MolecularCartography/ili). To recreate these panels, one simply needs to drag and drop a 3D_model.stl file and a metabolomics_feature_table.csv file into the [ili chrome extension](https://chrome.google.com/webstore/detail/%60ili/mkapabmcenklinkkegdigblcciogjckn). 
Follow this step-by-step description to recreate panels.
1. Open the ili chrome extension. Familiarize yourself with the GUI. 
2. Drag and drop the 3D_model.stl file and let it load and render. 
3. Drag and drop the ...metabolomics_feature_table.csv files (one for each timepoint) and let the application load and render. 
4. Drag and drop ...feature_snapshot.json files to load the specific feature (gamma-glutamyl-S-allylcysteine or tryptophan) with the appropriate visualization settings to recreate figure panels. 

## e)
This pannel is plotting the sum of counts of Δm/z shifts ( Δm/z of 15.995 Da corresponding to the O atom , and 28.031 Da corresponding to C2H4) observed across the global molecular network of spectra in the study, subset by sample (surface) and timepoint (panel shows T2).
Follow this step-by-step description to recreate panel. 
1. Open the ili chrome extension. Familiarize yourself with the GUI. 
2. Drag and drop the 3D_model.stl file and let it load and render. 
3. Drag and drop the T2_mz_shifts_counts_table.csv file and let the application load and render. 
4. Drag and drop ...shift_snapshot.json files to load the specific Δm/z shift (O or C2H4) with the appropriate visualization settings to recreate figure panels. 

# Figure 2
## a)
This panel shows three-dimensional embedding using singular value decomposition of co-occurrence probabilities, which are highest for microbial genera (arrows) pointing in the same direction as metabolites (dots). To recreate this panel one simply needs to drag and drop a biplot.qzv file into the [qiime2 web visalizer](https://view.qiime2.org/)
Follow this step-by-step description to recreate panel. 
1. Open the qiime2 web-browser visualizer.
2. Drag and drop the mmvec_biplot.qzv file.
3. Drag and drop the mmvec_snapshot.json file to load the specific visualization settings that recreate the panel. 

## 
