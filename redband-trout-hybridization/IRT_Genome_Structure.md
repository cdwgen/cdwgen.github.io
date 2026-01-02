---
layout: default
title: Genome Structure of Kootenai Redband Trout
---

[← Back to Redband Trout Hybridization Dynamics](index.md)

# Linkage Map Construction and Alignment

Genetic maps for three populations of Kootenai IRT (2 wild: East Fork Yaak River and Wolf Creek; 1 hatchery: Gerrard strain IRT) were created via... LepMap2

Per-population genetic maps and the global consensus map were aligned to the Arlee Coastal Rainbow Trout (CRT) reference genome ([NCBI: GCF_013265735.2](https://www.ncbi.nlm.nih.gov/assembly/GCF_013265735.2/); [Gao et al. 2021](https://doi.org/10.1093/g3journal/jkab052)), the Swanson CRT reference genome ([NCBI: GCA_025558465.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_025558465.1/); [Ali et al. 2025](https://doi.org/10.1038/s41597-025-04693-7)), and the Connor Lake Westslope Cutthroat Trout (WCT) reference genome ([NCBI: GCF_045791955.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_045791955.1/); [Flores et al. 2025](https://doi.org/10.1093/g3journal/jkaf064)) using [Minimap2](https://github.com/lh3/minimap2) v2.30 ([Li 2018](doi:10.1093/bioinformatics/bty191); [Li 2021](doi:10.1093/bioinformatics/btab705) to identify karyotypic rearrangements and inversions.

# Genome Structure of Kootenai Redband Trout

The genome structure of Kootenai Basin IRT mirrors that of the Swanson CRT reference genome and all three populations examined have a haploid karyotype of 29 chromosomes. Alignment to the Swanson and Arlee CRT reference genomes shows that Kootenai IRT are homozygous for the derived form of the Chr05 complex found to be variable in some Rainbow Trout (RBT) populations ([Pearse et al. 2019](https://doi.org/10.1038/s41559-019-1044-6). Similarly to Arlee and Swanson, Kootenai IRT possess the derived form of the chromosome 20 (Omy20) intraspecific inversion found in northern populations of RBT ([Hale et al. 2024](https://doi.org/10.1093/g3journal/jkae100)). Maps showed no clear evidence of the intraspecific chromosome 26 inversion recently described in the Swanson RBT assembly ([Ali et al. 2025](https://doi.org/10.1038/s41597-025-04693-7)) in any population. A region of reduced recombination on chromosome 17 was apparent in alignments to the Arlee and Swanson assemblies, roughly in line with an intraspecific inversion described in [Ali et al. 2025 (preprint)](https://doi.org/10.1101/2025.10.11.681701). Curiously, this same pattern of reduced recombination was observed when the map was aligned to the Connor Lake WCT assembly. Alignment to WCT also showed interspecific inversions on chromosomes 20 (Chr20), 22 (Chr22), and 29 (Chr29) consistent with [Flores et al. (2025)](https://doi.org/10.1093/g3journal/jkaf064). 

Below are alignments of the global IRT linkage map to each of the assemblies. Each panel represents a single linkage group (LG01–LG29) plotted against its corresponding chromosome in the assembly, with genetic position (cM) on the y-axis and physical position (Mb) on the x-axis. Marker strand orientation is indicated to highlight regions of colinearity and reversed orientation. Chromosome names in the RBT assemblies mirror Arlee chromosome nomenclature while the WCT chromosomes are numbed in accordence with the Connor Lake assembly. Linkage groups are numbered in accordance with the Swanson assembly.

---

## Alignment to Swanson CRT Assembly

Kootenai IRT genome structure closely mirrors the Swanson CRT assembly...

<iframe
  src="{{ '/redband-trout-hybridization/assets/pdfs/IRT_Global_v_Swanson_CRT_alignment_all_chromosomes.pdf' | relative_url }}"
  width="100%"
  height="550px"
  style="border:none;">
</iframe>

[Open Global Map vs Swanson Assembly in a new tab]({{ '/redband-trout-hybridization/assets/pdfs/IRT_Global_v_Swanson_CRT_alignment_all_chromosomes.pdf' | relative_url }}){:target="_blank"}

## Alignment to Arlee CRT Assembly

...

<iframe
  src="{{ '/redband-trout-hybridization/assets/pdfs/IRT_Global_v_Arlee_CRT_alignment_all_chromosomes.pdf' | relative_url }}"
  width="100%"
  height="550px"
  style="border:none;">
</iframe>

[Open Global Map vs Swanson Assembly in a new tab]({{ '/redband-trout-hybridization/assets/pdfs/IRT_Global_v_Arlee_CRT_alignment_all_chromosomes.pdf' | relative_url }}){:target="_blank"}

## Alignment to Connor Lake WCT Assembly

...

<iframe
  src="{{ '/redband-trout-hybridization/assets/pdfs/IRT_Global_v_ConnorLk_WCT_alignment_all_chromosomes.pdf' | relative_url }}"
  width="100%"
  height="550px"
  style="border:none;">
</iframe>

[Open Global Map vs Swanson Assembly in a new tab]({{ '/redband-trout-hybridization/assets/pdfs/IRT_Global_v_ConnorLk_WCT_alignment_all_chromosomes.pdf' | relative_url }}){:target="_blank"}

## Download the linkage maps

The maps used to create these alignments can be found [here]().
