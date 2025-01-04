# Tissue-Analysis
Background:

Diffuse Large B Cell Lymphoma (DLBCL) is an aggressive form of non-Hodgkin's lymphoma. 

Chimeric Antigen Receptor (CAR) T cells are synthetic and modular proteins used to target highly cytotoxic T cells to specific target proteins.

When used in Diffuse Large B Cell Lymphoma they target CD19, a transmembrane protein expressed on all B cell lineages.

We are asking: 
- What explains the different responses to CAR-T therapy? 
- Which patients are most liekly to have an intiial or complete response to CAR-T? Why?
- Of those patients who initially have a complete response, which are most likely to ultimately have progression of disease? Why?

Aims: 
- Identify transcriptional signatures in pre-CAR T treatment tumor biopsies which correlate with a durable response at 6 months

- Compare the differences in the spatial organization of cell types and transcriptional signatures between responders and non-responders

In this notebook the computational tool, Starfysh, is used to combine histology and spatial transcriptomics to deconvolute cell states and evaluate tumor heterogeneity and identify spatial hubs within tissues. 

Some visualizations:

Overlay of tissue sample colored by hubs 
<img width="500" alt="Screenshot 2025-01-04 at 4 12 57 PM" src="https://github.com/user-attachments/assets/3499ae7e-437a-4f16-966e-c02d3b0c24fe" />


UMAP Spatial Hubs calculated by Louvain algorithm

<img width="500" alt="Screenshot 2025-01-04 at 4 12 41 PM" src="https://github.com/user-attachments/assets/adc48583-b121-4477-b5bf-4c3a2a99394b" />

Correlation Matrix between cell type and gene expression
<img width="500" alt="Screenshot 2025-01-04 at 4 12 14 PM" src="https://github.com/user-attachments/assets/8dca7f62-2feb-4bbc-b02d-1a9cb2fe52b0" />

