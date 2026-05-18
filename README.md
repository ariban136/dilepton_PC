# Dilepton Production as a Probe of Pion Condensation in Hot and Dense QCD Matter

The data files related to the work:

**Aritra Bandyopadhyay, Chowdhury Aminul Islam, Krzysztof Redlich, and Chihiro Sasaki**,
*"Dilepton Production as a Probe of Pion Condensation in Hot and Dense QCD Matter"*
arXiv:2604.21633 [hep-ph] (2026)
https://arxiv.org/abs/2604.21633

are organized as follows. Each figure has a corresponding zip file (fig2.zip, fig3.zip, ..., fig7and8.zip) containing all the relevant datafiles. The naming convention and column descriptions for each figure are detailed below.

---

## Data Usage

The data provided in this repository correspond to numerical results obtained within the two-flavor Nambu–Jona-Lasinio (NJL) model at finite temperature, baryon chemical potential (μB), and isospin chemical potential (μI), including an isoscalar-vector interaction channel (GV). The dilepton production rate (DPR) is computed via RPA resummation of the vector current correlator. The parameter set used is m = 4.76 MeV, Λ = 659 MeV, GS = 4.78 GeV⁻², yielding a vacuum constituent quark mass M0 ≃ 303.5 MeV.

The three values of the isoscalar-vector coupling considered are:
- GV = 0 → labeled **Gv0** in filenames
- GV = 0.5 GS → labeled **Gv5** in filenames
- GV = GS → labeled **Gv1** in filenames

Readers are encouraged to cite the paper if this data is used in their work.

---

###########################
## Fig. 2 — fig2.zip
###########################

**Description:** The effective quark mass M as a function of temperature T (upper-left, upper-right, and lower-left panels) and baryon chemical potential μB (lower-right panel) within the SU(2) NJL model at finite isospin asymmetry, for three values of the isoscalar-vector coupling GV = 0, 0.5 GS, and GS.

**Columns:** T [GeV], M [GeV] (upper three panels) | μB [GeV], M [GeV] (lower-right panel)

**Files (upper-left panel, GV = 0, M vs T):**
- MGv0muB0muI0.csv → μB = 0, μI = 0
- MGv0muB0muI25.csv → μB = 0, μI = 0.25 GeV
- MGv0muB5muI0.csv → μB = 0.5 GeV, μI = 0
- MGv0muB5muI25.csv → μB = 0.5 GeV, μI = 0.25 GeV
- MGv0muB7muI0.csv → μB = 0.7 GeV, μI = 0
- MGv0muB7muI25.csv → μB = 0.7 GeV, μI = 0.25 GeV

**Files (upper-right panel, GV = 0.5 GS, M vs T):**
- MGv5muB0muI0.csv → μB = 0, μI = 0
- MGv5muB0muI25.csv → μB = 0, μI = 0.25 GeV
- MGv5muB5muI0.csv → μB = 0.5 GeV, μI = 0
- MGv5muB5muI25.csv → μB = 0.5 GeV, μI = 0.25 GeV
- MGv5muB7muI0.csv → μB = 0.7 GeV, μI = 0
- MGv5muB7muI25.csv → μB = 0.7 GeV, μI = 0.25 GeV

**Files (lower-left panel, GV = GS, M vs T):**
- MGv1muB0muI0.csv → μB = 0, μI = 0
- MGv1muB0muI25.csv → μB = 0, μI = 0.25 GeV
- MGv1muB5muI0.csv → μB = 0.5 GeV, μI = 0
- MGv1muB5muI25.csv → μB = 0.5 GeV, μI = 0.25 GeV
- MGv1muB7muI0.csv → μB = 0.7 GeV, μI = 0
- MGv1muB7muI25.csv → μB = 0.7 GeV, μI = 0.25 GeV

**Files (lower-right panel, M vs μB, T = 0.1 GeV):**
- MGv0T01muI0.csv → GV = 0, μI = 0
- MGv0T01muI25.csv → GV = 0, μI = 0.25 GeV
- MGv5T01muI0.csv → GV = 0.5 GS, μI = 0
- MGv5T01muI25.csv → GV = 0.5 GS, μI = 0.25 GeV
- MGv1T01muI0.csv → GV = GS, μI = 0
- MGv1T01muI25.csv → GV = GS, μI = 0.25 GeV

---

###########################
## Fig. 3 — fig3.zip
###########################

**Description:** The pion condensate Δ as a function of temperature T (upper-left, upper-right, and lower-left panels) and isospin chemical potential μI/mπ (lower-right panel) within the SU(2) NJL model, for GV = 0, 0.5 GS, and GS. All T-dependent panels are at fixed μI = 0.25 GeV; the lower-right panel is at fixed T = 0.1 GeV.

**Columns:** T [GeV], Δ [GeV] (upper three panels) | μI/mπ, Δ [GeV] (lower-right panel)

**Files (upper-left panel, GV = 0, Δ vs T):**
- DeltaGv0muB0.csv → μB = 0
- DeltaGv0muB5.csv → μB = 0.5 GeV
- DeltaGv0muB7.csv → μB = 0.7 GeV

**Files (upper-right panel, GV = 0.5 GS, Δ vs T):**
- DeltaGv5muB0.csv → μB = 0
- DeltaGv5muB5.csv → μB = 0.5 GeV
- DeltaGv5muB7.csv → μB = 0.7 GeV

**Files (lower-left panel, GV = GS, Δ vs T):**
- DeltaGv1muB0.csv → μB = 0
- DeltaGv1muB5.csv → μB = 0.5 GeV
- DeltaGv1muB7.csv → μB = 0.7 GeV

**Files (lower-right panel, Δ vs μI/mπ, T = 0.1 GeV):**
- DeltaGv0T01muB5.csv → GV = 0, μB = 0.5 GeV
- DeltaGv0T01muB7.csv → GV = 0, μB = 0.7 GeV
- DeltaGv5T01muB5.csv → GV = 0.5 GS, μB = 0.5 GeV
- DeltaGv5T01muB7.csv → GV = 0.5 GS, μB = 0.7 GeV
- DeltaGv1T01muB5.csv → GV = GS, μB = 0.5 GeV
- DeltaGv1T01muB7.csv → GV = GS, μB = 0.7 GeV

---

###########################
## Fig. 4 — fig4.zip
###########################

**Description:** The vector condensate ΣV as a function of temperature T (left and middle panels) and baryon chemical potential μB (right panel) within the SU(2) NJL model. Only GV = 0.5 GS and GV = GS are considered since GV = 0 yields a vanishing vector condensate.

**Columns:** T [GeV], ΣV [GeV] (left and middle panels) | μB [GeV], ΣV [GeV] (right panel)

**Files (left panel, ΣV vs T, μI = 0):**
- SigmaVGv5muB5muI0.csv → GV = 0.5 GS, μB = 0.5 GeV
- SigmaVGv5muB7muI0.csv → GV = 0.5 GS, μB = 0.7 GeV
- SigmaVGv1muB5muI0.csv → GV = GS, μB = 0.5 GeV
- SigmaVGv1muB7muI0.csv → GV = GS, μB = 0.7 GeV

**Files (middle panel, ΣV vs T, μI = 0.25 GeV):**
- SigmaVGv5muB5muI25.csv → GV = 0.5 GS, μB = 0.5 GeV
- SigmaVGv5muB7muI25.csv → GV = 0.5 GS, μB = 0.7 GeV
- SigmaVGv1muB5muI25.csv → GV = GS, μB = 0.5 GeV
- SigmaVGv1muB7muI25.csv → GV = GS, μB = 0.7 GeV

**Files (right panel, ΣV vs μB, T = 0.1 GeV):**
- SigmaVGv5T01muI0.csv → GV = 0.5 GS, μI = 0
- SigmaVGv5T01muI25.csv → GV = 0.5 GS, μI = 0.25 GeV
- SigmaVGv1T01muI0.csv → GV = GS, μI = 0
- SigmaVGv1T01muI25.csv → GV = GS, μI = 0.25 GeV

---

###########################
## Fig. 5 — fig5.zip
###########################

**Description:** The T–μI phase diagram for three values of the isoscalar-vector coupling: GV = 0 (left), GV = 0.5 GS (middle), and GV = GS (right). Each file contains either the chiral crossover boundary (suffix Ch) or the pion condensation phase boundary (suffix Pc) for a given μB and GV.

**Columns:** μI [GeV], T [GeV]

**Files (left panel, GV = 0):**
- PhDgGv0muB0Ch.csv → chiral crossover, μB = 0
- PhDgGv0muB0Pc.csv → pion condensation boundary, μB = 0
- PhDgGv0muB5Ch.csv → chiral crossover, μB = 0.5 GeV
- PhDgGv0muB5Pc.csv → pion condensation boundary, μB = 0.5 GeV
- PhDgGv0muB7Ch.csv → chiral crossover, μB = 0.7 GeV
- PhDgGv0muB7Pc.csv → pion condensation boundary, μB = 0.7 GeV

**Files (middle panel, GV = 0.5 GS):**
- PhDgGv5muB0Ch.csv → chiral crossover, μB = 0
- PhDgGv5muB0Pc.csv → pion condensation boundary, μB = 0
- PhDgGv5muB5Ch.csv → chiral crossover, μB = 0.5 GeV
- PhDgGv5muB5Pc.csv → pion condensation boundary, μB = 0.5 GeV
- PhDgGv5muB7Ch.csv → chiral crossover, μB = 0.7 GeV
- PhDgGv5muB7Pc.csv → pion condensation boundary, μB = 0.7 GeV

**Files (right panel, GV = GS):**
- PhDgGv1muB0Ch.csv → chiral crossover, μB = 0
- PhDgGv1muB0Pc.csv → pion condensation boundary, μB = 0
- PhDgGv1muB5Ch.csv → chiral crossover, μB = 0.5 GeV
- PhDgGv1muB5Pc.csv → pion condensation boundary, μB = 0.5 GeV
- PhDgGv1muB7Ch.csv → chiral crossover, μB = 0.7 GeV
- PhDgGv1muB7Pc.csv → pion condensation boundary, μB = 0.7 GeV

---

###########################
## Fig. 6 — fig6.zip
###########################

**Description:** DPR as a function of the invariant mass Q at fixed T = 0.1 GeV, μB = 0, and GV = 0, for three values of the dilepton three-momentum q = 0, 0.2 GeV, and 0.6 GeV, and two values of the isospin chemical potential μI = 0 (uncondensed) and μI = 0.25 GeV (pion-condensed).

**Columns:** Q [GeV], DPR

**Files:**
- DPRGv0muB0muI0q0.csv → q = 0, μI = 0
- DPRGv0muB0muI25q0.csv → q = 0, μI = 0.25 GeV
- DPRGv0muB0muI0q2.csv → q = 0.2 GeV, μI = 0
- DPRGv0muB0muI25q2.csv → q = 0.2 GeV, μI = 0.25 GeV
- DPRGv0muB0muI0q6.csv → q = 0.6 GeV, μI = 0
- DPRGv0muB0muI25q6.csv → q = 0.6 GeV, μI = 0.25 GeV

---

###########################
## Figs. 7 & 8 — fig7and8.zip
###########################

**Description:** DPR as a function of the invariant mass Q at fixed T = 0.1 GeV and q = 0. Fig. 7 organizes panels by GV (left: GV = 0, middle: GV = 0.5 GS, right: GV = GS) while Fig. 8 organizes the same data by μB (left: μB = 0, middle: μB = 0.5 GeV, right: μB = 0.7 GeV). Both figures share the same datasets.

**Columns:** Q [GeV], DPR

**Files:**
- DPRGv0muB0muI0.csv → GV = 0, μB = 0, μI = 0
- DPRGv0muB0muI25.csv → GV = 0, μB = 0, μI = 0.25 GeV
- DPRGv0muB5muI0.csv → GV = 0, μB = 0.5 GeV, μI = 0
- DPRGv0muB5muI25.csv → GV = 0, μB = 0.5 GeV, μI = 0.25 GeV
- DPRGv0muB7muI0.csv → GV = 0, μB = 0.7 GeV, μI = 0
- DPRGv0muB7muI25.csv → GV = 0, μB = 0.7 GeV, μI = 0.25 GeV
- DPRGv5muB0muI0.csv → GV = 0.5 GS, μB = 0, μI = 0
- DPRGv5muB0muI25.csv → GV = 0.5 GS, μB = 0, μI = 0.25 GeV
- DPRGv5muB5muI0.csv → GV = 0.5 GS, μB = 0.5 GeV, μI = 0
- DPRGv5muB5muI25.csv → GV = 0.5 GS, μB = 0.5 GeV, μI = 0.25 GeV
- DPRGv5muB7muI0.csv → GV = 0.5 GS, μB = 0.7 GeV, μI = 0
- DPRGv5muB7muI25.csv → GV = 0.5 GS, μB = 0.7 GeV, μI = 0.25 GeV
- DPRGv1muB0muI0.csv → GV = GS, μB = 0, μI = 0
- DPRGv1muB0muI25.csv → GV = GS, μB = 0, μI = 0.25 GeV
- DPRGv1muB5muI0.csv → GV = GS, μB = 0.5 GeV, μI = 0
- DPRGv1muB5muI25.csv → GV = GS, μB = 0.5 GeV, μI = 0.25 GeV
- DPRGv1muB7muI0.csv → GV = GS, μB = 0.7 GeV, μI = 0
- DPRGv1muB7muI25.csv → GV = GS, μB = 0.7 GeV, μI = 0.25 GeV

---

## Contact

Aritra Bandyopadhyay
aritrabanerjee.444@gmail.com

## License

This dataset is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)
https://creativecommons.org/licenses/by/4.0/
