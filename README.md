# In-Silico Structural Analysis of Human Carbonic Anhydrase II

## Overview

This project presents a computational analysis of human Carbonic Anhydrase II (CA II), integrating pharmaceutical concepts with bioinformatics and structural biology.

The study begins with protein sequence analysis and physicochemical characterization, followed by analysis of the experimentally determined three-dimensional protein structure. The zinc-containing catalytic region was investigated computationally by identifying nearby amino-acid residues and calculating their distances from the zinc ion.

The project demonstrates how Python-based bioinformatics tools can be applied to investigate a pharmaceutically relevant protein target.

## Objective

To perform an in-silico analysis of human Carbonic Anhydrase II using sequence, physicochemical, and structural information, and to characterize the zinc-containing active-site environment using computational methods.

## Data Sources

- **Protein:** Human Carbonic Anhydrase II (CA2)
- **UniProt Accession:** P00918
- **3D Structure:** PDB ID 1CA2
- **Organism:** Homo sapiens

## Tools and Technologies

- Python
- Biopython
- pandas
- NumPy
- Matplotlib
- PyMOL
- Jupyter Notebook

## Methodology

The project was carried out through the following computational steps:

1. Retrieved the human Carbonic Anhydrase II protein sequence from UniProt.
2. Stored and analyzed the CA2 FASTA sequence using Python.
3. Calculated protein length and amino-acid composition.
4. Calculated physicochemical properties using Biopython.
5. Loaded the experimentally determined 3D structure of CA II (PDB: 1CA2).
6. Identified the zinc ion present in the protein structure.
7. Identified amino-acid residues located within 4 Å of the zinc ion.
8. Calculated the minimum distance between the zinc ion and nearby residues.
9. Visualized the protein structure and zinc-containing active-site region using PyMOL.
10. Summarized the structural findings and their pharmaceutical relevance.

## Results

### 1. Protein Sequence Analysis

| Parameter | Result |
|---|---:|
| Protein | Human Carbonic Anhydrase II |
| UniProt Accession | P00918 |
| Sequence Length | 260 amino acids |
| Molecular Weight | 29,245.67 Da |
| Theoretical pI | 6.87 |
| Instability Index | 21.68 |
| GRAVY | -0.579 |

### 2. Structural Analysis

| Parameter | Result |
|---|---|
| PDB Structure | 1CA2 |
| Protein Chain | Chain A |
| Resolved Residues | 256 |
| Zinc Ions | 1 |
| Residues within 4 Å of Zinc | His94, His96, His119, Thr199 |

### 3. Zinc–Residue Distances

| Residue | Closest Atom | Distance from Zn (Å) |
|---|---|---:|
| His94 | NE2 | 1.995 |
| His96 | NE2 | 2.103 |
| His119 | ND1 | 1.910 |
| Thr199 | OG1 | 3.831 |

The structural analysis identified three histidine residues located very close to the zinc ion and Thr199 within the selected 4 Å local environment.

## Discussion

The sequence analysis showed that human Carbonic Anhydrase II consists of 260 amino acids and has a calculated molecular weight of approximately 29.25 kDa.

Structural analysis of PDB 1CA2 showed 256 resolved amino-acid residues in Chain A and identified one zinc ion within the protein structure.

The zinc-centered analysis identified His94, His96, His119, and Thr199 within 4 Å of the zinc ion. His94, His96, and His119 showed particularly close distances to the zinc ion, consistent with their important structural position in the zinc-containing catalytic region.

The computational analysis demonstrates how protein sequence information and three-dimensional structural information can be combined to characterize a pharmaceutically relevant protein target.

From a B.Pharm perspective, this project connects pharmacology, biochemistry, medicinal chemistry, and bioinformatics. It provides an example of how computational structural analysis can support the early investigation of protein targets in drug discovery.

## Conclusion

This project successfully performed an in-silico structural analysis of human Carbonic Anhydrase II using Python, Biopython, and PyMOL.

Protein sequence analysis provided information about the composition and physicochemical characteristics of CA II, while structural analysis of PDB 1CA2 identified the zinc-containing region and nearby amino-acid residues.

The project demonstrates how computational biology can be integrated with pharmaceutical knowledge to study biologically and pharmaceutically relevant protein targets.

Overall, this work provides a foundation for further computational studies involving protein–molecule interactions, molecular modeling, and computer-aided drug discovery.

# In-Silico Structural Analysis of Human Carbonic Anhydrase II

## Overview

## Objective

## Data Sources

## Tools and Technologies

## Methodology

## Results

### 1. Protein Sequence Analysis
### 2. Structural Analysis
### 3. Zinc–Residue Distances

## Discussion

## Conclusion
