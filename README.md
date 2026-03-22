## 🔬 Project Highlights
- Performed complete RNA-Seq analysis pipeline
- Identified unique transcripts in Salmonella enterica
- Conducted functional annotation using Gene Ontology
- Performed comparative transcript analysis using Venny
- Applied molecular docking on selected targets# RNA-Seq-Salmonella-Transcriptome

RNA-Seq analysis using FastQC, Trinity, BLAST, and GO annotation

# Transcriptomic Analysis of Salmonella enterica

## Overview
This project focuses on RNA-Seq based transcriptome analysis to identify unique transcripts in Salmonella enterica.

## Tools Used
- FastQC
- Trimmomatic
- Trinity
- BLAST
- PANTHER (Gene Ontology)
- Venny
- AutoDock Vina (Docking)

## Workflow
1. RNA-Seq data retrieval from NCBI SRA
2. Quality control using FastQC
3. Read trimming using Trimmomatic
4. De novo assembly using Trinity
5. Sequence annotation using BLAST
6. Functional analysis using PANTHER
7. Comparative analysis using Venny
8. Molecular docking of selected targets

## 📊 Results

### Venny Diagram
This diagram shows the comparison of transcripts across different datasets and helps identify unique and shared genes.

![Venny](Venn%20diagram.png)

### Docking result

- Molecular docking was performed using AutoDock Vina to evaluate protein–ligand interactions  
- The ligand exhibited strong binding affinity with the target protein  
- Multiple docking conformations were generated, and the best pose was selected based on minimum binding energy  
- Interaction analysis revealed key hydrogen bonds and hydrophobic interactions stabilizing the protein–ligand complex  
- The ligand occupied the active site of the protein, suggesting potential inhibitory activity  
- Structural visualization using PyMOL confirmed proper orientation and binding within the active pocket  
- These results indicate that the ligand may act as a potential lead compound for further drug discovery studies

![Docking](Dock%20result%201.png)
![Docking](Dock%20result%202.png)
![Docking](Dock%20result%203.png)
![Docking](Dock%20result%204.png)

### FastQC Analysis (Raw Reads)
Quality assessment of raw RNA-Seq reads was performed using FastQC.  
The analysis provided insights into sequence quality scores, GC content, and potential adapter contamination.  
Minor variations in base quality were observed toward the end of reads, which is common in high-throughput sequencing data.

![FastQC Raw](FastQC%20Raw%20reads.png)

### FastQC Analysis (Trimmed Reads)
Post-trimming quality assessment was performed using FastQC to ensure data reliability.  
The trimmed reads showed improved quality scores across all base positions, with removal of low-quality bases and adapter sequences.  
This confirmed that the preprocessing step enhanced the overall data quality for downstream analysis.

![FastQC Trimmed](FastQC%20trimmed%20reads.png)

### Gene Ontology Analysis – Molecular Function
Functional annotation using PANTHER classified the identified transcripts based on their molecular functions.  
The analysis revealed that a significant proportion of genes are involved in catalytic activity, binding functions, and antioxidant activity.  
These functions indicate the presence of enzymes and regulatory proteins that play key roles in cellular metabolism and stress response mechanisms.

![Panther GO](PantherGo%20bioprocess.png)

### Gene Ontology Analysis – Biological Process
Gene Ontology classification under biological processes highlighted the involvement of transcripts in essential cellular and metabolic pathways.  
Key processes included cellular processes, detoxification, homeostasis, and response to external stimuli.  
These findings provide insights into the functional roles of genes contributing to pathogenicity, adaptation, and survival mechanisms.

![Panther GO](Panther%20Go%20Mol%20function.png)

### Unique Transcript Identification
Comparative analysis using Venny enabled the identification of unique and shared transcripts across datasets.  
A set of unique transcripts was identified, which may represent strain-specific genes with potential roles in pathogenicity and adaptation.  
These transcripts can serve as potential targets for further functional and therapeutic studies.

![Unique transkript identification](Unique%20transcripts.png)

### BLAST Analysis
Sequence similarity search was performed using BLAST against reference databases to annotate the assembled transcripts.  
The analysis identified homologous sequences and provided functional insights into gene identity and potential biological roles.  
Several transcripts showed significant similarity to known proteins, enabling downstream functional classification and annotation.

![Blast analysis](Blast%20result.png)


## 🧠 Skills Demonstrated
- RNA-Seq Analysis
- NGS Data Processing
- Functional Annotation (GO)
- Comparative Analysis
- Molecular Docking

## Author
Harini R
