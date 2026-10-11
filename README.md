# Cell-to-Cell Communication: CD4+ Helper T Cell

## Biological Question
How do activated CD4+ helper T cells communicate with other immune cells through cytokine signaling?

## Part A. Sender Cell and Biological Context

**Sender Cell:** CD4+ Helper T Cell  
**Organism:** *Homo sapiens*  
**Biological Context:** Immune activation

CD4+ helper T cells are immune cells that coordinate immune responses by producing cytokines. These signaling molecules help regulate the activation, proliferation, and functions of other immune cells.

## Part B. Candidate Ligand and Sender-Cell Evidence

**Candidate Ligand:** Interleukin-2 (IL-2)  
**Official Gene Symbol:** IL2  
**Protein Type:** Secreted cytokine  
**Database:** Human Protein Atlas (HPA)  
**Dataset:** Schmiedel RNA-seq

### Expression Evidence

The Human Protein Atlas Schmiedel dataset shows high IL2 RNA expression in activated naive CD4+ T cells, approximately 7,800 TPM, compared with very low expression in resting naive CD4+ T cells.

This supports the selection of IL-2 as a candidate signaling molecule produced by activated CD4+ helper T cells. The RNA expression data support the biological plausibility of IL-2 production but do not directly measure protein secretion.

### Evidence Screenshot

![IL2 expression in activated CD4+ T cells](figures/01_sender_cell_evidence.png)

### Reference

Human Protein Atlas. IL2 (Interleukin-2).

https://www.proteinatlas.org/ENSG00000109471-IL2

## Part C. Receptor and Receiver Cell Identification

### Proposed Cell-to-Cell Communication

**Sender Cell:** Activated CD4+ helper T cell  
**Ligand:** Interleukin-2 (IL-2)  
**Receptor:** IL-2 receptor complex (IL2RA, IL2RB, IL2RG)  
**Receiver Cell:** Regulatory T cell (Treg)  
**Signaling Type:** Paracrine  
**Biological Context:** Immune regulation

### OmniPath Findings

OmniPath classifies IL2 (UniProt: P60568) as a secreted ligand with a transmitter role in intercellular communication.

IL2RA (UniProt: P01589) is classified as a transmembrane receptor with a receiver role. IL2RA is the alpha subunit of the high-affinity IL-2 receptor complex, which also includes IL2RB and IL2RG.

**IL2 Ligand Evidence:**

![OmniPath IL2 Ligand Evidence](figures/02_omnipath_evidence.png)

**IL2RA Receptor Evidence:**

![OmniPath IL2RA Receptor Evidence](figures/03_omnipath_receptor_evidence.png)

### Receiver Cell Evidence

The Human Protein Atlas identifies IL2RA as group enriched in regulatory T cells (Tregs) and basophils. Its predicted membrane localization supports its function as a cell-surface receptor component.

This provides evidence that regulatory T cells are biologically reasonable receivers of IL-2 signaling.

![HPA Regulatory T Cell Evidence](figures/04_receiver_cell_evidence.png)

### Proposed Signaling Mechanism

Activated CD4+ helper T cells secrete IL-2, which can bind to the IL-2 receptor complex on regulatory T cells. This signaling contributes to regulatory T-cell survival and immune regulation.

The proposed communication is paracrine because IL-2 is released by the sender cell and acts on a nearby receiver cell.

### References

- Human Protein Atlas — IL2RA: https://www.proteinatlas.org/ENSG00000134460-IL2RA
- OmniPath Explorer: https://explore.omnipathdb.org/
- UniProt — IL2: https://www.uniprot.org/uniprotkb/P60568/entry
- UniProt — IL2RA: https://www.uniprot.org/uniprotkb/P01589/entry
