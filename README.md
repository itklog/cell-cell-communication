### Title
**Paracrine TNF Signaling from Microglia to Astrocytes through TNFRSF1A**

### Biological Question
How can tumor necrosis factor (TNF) produced by microglial cells signal to astrocytes through TNF receptor superfamily member 1A (TNFRSF1A), and what intracellular signaling components and cellular responses are associated with this communication?


## Chosen Sender Cell and Biological Context

The chosen sender cell is the **microglial cell**, a resident immune cell of the central nervous system (CNS).

The biological context is **neuroinflammation and synaptic homeostasis**. Activated microglia can produce and release inflammatory signaling molecules that act on neighboring cells within the CNS.

In this model, microglia function as the sender cell and communicate with astrocytes through a soluble extracellular signal.

**Sender cell:** Microglial cell  
**Tissue/context:** Central nervous system (CNS), particularly neuroinflammatory conditions


## Candidate Ligand and Evidence for Sender-Cell Expression

The candidate signaling molecule is **tumor necrosis factor (TNF)**, encoded by the **TNF** gene.

**Protein:** Tumor Necrosis Factor (TNF-alpha)  
**Gene:** `TNF`  
**UniProt/Gene identifier used:** `ENSG00000232810-TNF`

Evidence from **The Human Protein Atlas (HPA)** supports TNF expression and its potential role as an extracellular signal:

- TNF has verified **evidence at the protein level**.
- It shows **cytoplasmic expression in subsets of immune cells**.
- Its predicted subcellular localization is **secreted**.

These findings support the use of TNF as a candidate soluble ligand produced by the microglial sender cell.


## Receptor and Receiver Cell with Supporting Evidence

The selected receptor is **TNF receptor superfamily member 1A (TNFRSF1A)**, also known as **TNF receptor 1 (TNFR1)**.

**Receptor gene:** `TNFRSF1A`  
**Receptor protein:** Tumor Necrosis Factor Receptor Superfamily Member 1A (TNFR1)  
**Receiver cell:** Astrocyte

According to **The Human Protein Atlas**, the brain expression cluster for TNFRSF1A RNA is annotated under **"Astrocytes - Mixed function (mainly)"**. This supports the selection of astrocytes as the receiver cell.

The proposed communication is therefore:

**Microglial cell → TNF → TNFRSF1A on astrocyte**


## Type of Cell-to-Cell Signaling

The proposed mechanism represents **paracrine signaling**.

Microglial cells release soluble TNF into the local extracellular environment. TNF can then diffuse over a short distance and interact with receptors on neighboring cells, including astrocytes.

This differs from:

- **Endocrine signaling**, because the signal is not primarily transported through the circulation to distant tissues.
- **Autocrine signaling**, because the proposed receiver cell is an astrocyte rather than the same microglial cell that releases TNF.
- **Contact-dependent signaling**, because TNF is represented as a soluble extracellular ligand rather than a membrane-bound signal requiring direct cell-cell contact.


## OmniPath Findings

OmniPath was used as a pathway and interaction resource to support the proposed direction of signaling from the TNF receptor toward intracellular signaling components.

The model places **TNFRSF1A** at the receiver-cell membrane and connects it with downstream signaling components identified in the receptor-centered network, particularly **MADD, NSMAF, and SPATA2**.

The proposed direction of information flow is:

**TNF → TNFRSF1A → MADD / NSMAF / SPATA2 → inflammatory cellular response**

OmniPath and pathway-level evidence support the interpretation that TNFRSF1A-associated signaling can connect extracellular TNF recognition with intracellular inflammatory signaling.


## STRING Network Interpretation

A **STRING** network was constructed using `TNF` and `TNFRSF1A` as the primary query proteins in *Homo sapiens*.

### Network size
**7 nodes**

### Proteins identified
- `TNF`
- `TNFRSF1A`
- `MADD`
- `NSMAF`
- `SPATA2`
- `TNFRSF10C`
- `TNFRSF6B`

The most relevant downstream proteins for the proposed receptor-associated response are:

### MADD
MADD is an adaptor associated with TNFRSF1A signaling and is connected to **MAP kinase cascade activation and cell survival pathways**.

### NSMAF
NSMAF is a signaling component associated with **sphingomyelinase activation**, contributing to the generation of secondary signaling molecules.

### SPATA2
SPATA2 functions as a structural adaptor associated with the TNF receptor complex and is involved in the regulation of **ubiquitin-mediated NF-κB signaling**.

Together, MADD, NSMAF, and SPATA2 provide plausible intracellular connections between TNFRSF1A activation and downstream cellular responses.

### Enriched Pathway

The STRING analysis identified the:

**KEGG: TNF signaling pathway (hsa04668)**

A relevant biological process is the:

**Cellular response to tumor necrosis factor / inflammatory signaling cascade**

This pathway is consistent with the proposed mechanism because TNF-TNFRSF1A signaling can activate intracellular pathways involved in inflammatory responses and cell-survival decisions.

> **Important interpretation:** STRING edges represent functional associations and predicted physical interaction networks. They should not automatically be interpreted as proof of direct physical binding between every connected protein.


## IntAct Validation

The selected molecular pair for validation was:

- **Molecule A:** TNF
- **Molecule B:** TNFRSF1A

### IntAct Record

**IntAct accession:** `EBI-15825849`

The curated record contains the following interacting molecules:

- TNF
- TNFRSF1A
- SMPD3
- RACK1
- EED

**Organism:** *Homo sapiens*

**Experimental detection method:**  
Affinity purification followed by mass spectrometry

**Primary publication:**  
PNAS  
DOI: `10.1073/pnas.0908486107`

The IntAct record supports the presence of TNF and TNFRSF1A within a **physical multi-protein signaling complex**.

The evidence is therefore stronger for **physical association within an experimentally detected molecular complex** than for proving direct binary binding between TNF and TNFRSF1A alone.



##  Final Cell-to-Cell Communication Model

### Proposed Information Flow

**Activated Microglia**  
↓  
**TNF production and secretion**  
↓  
**TNF in extracellular space**  
↓  
**TNFRSF1A on Astrocyte**  
↓  
**MADD + NSMAF + SPATA2**  
↓  
**Intracellular signaling**  
↓  
**Inflammatory gene expression and signaling**  
↓  
**Pro-inflammatory cytokine secretion + reactive astrogliosis**

### Final Model

The final model represents paracrine communication in which activated microglia release TNF into the extracellular space. TNF binds to TNFRSF1A on an astrocyte, initiating receptor-associated intracellular signaling.

The final diagram is provided as:

`05_final_model.jpg`



## Final Model Interpretation

This cell-to-cell communication model illustrates **paracrine signaling** between activated microglial sender cells and astrocyte receiver cells in the central nervous system. Activated microglia produce and release the pro-inflammatory cytokine **tumor necrosis factor (TNF)**, which diffuses through the extracellular space and binds to **TNF receptor superfamily member 1A (TNFRSF1A)** on the astrocyte cell surface.

Cross-database evidence supports the proposed signaling cascade. **STRING** network analysis identifies TNFRSF1A as a signaling hub associated with downstream components including **MADD, NSMAF, and SPATA2**. **IntAct** interaction data support the physical association of TNF and TNFRSF1A within a molecular complex detected by affinity purification and mass spectrometry. Following TNF-TNFRSF1A signaling, information is proposed to propagate through **MADD-associated MAPK signaling, NSMAF-associated sphingomyelinase signaling, and SPATA2-associated ubiquitin/NF-κB regulation**. These pathways can promote inflammatory gene expression and signaling, resulting in **pro-inflammatory cytokine secretion and reactive astrogliosis**.


## Answers to the Laboratory Questions

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

The sender cell is the **microglial cell**, a resident immune cell of the **central nervous system**. The model is placed in the context of **neuroinflammation and synaptic homeostasis**.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule is **TNF (tumor necrosis factor)**. The Human Protein Atlas reports evidence at the protein level, cytoplasmic expression in subsets of immune cells, and predicted **secreted** localization. These findings support TNF as a candidate extracellular signaling molecule produced by the sender cell.

### 3. What receptor receives the signal, and which receiver cell did you select?

The receptor is **TNFRSF1A (TNF receptor superfamily member 1A/TNFR1)**, and the selected receiver cell is an **astrocyte**. HPA brain-expression data annotate TNFRSF1A expression primarily in astrocytes.

### 4. What type of cell-to-cell signaling is represented?

The model represents **paracrine signaling** because microglia release soluble TNF into the local extracellular space, where it can act on neighboring astrocytes.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

The most relevant proteins are **MADD, NSMAF, and SPATA2**.

- **MADD** is associated with MAP kinase signaling and cell-survival pathways.
- **NSMAF** is associated with sphingomyelinase activation and secondary messenger generation.
- **SPATA2** is associated with ubiquitin-mediated NF-κB signaling.

These proteins provide intracellular connections between TNFRSF1A-associated signaling and downstream inflammatory responses.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The enriched pathway is the **TNF signaling pathway (KEGG hsa04668)**. A relevant biological process is the **cellular response to tumor necrosis factor/inflammatory signaling cascade**.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct record **EBI-15825849** contains TNF and TNFRSF1A within a molecular complex together with SMPD3, RACK1, and EED. The reported experimental method was **affinity purification followed by mass spectrometry**. This supports physical association within an experimentally detected molecular complex.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The **TNF ligand, TNFRSF1A receptor, microglial sender cell, astrocyte receiver cell, TNF signaling pathway, and associations with MADD, NSMAF, and SPATA2** are supported by database evidence.

The precise sequence of intracellular events and the specific magnitude of **reactive astrogliosis and pro-inflammatory cytokine secretion in the selected astrocyte context** remain an inference based on the integrated pathway evidence.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response is **increased inflammatory signaling, pro-inflammatory cytokine secretion, and reactive astrogliosis**. This is because TNF-TNFRSF1A signaling is associated with intracellular pathways involving **MAPK, sphingomyelinase signaling, and ubiquitin/NF-κB regulation**, which can alter gene expression and promote inflammatory cellular responses.


## References and Database Links

### The Human Protein Atlas

**TNF**
https://www.proteinatlas.org/ENSG00000232810-TNF

**TNFRSF1A**
https://www.proteinatlas.org/ENSG00000067182-TNFRSF1A

### STRING

STRING: Search and functional association network analysis  
https://string-db.org/cgi/network?taskId=bahjgLxAJTNL&sessionId=bKnUuaPnyWTm

### IntAct

IntAct Molecular Interaction Database  
[https://www.ebi.ac.uk/intact/](https://www.ebi.ac.uk/intact/search?query=TNF)

**IntAct accession:** `EBI-15825849`

### OmniPath

OmniPath: Molecular Signaling Network Resource  
https://omnipathdb.org/

### Primary Publication

Proceedings of the National Academy of Sciences (PNAS)
DOI: `10.1073/pnas.0908486107`
https://doi.org/10.1073/pnas.0908486107
