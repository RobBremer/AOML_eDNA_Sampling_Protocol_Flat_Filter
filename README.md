# AOML_eDNA_Sampling_Protocol_Flat_Filter

---
# MIOP terms
methodology_category: sample collection
project: "NOAA Atlantic Oceanographic and Meteorological Laboratory Omics Program; https://github.com/aomlomics/protocols; https://zenodo.org/communities/aomlomics"
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: Atlantic Ocean [GAZ:00000344], Pacific Ocean [GAZ:]
broad_scale_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: environmental DNA [NCIT:C169106]
creator: Sean Anderson, Luke Thompson, Alyse Larkin, Adam Martiny
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique, research vessel experience
time_required: 120
personnel_required: 1
language: en
issued: 2026-03-12
audience: scientists
publisher: NOAA Atlantic Oceanographic and Meteorological Laboratory
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447]
env_local_scale: marine photic zone [ENVO:00000209]
env_medium: sea water [ENVO:00002149]
habitat_natural_artificial_0_1: 0
samp_collect_method: CTD rosette
samp_collect_device: Niskin bottle
samp_size: 1000
samp_size_unit: mL
samp_store_temp: -80
samp_store_sol: not applicable
samp_mat_process: Samples were filtered using a peristaltic pump (pore size 0.45 micrometers).
filter_passive_active_0_1:  1
prefilter_material: not applicable
size_frac_low: not applicable
size_frac: 0.22
filter_diameter: not applicable
filter_material: polyethersulfone
---

# NOAA/AOML Water Sampling Protocol using Sterivex (Dry)

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Christopher Sinigalliano | NOAA/AOML | <https://orcid.org/0000-0002-9942-238X> |  |
| Maribeth Gidley | NOAA/AOML, UM/CIMAS |  |  |
| Robert Bremer | NOAA/AOML, UM/CIMAS | <https://orcid.org/0009-0001-9057-7289> | 2026-06-08 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
- External Protocols: Protcols from manufacturers or other groups. 
- Include the link to each protocol.
- Include the version number (internal) or access date (external) of the protocol when it was accessed.

#### Internal Protocols

| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE |
| ------------- | ------------- | ------------- | ------------- |
| AOML 'Omics Protocols | https://github.com/aomlomics/protocols | not applicable | ongoing |
| NOAA/AOML Water Sampling Protocol using Sterivex (Beads) | https://github.com/aomlomics/AOML_eDNA_Sampling_Protocol_Sterivex_Beads | 1.2.3 | 2026-01-16 |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Not applicable |   |   |   |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2023-11-27 | Initial release |
| 1.0.1 | 2024-10-23 | Formatting edits |
| 1.1.0 | 2024-11-16 | Addition of FAIR eDNA terms in YAML front matter |
| 1.2.0 | 2025-01-08 | Clarified the concentration of bleach throughout |
| 1.2.1 | 2025-04-22 | Corrected storage temperature |
| 1.2.2 | 2025-12-15 | Updated YAML front matter |
| 1.2.3 | 2026-01-16 | Updated YAML front matter |
| 1.3.0 | 2026-03-18 | Copied and modified from NOAA/AOML Water Sampling Protocol using Sterivex (Beads) |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| NOAA | National Oceanic and Atmospheric Administration |
| AOML | Atlantic Oceanographic and Meteorological Laboratory |
| UM | University of Miami |
| CIMAS | Cooperative Institute for Marine and Atmospheric Studies |
| eDNA | environmental DNA |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Field negative control | Negative control created during sampling. Usually distilled (DI) or DNAse RNAse free water run through a comparable filter in place of a seawater eDNA sample. This will act as a control for contamination during field sampling. |
| Niskin bottle | Plastic cylindrical bottle used for collecting water samples at different depths. Comes in a variety of volumes. |

## BACKGROUND

### Summary

This protocol describes collection and filtration of marine [environmental DNA](target) samples using flat filters and can be adapted to collect water samples from individual [Niskin bottle](samp_collect_device), [CTD rosette](samp_collect_method), or flow through systems. This protocol is used by [NOAA's Atlantic Oceanographic and Meteorological Laboratory](publisher) and their collaborators.

### Method description and rationale

This protocol is used to pump [sea water](environmental_medium) samples collected via [Niskin bottle](samp_collect_device), [CTD rosette](samp_collect_method), or flow through systems and pump it through a 0.22 uM or .45 uM filter using a vacuum pump. The recommended filtration volume for coastal samples is 1-2 liters, which takes ~1 hour. Precautions are taken to minimize contamination of samples by thoroughly sterilizing all equipment prior to use. 

### Spatial coverage and environment(s) of relevance

This protocol can be used across any marine environment to effectively collect water samples for biodiversity monitoring. This protocol can tolerate a wide range of depths for sampling - NOAA's AOML samples from 1m up to 1000m.

## PERSONNEL REQUIRED

One person with pipetting experience. Research vessel experience is recommended but not required.

### Safety

This protocol utilizes flame-sterilization. Flammable liquids such as ethanol should be treated with care as to not ignite large volumes or within close proximity to sampling personnel in order to avoid burns. Standard precautions should be taken such as wearing PPE at all times to avoid skin and eye exposure especially when working with bleach.

### Training requirements

Standard molecular biology training including sterile technique and pipetting technique is required to properly conduct this protocol. Research vessel experience is recommended. Personnel should be trained in filtering protocol prior to conducting on ship.

### Time needed to execute the procedure

The process of setting up sampling equipment and filtering seawater will take ~1.5 hours ([90](time_required) minutes) depending on number of samples.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** | 
| Sample Bottles | 1 L Plastic Sample Bottle | Generic Brand | Depends on # of Samples | Size can vary, material must be autoclavable | 
| 20 L carboy | 20 L Nalgene carboy | Generic brand | 1 | |
| 20 L carboy Lid | Sealing 20 L carboy lid with ports | Nalgene or Generic Brand | 1 | |
| Vacuum pump | GAST Compressor/Vacuum pump pump | GAST | 1 | |
| Pump tubing | Masterflex Precision Pump Tubing, Peroxide-Cured Silicone EW-96400-24 | Cole Parmer | 2 | Depends on # of filtering manifolds |
| Hose-barbs | Hose Barb | Cole-Parmer | 1 | Depends on # of manifolds |
| Pipette Bulb | Valved Pipette Aspirator/Bulb | Cole-Palmer | 1 | Can also use a mechanical pipette filler |
| -20 °C freezer | -20 °C commercial chest freezer | Generic brand | 1 | |
| **Consumable equipment** |
| Flat filter | Banded Membrane 47mm White, 0.45µm Grid | ThermoScientific | 100 | Quantity depends on number of samples desired, remember to account for negative control field blanks |
| Flat filter | Banded Membrane 47mm White, 0.22µm Grid | ThermoScientific | 100 | Quantity depends on number of samples desired, remember to account for negative control field blanks |
| Pre-printed Cryo-Safe labels | Cryo-Babies LCRY-1700 | Diversified Biotech | 100 | Depends on # of samples, one per sample ||
| 2 ml Microcentrifuge Tube | Screw Cap Self Standing Microcentrifuge Tubes | Generic Brand | 100 | Depends on # of samples, one per sample |
| 1000uL Pipette Tip | Sterile pipetter tips | Generic Brand | 1 box | 
| Gloves | Powder-free nitrile gloves | Generic brand | 1 | (box) Can be any generic brand of gloves |
| Field notebook | Hard cover notebook | Generic brand | 1 | Encouraged to keep a digital sample log in addition to written notes |
| **Chemicals** |
| 5-9% Sodium hypochlorite | Household bleach | Generic brand | 1 | (bottle) Dilute 1:20 for lab use |
| Deionized or Milli-Q water | DI water | Generic brand | 8 | (L) Can use ship's DI water |
| DNA/RNA Shield | DNA/RNA Shield | Zymo | 50 mL | Depends on # of samples, 1000uL per sample |

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

## STANDARD OPERATING PROCEDURE

### Sampling Protocol

#### Preparing Sterivex Filters

1. Wearing gloves, prepare the Sterivex filters by opening sealed package and labeling each Sterivex filter with a pre-printed sticker.

#### Preparing Sampling Equipment

1. Attach tubing from the end of the filtering manifold to the lid of the carboy.
2. Attach tubing from the other port on the carboy lid to the inlet of the vacuum pump.
3. Fill 2ml tubes with 1000uL of DNA/RNA Shield.
4. Sterilize all filter funnel cups and sample bottles.
5. Collect sample water from Niskin bottle or flow-through system into a sterile sample bottle. Close cap on sample bottle. Avoid handling the sample bottle near the threads when open.
6. Gently place bottle in ice within a cooler to avoid damaging bottle.


#### Sample Filtration

1. Remove top of a sterile funnel filter cup. Repeat for each sample being filtered.
2. Using a pair of flame sterilized forceps, place a new flat filter at the base of the funnel filter cup. Repeat for each sample being filtered. Replace the top of the cup over the flat filter.
3. Fill the filter cup with sample water. Ensure to record the cumulative volume that is filtered through each filter.
4. Open valve and turn pump on to begin sucking sample water through the filter.
5. Once there is no water left in the cup and the filter has just dried, turn the pump off. Remove the top half of the cup, exposing the filter.
6. If the filter clogs before the water has been fully pumped through the filter, remove the remaining water using a sterile serological pipette.
7. Using a pair of sterilized forceps, fold the filter two times into a long cylindrical shape. Using the forceps, place the filter in a tube filled with 1000uL of DNA/RNA Shield.
8. On the log sheet, record the date, time, latitude, longitude, volume filtered and any notes about the sample. This information should be entered into an Excel spreadsheet every few days to maintain a digital copy in addition to the paper copy.
9. Gently remove any excess seawater from the filters using a sterilized 60 mL syringe.
10. In between filtering different water samples, rinse out the tubing with 1:20 dilution bleach solution, followed by DI water. Then proceed with the next volume of seawater.

#### Storage

1. Immediately freeze at ≤ –20 °C until extraction.

#### Post-Sampling

1. Autoclave all bottles used to collect seawater.
2. Autoclave all filter manifold cups use to filter seawater.
3. If you do not have access to an autoclave, rinse bottles and manifold cups with 10% bleach, then either DI water or DNAse/RNAse free water.

### Quality control

Negative field controls are included with every research cruise. DI or DNAse/RNAse free water is filtered in place of sample water. These filters are stored the same as other sample filters.

### Basic troubleshooting guide

Leaks

- If there is a leak present in the pump setup, you will notice trouble pulling water through the pump system. Check all seals and re-attach tubing.

Clogged Filter

- If a filter is clogged, turn valves and connections off and attempt to clear obstructions (i.e. large chunks of sediment or algae). Make note of any abnormal conditions and try to pump the full volume of seawater through the filter. In more productive areas, especially surface samples, we would frequently have filters that could not take the full volume. Since there are only two pumps and multiple sample depths at one time, it was common for us to use a cut-off time before starting the next sample (~45 min).

## REFERENCES

Not applicable.

## APPENDIX A: DATASHEETS

Not applicable.

## APPENDIX B: VIDEO & IMAGE FILES

[Filtering Video (Youtube): eDNA Sampling for Bio-GO-SHIP](https://www.youtube.com/watch?v=RjJ_bpb1z04)
