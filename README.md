# bids-curation-checklist
A checklisting attempt to make the DCN's CURATED steps for data curation apply to BIDS.

To read all about DCN's CURATED Steps, go [here](https://datacurationnetwork.org/outputs/workflows/).

## C = Check files/code and read documentation (risk mitigation, file inventory, appraisal/selection)

- [ ] Begin Curator Log to track curation decisions
- [ ] Open the related article and supporting information if available
- [ ] Inventory the dataset
  - [ ] Identify file formats
  - [ ] Review file organization, hierarchy, and naming convention(s)
  - [ ] Extract zip files when possible
- [ ] Create working copy of files for formal inventory and testing
- [ ] Examine code for obvious errors/missing components, etc.
- [ ] Check that metadata quality is rich, accurate, and complete to institutional requirements.
- [ ] Check documentation type (readme / Codebook / Data Dictionary / Other: ________________________)
  - [ ] Complete
  - [ ] Needs work 
  - [ ] If missing, document for the “Request” step
- [ ] Check whether human subject data (data about humans regardless of IRB determination) is present. If so,
  - [ ] Request consent form / participation agreement if not present
  - [ ] If the data are not de-identified, document for the "Request" step.
- [ ] Check the accessibility of all files
  - [ ] Ensure there are robust descriptions in plain text of data files and any images.
- [ ] Check whether any visualization(s) of data are easily accessible
  - [ ] Review alt-text and visualization descriptions. Ensure these describe, but do not interpret, associated visualizations.
  - [ ] Check data visualizations follow accessible color contrast guidelines
  - [ ] Recommend graphical representation ____________
  - [ ] Recommend web-accessible surrogate ________________
 
## U = Understand the data (or try to), if not… (run files/code, QA/QC issues, readmes)

## R = Request missing information or changes (tracking provenance of any changes and why)

## A = Augment metadata for findability (DOIs, metadata standards, discoverability)

## T = Transform file formats for reuse (data preservation, conversion tools, data visualization)

## E = Evaluate for FAIRness (transparent usage licenses, responsibility standards, metrics for tracking use)

## D = Document all curation activities throughout the process

