---
# MIOP terms
methodology_category: sample collection
project: CalCOFI MOSAIC eDNA Sampling
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: North Pacific Ocean [GAZ:00002418]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], marine aphotic zone [ENVO:00000210]
local_environmental_context: marine pelagic zone [ENVO:00000208], marine pelagic biome [ENVO:01000023]
environmental_medium: sea water [ENVO:00002149]
target: environmental DNA [NCIT:C169106]
creator: Nastassia Patin, Eldridge Wisely, Ella Crotty
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique, research vessel experience
time_required: 30-85
personnel_required: 1
language: en
issued: 2025-12-16
audience: scientists
publisher: Scripps Institution of Oceanography, UC San Diego
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
checkls_ver: 1.0.2
samp_category: sample
sterilise_method: Bleach and DNAway
neg_cont_0_1: 1
pos_cont_0_1: 0
habitat_natural_artificial_0_1: 0
samp_collect_method: CTD
samp_collect_device: Swinnex filter housing
samp_size: 1-3
samp_size_unit: L
samp_store_temp: -80
samp_store_sol: DNA/RNA Shield
mod_date: 2025-12-16
accessRights: publicly available
bibliographicCitation: None
code_repo: github.com/CalCOFI/eDNA-protocols
---

# CalCOFI Sampling From CTD

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
| Nastassia Patin | UC San Diego, CalCOFI | 0000-0001-8522-7682 | 2025-12-16 |
| Eldridge Wisely | UC San Diego, CalCOFI | 0009-0001-2784-4778 | 2025-12-16 |
| Ella Crotty | UC San Diego, CalCOFI | 0009-0004-4340-2007 | 2025-12-16 |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-12-16 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| CalCOFI | California Cooperative Oceanic Fisheries Investigations |
| CTD | Conductivity, Temperature, Depth (Instrument) |
| eDNA | environmental DNA |
| PCR | Polymerase Chain Reaction |
| SIO | Scripps Institution of Oceanography |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Niskin bottle | Water sampling bottle attached to CTD rosette, used to sample seawater at different depths |

## BACKGROUND

### Summary

This protocol describes the sampling of marine eDNA from water sampled from a CTD Niskin bottle. This protocol was used on CalCOFI cruises, but could be adapted for use on any research vessel with a CTD. The end result of this protocol is filters with preserved eDNA from seawater from whatever depth the selected Niskin bottle triggered at.

### Method description and rationale

This protocol describes sampling eDNA from a Niskin bottle sample. Water is sampled from the Niskin bottle and brought into the ship's lab. There, the sample is placed somewhere secure and a tube with a serological pipette on the end is placed in the sample. The other end of the tube must have a nut attachment, which is then attached to a Swinnex filter housing with a filter in it, and the tube is run through a peristaltic pump to pump the sample water through the filter. The filter, now containing environmental DNA, is preserved.

### Spatial coverage and environment(s) of relevance

This protocol can be used on any oceanographic research vessel with a CTD or similar water sampler.

## PERSONNEL REQUIRED

One person with pipetting experience. Research vessel experience is recommended but not required. Two people can sample 24/7.

### Safety

There are no major safety concerns with this protocol. Proper PPE should be worn at all times, especially when sterilizing equipment with bleach. Appropriate work gear should be worn on deck and near the CTD according to the vessel's protocol.

### Training requirements

Standard molecular biology training including sterile technique and pipetting technique is required to properly conduct this protocol. Research vessel experience is recommended. In-person training in this method prior to the cruise is recommended.

### Time needed to execute the procedure

The process of taking the sample should take approximately 5-10 minutes. Filtering the sample may take anywhere from 15-60 minutes depending on particulate and chlorophyll concentration in the seawater and functionality of the peristaltic pump. Preserving the sample should take approximately 10-15 minutes.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| 20 L carboy | 20 L Nalgene carboy | Generic brand | 1 | To hold bleach. Label "DO NOT PUT DOWN DRAIN". |
| Peristaltic pump motor | Motor Model No. 07559-10, 1-100 RPM | Cole-Parmer Instrument Company | 1 | |
| Peristaltic pump heads | Easy-Load II L/S, Model 77200-60 | Masterflex | 2 | Enough pump heads for however many parallel CTD samples you plan to process. Ensure that the pump heads are compatible with your tubing size. |
| Tubing | Masterflex 6424-17 | Masterflex | 10 | **Ensure that your TUBE SIZE is compatible with your peristaltic pump before departing for a cruise.** Bring at least one tube per parallel sample (Underway, CTD, and replicates) and bring extras in case of damage. See Appendix C for sizing information. |
| Serological pipette | 10 mL Serological Pipette | Generic brand | 2 | Use metal forceps to remove any internal filter |
| 1 L graduated cylinder | Graduated cylinder - 1 L | Generic brand | 1 | Used to measure outflow |
| -80 °C freezer | -80 °C commercial chest freezer | Generic brand | 1 | |
| Forceps | Plastic or metal forceps | Generic Brand | 4 | This protocol uses approx. 50 plastic forceps and sterilizes them when more are needed. 4 metal forceps with constant sterilization would also work (see scissors sterilization protocol). Metal forceps are useful for removing the serological pipette filter. |
| Cryovial rack | Any rack that fits final sample storage cryovials | Generic brand | 1 |  |
| Ruler/straightedge | Ruler | Generic brand | 1 | Useful for lab notebook records |
| PCR station | MY-PCR Prep Station | Mystaire | 1 | Portable hood with fan, not needed if you have access to a hood on the research vessel. Bring power cord. |
| Permanent Marker (Thick) | Sharpie Permanent Marker, Fine Point, Black | Sharpie | 2 | To label large items |
| Permanent Marker (Thin) | Sharpie Permanent Marker, Extra Fine Point, Black | Sharpie | 2 | To label cryovials |
| Pencils | Pencil | Generic brand | 5 | To write in lab notebook, include extras. |
| Screw end for tubing | Stainless Steel 1/4" Hose Barb to 1/4" Female | Beduan or generic brand | 4 | To attach the filter housings to the tube. Assemble the tubing with housing before departing on a cruise to ensure good fit. |
| **Consumable equipment** |
| Field notebook | Notebook, ideally with waterproof pages | Generic brand | 1 | Transfer to digital sample sheet once a day during cruise |
| Sterile collection bags | Whil-Pak collection bags | Whirl-Pak Filtration Group | 1 box | Various sizes can be used for water collection, 3-5 L recommended for CTD sampling. Expect to use one per CTD sample. |
| DNA/RNA Shield | Zymo DNA/RNA Shield, Catalog # R1100-250 | Zymo Research | 250 mL | 0.4mL required per sample. |
| DNAway | DNA Away Catalog # 7010 | Molecular BioProducts | 250 mL | For sterilizing the hood, pipette, and scissors. |
| Gloves | Powder-free nitrile gloves | Generic brand | 1 box | Expect approximately 3 boxes for a 10-day cruise. Can be any generic brand of gloves. |
| 1000 µL Pipette Tips | 1000 µL Pipette Tips | Generic Brand | 1 box | Quantity depends on cruise length. Expect 1 tip per sample. Verify that tips fit your pipette before cruise begins. |
| Filters | 5.0 µm MCE Filters, 47 mm | Millipore | 1 | Quantity depends on cruise length. Expect 1 filter per sample and bring extra. |
| Cryovials | CryoELITE® Cryogenic Vials, Freestanding, External Thread, 2 mL | Wheaton | 1 | Quantity depends on cruise length. Expect 1 cryovial per sample. |
| Cryovial storage box | Cardboard box with grid inside for cryovials | Generic brand | 1 | Enough boxes to store all samples in freezer. |
| Shop towels | Shop towels | Generic brand | 1 roll | Used to cover the benchtop in the PCR hood. Expect to replace every 5-10 samples. |
| Ziplock bags | Gallon-sized ziplock bags | Ziploc | 1 box | Used to sterilize equipment. Expect it to need replacing every 3-5 sterilizations. |
| Repair tape | White Duct Tape | Generic Brand | 1 roll | For repairs. |
| **Chemicals** |
| 5-9% Sodium hypochlorite | Household bleach | Generic brand | 1 bottle | Dilute 1:10 for sterilization |
| Deionized or Milli-Q water | DI water | Generic brand | 2 | (L per sterilization) Can use ship's MilliQ water |

## STANDARD OPERATING PROCEDURE

### Notes
- At every station, there will be a CTD cast. This cast will capture water in Niskin bottles from multiple depths. If your schedule allows, you should sample water from bottles taken at different depths, mix these samples, and filter them in the same way as you are filtering the underway water sample water from the surface bottle and filter it using the peristaltic pump. See below for full protocol.

### Time Management
- Setup at the beginning of a shift:
  - Use DNAway to wipe down the hood, pipette, DNA/RNA Shield bottle, and anything else you touch a lot (See Step 2 below)
  - Swap out the shop towel
- Before each station (30-60 mins before):
  - Check the protocol and any plans you have for replicates so you know what you're doing on station
  - Check with CTD team and ask if you could have a second surface Niskin bottle taken if they have a spare
  - Make sure you've bleached enough equipment to use on station: Enough housings for the samples you'll take, the tubing you use for CTD filtering, forceps
  - Keep an eye on the ship's speed! Depending on the ship, starting and stopping could be very smooth and tough to notice.
- On station:
  - Check your latitude and longitude, take a picture or write it down
  - Record or ask when the CTD goes down and comes up
  - After everyone else has taken CTD samples (this may be after station), take a whirlpak or ziplock bag full of water from the shallowest bottle
- Leaving station:
  - Check latitude and longitude, take a picture or write it down
  - Filter CTD water from the bag into a filter housing and hold the waste water in something to measure the volume filtered
- During spare time:
  - Sterilize housings and forceps
  - Data entry (try to do at least once per day)
  - Check with marine mammal observers, note sightings and audio detections
- End of shift:
  - If working alone, make a note of any issues, clean up and secure station.
  - If working shifts, pass on any information about equipment issues and current samples running.

### Sampling Protocol

#### Setup

1. Set up the hood for your clean work space. This is where you will assemble the new filters + housings, and transfer the filters from the housings to the cryovials.
2. Decontaminate the inside the hood thoroughly using DNAway or bleach. Spray the solution, let sit for 10 minutes, and wipe down.
3. Wipe down your forceps, cleaning solutions, P1000 pipet and tips, DNA/RNA Shield bottle, Sharpies and anything else you will use consistently in the hood before storing them inside.
4. After the hood has been decontaminated, keep it closed at all times unless working in it.

#### CTD Water Filtration

There may be extra water available from the CTD cast, particularly from deeper bottles. If this happens during your shift and you have the time and ability to do so, you can sample this extra water for a direct comparison with the underway samples.
With the new CTD, you may also be able to request an additional Niskin at the surface for eDNA sampling. Make sure to request this before bottles are prepped (this time will be written on the whiteboard in the main lab)
Check with the CalCOFI technicians which bottle numbers have extra water available.

1. Sample at least 1 L water from 3-5 bottles or 3 L from one surface bottle; they can be from different depths.
2. From each bottle: open the valve at the bottom of the Niskin bottle. Allow water to flow for 5-10 seconds and use the flow through to rinse your collection bottle 3x. without collecting it. Place your collection container under the flow and collect ~1-3 L. Close the valve, move to the next bottle, repeat.
    - Alternatively, use a sterile whirlpak instead of a bottle
3. Record the bottle numbers, depths and volume sampled from each bottle. From the CTD console, you should also record latitude and longitude in decimal degrees, CTD cast number, and the time the CTD was pulled up.
4. Mix the sample container by swirling it around.
5. Take the sample into the lab and use it as the source water for your filter. Perform the filtration by running a tube through the peristaltic pump, with a serological pipette tip in the sample and a nut attachment connecting the other end of the tube to a Swinnex filter housing.
    - Use separate tubing connected to a serological pipette tip with the cotton filter removed.
    - Only clamp the tube down in the peristaltic pump when actively filtering. This prevents additional wear and tear on the tube.
6. Measure the filtrate volume using the graduated cylinder and mark the filtration end time. This is very important!
7. In the PCR hood, set out your forceps decontamination kit: 4 x 50 mL Falcon tubes containing DNAway, water (x 2 tubes), and 100% EtOH, in that order.
8. Detach the Swinnex housing + filter from the tubing and bring them into the hood.
9. Label a cryovial with the cruise number and filter number.
10. In the hood, disassemble the Swinnex and transfer the filter into a labeled cryovial. Decontaminate your forceps by dipping them sequentially into the Falcon tubes before touching the filter. Label the tube - see below for the labeling scheme.
    - Roll the filter into a little tube or fold into eighths and stick into the cryovial. It is helpful to use two sets of forceps for this. See video protocol for one possible technique to do this with one pair of forceps.
6. Between CTDs (for instance, while you are filtering the underway) rinse your collection container three times with milliQ water or use a new collection container. Remember to unclamp the tube in the peristaltic pump.

#### Sample Preservation

1. Using a P1000 (1000 µL pipette), add 400 uL of DNA/RNA Shield preservative into the cryovial.
2. Place the cryovial in a -80ºC freezer as soon as possible.

#### Storage

1. Freeze at –80°C in a box with other samples until extraction.

#### Post-Sampling/Sterilization

- You do not need to sterilize all tubing and filter housings in between every sample, but you should try to clean periodically.
- Clean both the tubing and the filter housing by attaching the empty housing (without a filter) to the tubing.
- Clean the filter housings by placing the tops in one bag and the bottoms in another, soaking in bleach 15 minutes, then rinsing and shaking three times with milliQ water in the bag.
- Cleaning can entail:
  - Running bleach through the tubing and serological pipette for 10 minutes (both ends of the tube in the same bag, so it recirculates), then run milliQ water through the tubing and serological pipette for 20 minutes (one end of the tube in a different bag, so it does not recirculate and both ends are in bags instead of out in the air).
  - Running 1-2L sample water through the tubing and housing before adding in a filter.
  - Running 1-2L milliQ or DI water through the tubing and housing before sampling.
  - Running 500mL diluted (5-10%) bleach through tubing and housing, followed by running 2-3 L sample water to thoroughly rinse.
  - Adding 1-2L diluted bleach to the intermediate container (carboy), then rinsing thoroughly with DI water.
  - Wiping down the benches and other surfaces with 70% ethanol and/or DNAway.
- For every sample, allow the sample water to run through tubing for 5 minutes before adding a filter. This will flush any residual bleach and/or material from a previous sample.
- Do not allow bleach to go down the sink. Bleach can go in and out of its bottles and bags, and in the bleach waste carboy if it is dirty and you need to make new bleach.

#### Data records

- While filtering, record all the relevant information on the printed copy of the appropriate data sheet (underway vs CTD samples).
- Periodically (at least once per day) transcribe the written records into the electronic copy of the sample sheet.
- Full underway sample IDs should be as follows:
\<CRUISE-ID>_ \<LINENUMBER-TRANSECTNUMBER>_\<FILTER-NUMBER>
  - For example: RS2311\_LINE80-01\_F001
- Full CTD sample IDs should be labeled as follows:
\<CRUISE-ID>\_\<STATION>\_\<CTD-CAST>_\<FILTER-NUMBER>
  - For example: RS2311\_90-55\_C001_F002
- Cryovials can be labeled with the filter number only (F001 - FXXX)

### Quality control

**Negative Controls**
- During a transect or station, attach a filter in a filter housing to a tube in the peristaltic pump. Run MilliQ water from the ship through the same serological pipette and tube that other CTD samples have gone through for the duration of the station. Process filter the same way as the sample filters (steps 12-15 of underway filtration).

### Basic troubleshooting guide

**Filter clog**

If the filter clogs, end the sample and record whatever volume did make it through.

**Peristaltic pump not pumping**

If the peristaltic pump is making its normal noises but water is not coming out of the housing, here are some things you can do:
- Feel along the tube for leaks or cracks.
- Open the peristaltic pump clamp to see if the pump has chewed up the tube. Replace tube if needed.
- Look along the tube for compressed sections. If you see one, turn the speed down and massage the compressed section until it pops back into shape. Wait until water comes out to turn the speed up.
- Moving the tube so that a different section is clamped in the peristaltic pump regularly helps prevent damage and improve flow.

**Filters keep coming out torn**

If filters are torn when you open the filter housing to preserve them, try not tightening the housings quite as hard. Undertightening can lead to leaks, but overtightening can lead to filter tears.

**Filter housing is leaking**

Screw the housing together tighter. If the problem persists, try to screw it together straighter.

**Out of Whirlpak bags**

If you run out of whirlpak bags, fresh ziplock bags may be used for CTD sampling.

## REFERENCES

Work in progress.

## APPENDIX A: DATASHEET TEMPLATE

Final latitude and longitude should be in decimal degrees, but that can be calculated later as a different column. Column names can be abbreviated.

![Sample sheet template](https://github.com/CalCOFI/MOSAIC_CTD_Sampling/blob/main/CalCOFI%20eDNA%20Niskin%20Sample%20Sheet%20TEMPLATE.xlsx)


## APPENDIX B: VIDEO & IMAGE FILES

[Video protocol](https://youtu.be/uCHXO4iRwDQ?si=7Tvsbfo6uyvfpjgL)

![CTDPipette)](https://github.com/CalCOFI/MOSAIC_CTD_Sampling/blob/main/CTDPipette.JPG)

Figure 1. Serological pipette in CTD sample as described in this protocol.

![Backflow)](https://github.com/CalCOFI/MOSAIC_CTD_Sampling/blob/main/CarboyMarkings.JPG)

Figure 2. Swinnex filter housing backflow, shown here using the underway tap but can be done very similarly with the CTD sample outflow from the peristaltic pump.

![OutflowMeasurement)](https://github.com/CalCOFI/MOSAIC_CTD_Sampling/blob/main/OutflowMeasurement.JPG)

Figure 3. Step 6. Measure the filtrate volume using the graduated cylinder and mark the filtration end time. This is very important!

![PCRHoodSetup)](https://github.com/CalCOFI/MOSAIC_CTD_Sampling/blob/main/PCRHoodSetup.JPG)

Figure 4. PCR hood setup used in this protocol.

## APPENDIX C: PERISTALTIC PUMP TUBE SIZING

It is **extremely important** to ensure that your tubes are compatible with your peristaltic pump! Pump heads should have compatible tube sizes printed on them. [This website](https://blog.darwin-microfluidics.com/masterflex-l-s-pump-heads-the-ultimate-guide/) has more information, and the sizing tables from the website are copied below.

### Masterflex L/S Tube Sizes & Names

||L/S Precision Tubing |||||| L/S High-performance Precision Tubing||||
|-|-|-|-|-|-|-|-|-|-|-|
|L/S Tubing Size|13|14|16|25|17|18|15|24|35|36|
|L/S Tubing Name/Inner Diameter (mm)|0.8|1.6|3.1|4.8|6.4|7.9|4.8|6.4|7.9|9.7|

### Masterflex L/S Tube Sizes and Pump Head Compatibility

x = compatible

\- = not compatible

|Pump Head|13|14|16|25|17|18|15|24|35|36|
|-|-|-|-|-|-|-|-|-|-|-|
|Standard|x|x|x|-|x|x|x|x|x|x|
|Easy-Load|x|x|x|x|x|x|x|x|-|-|
|Easy-Load II & 3|x|x|x|x|x|x|x|x|x|x|
|Multichannel|x|x|x|-|-|-|x|x|x|x|
|Multichannel Cartridge|x|x|x|x|x|-|-|-|-|-|
|High-Performance|-|x|x|-|-|-|x|x|x|x|
