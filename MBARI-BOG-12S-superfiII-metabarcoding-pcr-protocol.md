---
# MIOP terms
methodology_category: Omics Analysis
project: Marine Biodiversity Observation Network (MBON)
purpose: detect diversity in Actinopteri
analyses: PCR [OBI:0000415]
geographic_location: Monterey Bay [GAZ:00002509]
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: upwelling [ENVO:01000005]
environmental_medium: sea water [ENVO:00002149]
target: 12S [NCIT:C128263]
creator: Katie Pitz; Jacoby Baker; Kobun Truelove
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989], agarose gel electrophoresis system [OBI:0001134]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 420
personnel_required: 1
language: en
issued: 2025-04-16
audience: scientists
publisher: Monterey Bay Aquarium Research Institute
hasVersion: 3
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
pcr_0_1: 1
thermocycler: # name of thermocycler
amplificationReactionVolume: 50
assay_name: # ssu16sv4v5_emp
assay_validation: # not provided
targetTaxonomicAssay: 12S rRNA gene sequencing the V5-V6 region using primers MiFish-F and MiFish-R
targetTaxonomicScope: fishes
target_gene: 12S rRNA
target_subfragment: V5-V6
ampliconSize: # 411
pcr_primer_forward: GTCGGTAAAACTCGTGCCAGC
pcr_primer_reverse: CATAGTGGGGTATCTAATCCCAGTTTG
pcr_primer_name_forward: 12S MiFish_U F Fluidigm
pcr_primer_name_reverse: 12S MiFish_U R Fluidigm
pcr_primer_reference_forward: http://dx.doi.org/10.1098/rsos.150088
pcr_primer_reference_reverse: http://dx.doi.org/10.1098/rsos.150088
pcr_primer_vol_forward: 3
pcr_primer_vol_reverse: 3
pcr_primer_conc_forward: 10
pcr_primer_conc_reverse: 10
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: Platinum SuperFi II PCR Master Mix
custom_mm: PCR reactions were run in 50 uL reaction volumes, with 3.0 uL of DNA, 25 uL of Platinum SuperFi II PCR MM, 16 uL of water, and 3.0 uL of each primer (10 uM).
pcr_dna_vol: 3
pcr_rep: 1
nucl_acid_amp: # https://doi.org/10.1111/1462-2920.13023
pcr_cond: initial denaturation:98_0.5;denaturation:98_0.16;annealing:62_0.16;elongation:72_0.5;13;final elongation:72_5;38
annealingTemp: 62
pcr_cycles: 38
pcr_analysis_software: not provided
pcr_method_additional: not provided
---

# Environmental DNA (eDNA) 12S Metabarcoding PCR Protocol (with Platinum SuperFi II Taq) V.3

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Jacoby Baker | MBARI | 0000-0002-0673-7535 | 2023-11-07 |
| N. Kobun Truelove | MBARI | 0000-0002-2236-1849 | 2023-11-07 |
| Kathleen J. Pitz | MBARI | 0000-0002-4931-8592 | 2023-11-07 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protcols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| Content Cell  | Content Cell | Content Cell | yyyy-mm-dd   | Content Cell      |
| Content Cell  | Content Cell | Content Cell | yyyy-mm-dd   | Content Cell      |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | yyyy-mm-dd | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

## BACKGROUND

### Summary

The 12S protocol is aimed at amplifying the hypervariable region of the mitochondrial DNA 12S rRNA gene in eukaryotes. The primers (MiFish-U-F & MiFish-U-R) used in this protocol were developed by Miya et al., 2015 for metabarcoding environmental DNA (eDNA) from fishes.


This work was supported by NASA grant NNX14AP62A ‘National Marine Sanctuaries as Sentinel Sites for a Demonstration Marine Biodiversity Observation Network (MBON)’ funded under the National Ocean Partnership Program (NOPP RFP NOAA-NOS-IOOS-2014-2003803 in partnership between NOAA, BOEM, and NASA), and the U.S. Integrated Ocean Observing System (IOOS) Program Office.

#### Citations
1. Miya M et al. 2015 MiFish, a set of universal PCR primers for metabarcoding environmental DNA from fishes: detection of more than 230 subtropical marine species. R.Soc.opensci. 2: 150088. [http://dx.doi.org/10.1098/rsos.150088](http://dx.doi.org/10.1098/rsos.150088)
2. Kawato, M., Yoshida, T., Miya, M., Tsuchida, S., Nagano, Y., Nomura, M., Yabuki, A., Fujiwara, Y. and Fujikura, K., 2021. Optimization of environmental DNA extraction and amplification methods for metabarcoding of deep-sea fish. MethodsX, 8, p.101238. [https://doi.org/10.1016/j.mex.2021.101238](https://doi.org/10.1016/j.mex.2021.101238)
3. [Platinum SuperFi II PCR Master Mix User Guide](https://www.thermofisher.com/document-connect/document-connect.html?url=https%3A%2F%2Fassets.thermofisher.com%2FTFS-Assets%2FLSG%2Fmanuals%2FMAN0018860_Platinum_SuperFi_II_PCR_MM_UG.pdf)



### Method Description and Rationale

This protocol follows an updated version of the MiFish primer PCR protocol. The Platinum SuperFi II was designed to have high fideleity and have increased resistence to PCR inhibitors.


### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to amplify extracted DNA from filtered sea water samples taken from marine coastal stations off the western coast of North America (primarily off of California).

- ocean [ENVO:00000015]
- freshwater lake [ENVO:00000021]

## PERSONNEL REQUIRED

1 technician

### Safety

>Identify hazards associated with the procedure and specify protective equipment and safety training required to safely execute the procedure

### Training Requirements

Sterile technique, pipetting skills.

### Time Needed to Execute the Procedure

Total time is 7 hours.
PCR preparation and running the PCR protocol takes 3 hours. Running the following gel is 1 hour, bead cleanup setup preparation and process takes 2 hours, and then another gel is run for 1 hour.

## EQUIPMENT

- Opentrons Consumables: If using Opentrons OT-2 Robot for KF Plate Prep.
- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| **Consumable equipment** |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| **Chemicals** |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |



## STANDARD OPERATING PROCEDURE


### Preparation

BEFORE STARTING
Disinfect work surfaces with 10% bleach or RNase Away followed by a MilliQ / DI water rinse and 70% ethanol wipe. Clean pipet surfaces with RNase Away and ethanol wipe.

UV pipets, molecular grade water, and tube racks for 30 minutes prior to starting protocol.


### PCR

1. PCR reactions were run in single 50ul reactions for each sample using the MiFish_U primers (Miya et al. 2015) with Fluidigm adapters CS1 & CS2

> Primer Sequences with Fluidigm adapter sequences in the 5’ to 3’ direction
>
> - Fluidigm CS1+**MiFish_U** (forward): 
  > ACACTGACGACATGGTTCTACA **GTCGGTAAAACTCGTGCCAGC**
> - Fluidigm CS2+**MiFish_U** (reverse): 
  > TACGGTAGCAGAGACTTGGTCT **CATAGTGGGGTATCTAATCCCAGTTTG**

2. PCR reactions were run in 96-well plates with two no-template controls (NTCs) run for each plate. One well is kept empty for a sequencing control (introduced later). One positive control is run per plate. PCR cycling parameters use a normal ramp speed.


**Primers**: PCR primer sequences

| PCR Primer Name | Direction | Sequence (5’ -> 3’)| Sequence (5’ -> 3’) with Fluidigm Adapters | Fluidigm Adapter |
| ----- | ----- | ----- | ----- | ----- |
| MiFish_U | forward | GTCGGTAAAACTCGTGCCAGC | ACACTGACGACATGGTTCTACA **GTCGGTAAAACTCGTGCCAGC** | CS1 |
| MiFish_U | reverse | CATAGTGGGGTATCTAATCCCAGTTTG | TACGGTAGCAGAGACTTGGTCT **CATAGTGGGGTATCTAATCCCAGTTTG** | CS2 |



**Reaction Mixture**: PCR reagents, volumes, initial and final concentrations

| Reagent | Volume | Initial Concentration | final concentration|
| ----- | ----- | ----- | ----- |
| DNA extract template | 3 μl | content |content |
| 2X Platinum SuperFi II PCR MM | 25 μl | content |content |
| forward primer | 3 μl | 10 μM |content |
| reverse primer | 3 μl | 10 μM |content |
| molecular-biology grade water | 16 μl | content |content |

**PCR Cycling Program**: 

| PCR Step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Intial Denaturation | 98° C | 30 seconds | 1 |
| Denaturation | 98° C | 10 seconds | 38x |
| Annealing | 62° C | 10 seconds | 38x |
| Extension | 72° C | 30 seconds | 38x |
| Final Extension | 72° C | 5 minutes | 1 |
| Hold | 4° C | ∞ |  |

>For primary 12S cycling parameters, we use the manufactuer's recommendation with a slight modification. The Platinum SuperFi II is designed to be used with a universial 60°C annealing temperature, however, we found we had better results with an annealing temperature of 62°C to reduce bacterial co-amplification.


### Quality Control

3. After primary PCR amplification of the marker region the PCR product was run through a 2% agarose gel to confirm the presence of target bands (~270 bp) and absense of non-specific amplification (bacterial band ~370 bp) across environmental samples.


#### Positive Control

Please include information about any positive controls, used in every PCR run to verify success of the PCR reaction. This should include a description of the sequence(s), the concentration and volume added, and the reference sequence(s).

#### Negative Control

Please include information about any negative controls, such as PCR-grade water used as a no template control (NTC) when setting up each PCR plate.

### PCR Clean-up

4. Primary PCR products were purified and size selected using the Agencourt AMPure XP bead system (Beckman Coulter, USA) at 0.9x volume beads to product.
5. A second agarose gel was run to confirm primer removal and retention of target amplicons after purification. NTCs were also tested using a Qubit dsDNA 1x high sensitivity kit to ensure no amplification.


### Basic Troubleshooting Guide

- Identify known issues associated with the procedure, if any.
- Provide troubleshooting guidelines when available.

## REFERENCES

- Insert all references cited in the document.
- Please insert full DOI address when available, e.g. http://doi.dx.org/10.1007/s11258-014-0404-1.

## APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance.
