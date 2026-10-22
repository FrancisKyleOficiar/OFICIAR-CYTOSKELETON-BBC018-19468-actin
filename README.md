# OFICIAR-CYTOSKELETON-BBC018-19468-actin

# Cytoskeleton and Cell Morphology
Student ID: 202303475
Name: Oficiar, Francis Kyle A.
Date Completed: October 22, 2026
Phenotype: Prometaphase 19648-actin.DIB, 19648-DNA.DIB
**Goal: Download and choose your own fluorescence images of HT29 human colon-cancer cells, select one phenotype, measure five cells in Fiji, make two plots in R, and document your work on GitHub.**

# PROCESS

<img width="1064" height="624" alt="image" src="https://github.com/user-attachments/assets/c8d9a8c5-5fa7-4899-aa3c-6bf0e1fb1287" />
Figure 1. Fiji ImageJ Software Download Page for Windows Installation and Windows x86-64 version was selected for installation on a Windows computer.

<img width="1064" height="598" alt="image" src="https://github.com/user-attachments/assets/43e9cb78-9fbd-4cdc-836a-15820f4bda61" />
Figure 2. Opening the .DIB images in Fiji with File > Import > Bio-Formats

<img width="874" height="650" alt="image" src="https://github.com/user-attachments/assets/7d0268f4-9d81-40ab-8a92-84184f35c6cd" />
Figure 3. Opening the field 19468 actin, DNA and pH3 images in Fiji (File > Open)

<img width="301" height="460" alt="image" src="https://github.com/user-attachments/assets/5145b615-bcfe-40f2-9583-4c2bf70b9a3c" />
Figure 4. Fiji Set Measurements: Area, Mean gray value, Shape descriptors, Display label

# Analyses & Answers

| Item | Answer |
|---|---|
| Phenotype chosen (visual classification) | Prometaphase |
| Image-field ID | 19468 |
| Actin filename | `19468-actin.DIB` |
| DNA filename | `19468-DNA.DIB` |
| Dataset page | [BBBC018 Dataset](https://bbbc.broadinstitute.org/BBBC018) |
| Download link | [Download BBBC018 Images (ZIP)](https://data.broadinstitute.org/bbbc/BBBC018/BBBC018_v1_images.zip) |
| Visible features supporting the phenotype | Chromosomes appear condensed and have not yet fully aligned at the cell's equator. They are beginning to interact with the mitotic spindle as the cell prepares for metaphase. |

<img width="307" height="455" alt="image" src="https://github.com/user-attachments/assets/593396cc-231f-4871-aec9-868a928e5e7e" />
Figure 5. BBBC018 reference example: prometaphase (field 19468)

# Open your chosen fluorescence images in Fiji

<img width="820" height="881" alt="image" src="https://github.com/user-attachments/assets/98880684-9ff6-45cf-9201-4fd09c88f920" />
Figure 6. Field 19468, F-actin channel (phalloidin), before measurement

<img width="820" height="881" alt="image" src="https://github.com/user-attachments/assets/7761a5b9-24de-4a86-9714-3a672a8456d1" />
Figure 7. Field 19468, DNA channel (Hoechst 33342), used as a guide for locating nuclei

### Table 1. The Three Fluorescence Channels of Field 19468

| Feature | Actin | DNA | pH3 (Optional) |
|---|---|---|---|
| **Filename** | `19468-actin.DIB` | `19468-DNA.DIB` | `19468-pH3.DIB` *(if available)* |
| **Stain** | Phalloidin | Hoechst 33342 | Phospho-histone H3 |
| **What it labels** | Filamentous actin (F-actin) in the cell body and edges | DNA within the nucleus | Phosphorylated histone H3, a marker associated with mitotic cells |
| **What you see** | Cell outlines and actin structures that help reveal cell shape | Nuclear DNA signals that help locate nuclei | Bright signals in cells positive for the mitotic marker |
| **Used for** | Examining cell shape and supporting cell tracing and measurement | Locating nuclei and distinguishing neighboring cells | Providing additional evidence of mitotic activity |

<img width="819" height="881" alt="image" src="https://github.com/user-attachments/assets/4b7c4efc-940c-49b1-bb12-4e451671023e" />
Figure 8. Five traced cells measured on 19468-actin.DIB (yellow outlines)

<img width="991" height="378" alt="image" src="https://github.com/user-attachments/assets/140aefd5-aa60-43df-b0cd-6fd8683cd79d" />
Table 2. Fiji measurements of five cells in field 19468 (19468-actin.DIB)

<img width="900" height="650" alt="actin_intensity" src="https://github.com/user-attachments/assets/ae100c5b-29bd-4504-aa6a-55082dda3057" />
Figure 9. Mean actin fluorescence of the five measured cells in field 19468

<img width="900" height="650" alt="area_vs_circularity" src="https://github.com/user-attachments/assets/68940d3e-c259-451f-8863-08056cab79ae" />
Figure 10. Cell area versus circularity for the five measured cells in field 19468

# EXPLAIN YOUR RESULTS

1. Which specific phenotype did you choose, and what visible features support that choice?

I chose Prometaphase as the candidate phenotype based on the reference images, where this stage is characterized by condensed chromosomes that have not yet aligned at the cell equator. However, the actin-stained image and the current measurements alone cannot confirm prometaphase; the DNA-stained image must show the corresponding chromosome morphology.

2. Were your five cells mostly round or elongated?

The five measured cells showed mixed shapes based on their circularity values, which ranged from approximately 0.43 to 0.84. Cells 1, 2, and 4 were relatively round, while Cells 3 and 5 were less circular and likely more irregular or elongated. Aspect-ratio values would be needed to distinguish elongation from other irregular shapes more confidently.

3. What role does actin play in maintaining cell shape and in cell movement (Karp Chapter 9)?

Actin filaments form part of the cell cortex beneath the plasma membrane, helping maintain cell shape and resist mechanical deformation. Actin polymerization and interactions with myosin generate forces that support cell protrusion, contraction, and movement.

4. Why can a single fixed fluorescence image NOT show how fast a cell moves?

A fixed fluorescence image captures cells at one moment and does not show changes in their positions over time. Measuring cell speed requires live-cell imaging at multiple time points so that displacement can be measured over a known time interval.

# References

Fiji (free): https://imagej.net/software/fiji/downloads
R (free): https://cran.r-project.org/
BBBC018 dataset page and phenotype examples: https://bbbc.broadinstitute.org/BBBC018
Direct download: BBBC018_v1_images.zip (46 MB): https://data.broadinstitute.org/bbbc/BBBC018/BBBC018_v1_images.zip
