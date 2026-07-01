# Gene Network Analysis of Nutrient-Responsive Stem Cell Regulation in Drosophila Ovary

## Background
Nutrient availability plays an important role in regulating stem cell maintenance, proliferation, and recovery in Drosophila ovaries.

## Aim
To identify nutrient-responsive genes associated with stem cell regulation using bioinformatics approaches.

## Objectives
1. Annotate candidate genes from a Drosophila dataset.
2. Identify genes involved in metabolism, signaling, and stem cell maintenance.
3. Perform functional enrichment analysis.
4. Construct gene interaction networks.

## Tools
- FlyBase
- g:Profiler
- STRING Database
- GitHub

## Results
### Functional Enrichment Analysis (g:Profiler)
Enrichment analysis of the 29 candidate genes revealed significant enrichment 
for biological processes central to nutrient-responsive stem cell regulation, 
including:
- Regulation of growth (padj = 3.80 × 10⁻¹¹)
- Multicellular organism growth (padj = 1.42 × 10⁻¹¹)
- Response to oxidative stress (padj = 8.59 × 10⁻¹⁰)
- Maintenance of cell number (padj = 8.13 × 10⁻⁹)
- Lipid homeostasis (padj = 5.01 × 10⁻⁶)

These results support the hypothesis that nutrient-sensing pathways converge 
on growth regulation and stress response mechanisms to maintain stem cell 
populations in the Drosophila ovary.

Full results: `gProfiler_dmelanogaster_2026-07-01_13-05-46.png`

### Gene Interaction Network (STRING)
A protein-protein interaction network was constructed for the 29 candidate 
genes. The network revealed a densely interconnected cluster comprising 
insulin/TOR signaling components (InR, Akt1, Tor, Tsc1, Rheb, S6k, chico, 
foxo, Myc), consistent with their central role in nutrient sensing and 
growth regulation. Antioxidant genes (Sod1, Sod2, Catalase, Prx3, Keap1) 
formed a distinct but connected sub-cluster, reflecting coordinated 
oxidative stress response. Stem cell regulators (piwi, bam, nanos, bgcn) 
clustered separately, linked to the core network primarily through Myc.

Full network image: `string_hires_image.png`
