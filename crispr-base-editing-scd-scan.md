# CRISPR Base Editing for Sickle Cell Disease — Brief Literature Scan

**Scope:** base editing of the γ-globin (*HBG1*/*HBG2*) promoter to induce fetal hemoglobin (HbF), direct HbS→HbG-Makassar correction, and in vivo delivery. **Search date:** 19 Oct 2026. **Sources:** PubMed (MCP) with abstracts retrieved from Europe PMC / NCBI E-utilities. Emphasis on 2023–2026 primary literature.

---

## Why base editing rather than nuclease cutting

Cas9 therapies (e.g., exa-cel) create double-strand breaks and rely on variable indels to disrupt a *BCL11A* binding motif. Base editors instead install a defined transition (A•T→G•C for adenine base editors) that recreates hereditary persistence of fetal hemoglobin (HPFH)-like promoter variants, blocking BCL11A binding while leaving *BCL11A* itself intact. Because the edit is a single defined base change rather than a heterogeneous indel, HbF induction is more uniform across cells — which matters, since HbF protects red cells in a dose- and distribution-dependent way.

---

## Key recent findings

### 1. First clinical proof of concept: risto-cel (BEAM-101) in the BEACON trial

**Gupta AO, et al. Base Editing of *HBG1* and *HBG2* Promoters for Sickle Cell Disease. *N Engl J Med.* 2026;394(18):1824–1835.** doi:10.1056/NEJMoa2504835 · PMID 41931046

- Phase 1–2, 31 patients aged 12–35 y with ≥4 severe vaso-occlusive crises (VOCs) in the prior 2 years; myeloablative, pharmacokinetically guided busulfan; single infusion of ≥3.0×10⁶ viable CD34+ cells/kg.
- Median follow-up 6.6 months (range 0.3–20.4). Neutrophil engraftment at 17.5 days, platelets at 19 days.
- At 6 months: **mean 67.4% on-target edited alleles**, **mean HbF >60% of total hemoglobin**, **HbS <40%** (n=13), maintained through follow-up.
- **No investigator-reported severe VOC** occurred later than 60 days after the last red-cell transfusion.
- Safety: all 31 had ≥1 adverse event; 87% had grade ≥3; 39% had a serious adverse event; one death from idiopathic pneumonia syndrome.
- *Caveats:* unplanned interim analysis, single-arm, short and uneven follow-up, industry-funded.

### 2. Feasibility extends across genotypes — including SCD

**Liu R, et al. Clinical base editing for β-hemoglobinopathies across different genetic backgrounds. *Cell Stem Cell.* 2026;33(10):1597–1609.e4.** doi:10.1016/j.stem.2026.08.009 · PMID 42705233

- Transformer base editor (tBE) targeting the *HBG1*/*HBG2* promoter in a four-patient descriptive report from three trials: one African patient with SCD and three patients with transfusion-dependent β-thalassemia (TDT) carrying mutations common in South and Southeast Asia.
- All patients achieved hematopoietic recovery and discontinued red-cell transfusion. Beyond 12 months: durable editing, sustained high-level **pan-cellular HbF**, and transfusion independence. No vaso-occlusive episodes in the SCD patient; no off-target mutations, malignancies, or deaths reported.
- *Why it matters:* prior tBE clinical experience was TDT-only in Chinese patients. This extends the platform to SCD and to genotypes prevalent outside East Asia. n=4, descriptive — hypothesis-generating, not efficacy evidence.

### 3. Mechanism: the −175A>G edit beats Cas9 strategies and reduces variegation

**Mayuranathan T, et al. Potent and uniform fetal hemoglobin induction via base editing. *Nat Genet.* 2023;55(7):1210–1220.** doi:10.1038/s41588-023-01434-7 · PMID 37400614

- Five strategies compared head-to-head in CD34+ hematopoietic stem and progenitor cells. Adenine base editor installation of the γ-globin **−175A>G** HPFH-like variant was the most potent.
- Homozygously edited erythroid colonies expressed **81 ± 7% HbF** versus **17 ± 11%** in unedited controls.
- HbF was lower and more variable with two Cas9 nuclease strategies (cutting a BCL11A binding motif in the γ-globin promoter, or the *BCL11A* erythroid enhancer), and the base edit was also more potent in red cells derived after CD34+ transplantation into mice.
- Broader point: Cas9-generated indels cause unexpected phenotypic variation that a defined base transition avoids.

### 4. The alternative target has a functional catch: HbS→HbG-Makassar

**Kostamo Z, et al. Base editing HbS to HbG-Makassar improves hemoglobin function supporting its use in sickle cell disease. *Nat Commun.* 2025;16:1441.** doi:10.1038/s41467-025-56578-3 · PMID 39920120

- Adenine base editing converts HbS (βE6V) to **HbG-Makassar (βE6A)**, a naturally occurring, clinically asymptomatic variant. Purified HbG appeared normal and **did not polymerize under hypoxia**; the βE6A fold resembled HbA in oxy and deoxy states.
- However, red cells containing **HbGS** (edited β-chain paired with residual HbS) were dehydrated, functionally altered, and sickled more under hypoxia. Blood counts and mitochondrial retention placed HbGS **between HbAS and HbSS** in severity; organ function was comparable to HbAS. **HbGG resembled HbAA** on most metrics.
- *Implication:* a direct-correction strategy is only as good as its editing homogeneity — near-complete biallelic editing is required. HbF induction is more forgiving of residual unedited cells, which is a substantive argument for the promoter-editing approach now in the clinic.

### 5. Delivery: in vivo LNP base editing to bypass apheresis and busulfan

**Xu S, et al. In vivo genome editing of human haematopoietic stem cells for treatment of blood disorders using mRNA delivery. *Nat Biomed Eng.* 2026;10(3):473–489.** doi:10.1038/s41551-025-01480-y · PMID 40796944

- Antibody-free targeted lipid nanoparticles delivering **ABE8e/sgRNA mRNA** to hematopoietic stem cells in vivo, achieving efficient *HBG1/2* promoter editing in human HSCs.
- In TDT patient-derived HSCs engrafted in immunodeficient NCG-X mice, editing restored globin chain balance in erythroid cells.
- Removes three bottlenecks at once: stem-cell collection/mobilization, ex vivo manufacturing, and chemotherapeutic conditioning.
- *Status:* preclinical. Human HSC targeting efficiency, editing durability, and innate/adaptive immune responses to repeat dosing remain unresolved.

---

## Cross-cutting caveats

- **Conditioning, not editing, is now the dominant risk.** Myeloablative busulfan carries infertility, secondary-malignancy, and organ-toxicity risk; the single BEACON death and most grade ≥3 events sit in this category. Non-genotoxic conditioning via epitope editing is in early development (*Nature* 2026;657:262–274, doi:10.1038/s41586-026-10737-8).
- **Follow-up is short.** A 2026 systematic review of autologous gene therapy in SCD (25 reports, 9 programs, 148 infused patients) notes that base-editing and Cas12a evidence rests on shorter follow-up with endpoints not pooled against the pivotal Cas9 cohorts, and that delivery attrition is real (e.g., 35/47 infused for lovo-cel) — *Shaik & Divers, Eur J Haematol.* 2026;117:1168–1180, doi:10.1111/ejh.70260.
- **Genomic surveillance stays mandatory.** Base editors can produce bystander edits within the activity window and RNA off-target effects. Clinical reports to date describe no off-target mutations, but sample sizes and follow-up are small.
- **Access and equity.** Cost, reimbursement, and global scalability remain unresolved; the accompanying *Cell Stem Cell* commentary frames scale, genomic surveillance, burden of cure, and access as the current translational tests (*Cell Stem Cell* 2026;33:1575–1577, doi:10.1016/j.stem.2026.09.003).

---

## Bottom line

Base editing for SCD has moved from concept to clinical result in roughly three years. The BEACON data establish that *HBG*-promoter base editing yields pancellular HbF >60%, HbS <40%, and early freedom from severe VOCs, and the tBE report extends feasibility to SCD and to genotypes beyond East Asia. The open questions have shifted from "does it work" to durability, conditioning toxicity, scalable delivery, and long-term genomic safety.

---

## References

1. Gupta AO, Sharma A, Frangoul H, et al.; BEACON Investigators. Base Editing of *HBG1* and *HBG2* Promoters for Sickle Cell Disease. *N Engl J Med.* 2026;394(18):1824–1835. doi:10.1056/NEJMoa2504835. PMID 41931046.
2. Liu R, Lai Y, Wang L, et al. Clinical base editing for β-hemoglobinopathies across different genetic backgrounds. *Cell Stem Cell.* 2026;33(10):1597–1609.e4. doi:10.1016/j.stem.2026.08.009. PMID 42705233.
3. Mayuranathan T, Newby GA, Feng R, et al. Potent and uniform fetal hemoglobin induction via base editing. *Nat Genet.* 2023;55(7):1210–1220. doi:10.1038/s41588-023-01434-7. PMID 37400614.
4. Kostamo Z, Ortega MA, Xu C, et al. Base editing HbS to HbG-Makassar improves hemoglobin function supporting its use in sickle cell disease. *Nat Commun.* 2025;16:1441. doi:10.1038/s41467-025-56578-3. PMID 39920120.
5. Xu S, Liang D, Wang Q, et al. In vivo genome editing of human haematopoietic stem cells for treatment of blood disorders using mRNA delivery. *Nat Biomed Eng.* 2026;10(3):473–489. doi:10.1038/s41551-025-01480-y. PMID 40796944.
6. Shaik MY, Divers S. Efficacy, Safety, and Treatment-Delivery Feasibility of Autologous Gene Therapy for Sickle Cell Disease: A Systematic Review With Descriptive Synthesis of Clinical Trials. *Eur J Haematol.* 2026;117(5):1168–1180. doi:10.1111/ejh.70260. PMID 42400217.
7. Harwani N, Sharma A. Flipping the fetal switch across β-hemoglobinopathies. *Cell Stem Cell.* 2026;33(10):1575–1577. doi:10.1016/j.stem.2026.09.003. PMID 42822434.
8. Casirati G, Cosentino A, Freschi M, et al. Non-genotoxic transplantation and in vivo selection through epitope editing. *Nature.* 2026;657(8130):262–274. doi:10.1038/s41586-026-10737-8. PMID 42420446.

*Search queries run (PubMed): "CRISPR base editing sickle cell disease"; "base editing HBG1 HBG2 fetal hemoglobin induction clinical trial"; "BEAM-101 base editing sickle cell BEACON trial"; "adenine base editor fetal hemoglobin sickle cell disease hematopoietic stem cells"; "base editing correction sickle mutation HBB Glu6Val Makassar"; "in vivo base editing hemoglobinopathy lipid nanoparticle mRNA delivery"; "ristoglogene autogetemcel risto-cel"; "base editing[tiab] AND (sickle[tiab] OR \"fetal hemoglobin\"[tiab]) AND 2025:2026[dp]".*
