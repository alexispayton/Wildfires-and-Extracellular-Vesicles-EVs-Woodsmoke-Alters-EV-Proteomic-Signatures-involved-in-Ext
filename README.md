# Wildfires and Extracellular Vesicles (EVs): Woodsmoke Alters EV Proteomic Signatures involved in Extracellular Matrix Degradation and Tissue Injury in Airway Organotypic Models 

> As wildfires become more common, this study sought to investigate how extracellular vesicles (EVs) are impacted by in vitro smoke exposure from various biomasses.


> All analyses in this folder are designated by their figure number or table number in the manuscript in parantheses.


This script was generated to support the manuscript titled 'Wildfires and Extracellular Vesicles (EVs): Woodsmoke Alters EV Proteomic Signatures involved in Extracellular Matrix Degradation and Tissue Injury in Airway Organotypic Models' currently under review.

# 1. Data Extraction
- Extracting particle concentrations to compare between treatment groups (co-culture and tri-culture) in a visualization later on

# 2. PDF Data Visualization (Figure 3)
- Figure of extracted PDF data visualizing unexposed and exposed tri-cultures and co-culture groups
- Tested for differences between groups using ANOVA tests

# 3. Proteomics Data Processing
- Normalized, implemented background filters, imputed missing proteomics data, and removed sample outliers

# 4. Group Distribution Analysis (Table S2 & Table S3)
- Used t tests to determine compare protein abundance distributions between co-culture unexposed vs. exposed and tri-culture unexposed vs. exposed groups
- Calculated overall log~2~ transformed abundances and stratified by set (co-culture and tri-culture)

# 5. Volcano Plot (Figure 4)
- Visualizes significance (p adjusted value) and expression degree/direction (fold change) of proteins in both co and tri-culture treatments

# 6. Hierarchical Clustering Heatmap (Figure 5)
- Hiearchical clustering of of samples to see if exposure groups would group together based on scaled log~2~ protein expression
