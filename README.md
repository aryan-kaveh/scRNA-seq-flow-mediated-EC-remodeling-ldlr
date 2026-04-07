# Flow-mediated endothelial remodeling and inflammation drive developmental vascular susceptibility in _ldlr_ loss of function

This repository accompanies the Nature Communications manuscript:

**Flow-mediated endothelial remodeling and inflammation drive developmental vascular susceptibility in _ldlr_ loss of function**

## Abstract

Atherosclerosis, the leading cause of cardiovascular disease, is associated with aberrant lipid metabolism, endothelial dysfunction, and chronic inflammation, yet its early manifestations and mechanisms remain incompletely understood. Low-density lipoprotein receptor loss of function is the most common monogenic cause of atherosclerosis. We employed low-density lipoprotein receptor knockout (_ldlr_-/-) zebrafish to investigate the developmental origins of atherosclerotic cardiovascular disease. Single-cell RNA-sequencing under differential flow conditions in embryonic _ldlr_-/- zebrafish identified a population of disproportionately stressed endothelial cells marked by overexpression of heat shock protein 70 (_hsp70_). _Hsp70_ is induced in stressed endothelial cells in a flow-dependent manner in zebrafish and in a subset of human endothelial cells, and its activation is associated with disrupted remodeling angiogenesis in vivo. Genetic and pharmacological studies demonstrated that _hsp70_ upregulation inhibits vascular apoptosis and ciliogenesis, leading to altered angiogenic remodeling. Concurrently, pro-inflammatory processes, including enhanced myelopoiesis and thrombogenicity, are amplified at early stages in _ldlr_-/- zebrafish, which also exhibit impaired regenerative angiogenesis and heightened neutrophil recruitment post-vascular injury. Our findings reveal how abnormalities in flow-mediated endothelial remodeling and inflammation converge during embryogenesis to drive vascular susceptibility to hemodynamic and other stressors in _ldlr_ loss of function.

---

## Scope

This repository documents the single-cell RNA sequencing computational framework associated with the study.

The original analyses were performed using project-specific scripts and package versions available at the time of the study. As the single-cell analysis ecosystem has evolved substantially since then, this repository directs readers to the current official documentation for the main analytical procedures used in the manuscript, including preprocessing, clustering, dimensionality reduction, differential expression, integration, and trajectory inference.

Accordingly, this repository is intended as a concise guide to the relevant analysis resources and public datasets associated with the study, rather than as a fully packaged software release (updated: April 7, 2026).

---

## Analysis resources

### Preprocessing, clustering, and dimensionality reduction
Official Seurat tutorials and documentation for normalization, feature selection, scaling, PCA, neighborhood graph construction, clustering, and UMAP visualization:

- Seurat guided tutorial (PBMC 3K)  
  https://satijalab.org/seurat/articles/pbmc3k_tutorial

- Seurat v5 essential commands  
  https://satijalab.org/seurat/articles/seurat5_essential_commands

- Seurat function reference  
  https://satijalab.org/seurat/reference/

### Differential expression analysis
Official Seurat documentation for marker discovery and differential expression testing:

- Differential expression vignette  
  https://satijalab.org/seurat/articles/de_vignette

- `FindMarkers`  
  https://satijalab.org/seurat/reference/findmarkers

- `FindAllMarkers`  
  https://satijalab.org/seurat/reference/findallmarkers

- `FindConservedMarkers`  
  https://satijalab.org/seurat/reference/findconservedmarkers

### Dataset integration
Official Seurat documentation for integration workflows across datasets and platforms:

- Introduction to scRNA-seq integration  
  https://satijalab.org/seurat/articles/integration_introduction.html

- Integrative analysis in Seurat v5  
  https://satijalab.org/seurat/articles/seurat5_integration

- `IntegrateLayers`  
  https://satijalab.org/seurat/reference/integratelayers

### Trajectory inference and pseudotime analysis
Official Monocle3 documentation for trajectory learning and pseudotime analysis:

- Monocle3 introduction  
  https://cole-trapnell-lab.github.io/monocle3/docs/introduction/

- Getting started with Monocle3  
  https://cole-trapnell-lab.github.io/monocle3/docs/getting_started/

- Trajectories and pseudotime  
  https://cole-trapnell-lab.github.io/monocle3/docs/trajectories/

### Gene set resources
Gene set resources used for enrichment-based interpretation:

- MSigDB home  
  https://www.gsea-msigdb.org/gsea/msigdb

- MSigDB human collections  
  https://www.gsea-msigdb.org/gsea/msigdb/collections.jsp

---

## Data availability

The single-cell datasets associated with this study are available through NCBI Gene Expression Omnibus (GEO):

- **GSE275308**
- **GSE212388**

GEO home:  
https://www.ncbi.nlm.nih.gov/geo/

GSE275308 accession page (will be made available upon publication of manuscript):
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE275308

GSE212388 accession page:  
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212388

---

## Notes

- The original manuscript analyses were performed with earlier package versions and manuscript-specific analysis scripts.
- Readers seeking to reproduce equivalent workflows are referred to the current official package documentation linked above.
- This repository is not intended to provide a maintained end-to-end software pipeline.

---

## Citation

If using the datasets or analysis framework associated with this work, please cite the manuscript:

**Flow-mediated endothelial remodeling and inflammation drive developmental vascular susceptibility in _ldlr_ loss of function**

---

## Correspondence

For questions regarding the study, please contact the corresponding author(s) of the manuscript.
