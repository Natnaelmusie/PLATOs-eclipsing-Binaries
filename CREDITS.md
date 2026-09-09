# Credits and attribution

## Project team

This was a final-year group research project at **Keele University** (module PHY-30006).
The team was:

- **Brittany Phillips**
- **Daniel Maddock**
- **Natnael Musie** (this repository)
- **George Abraham**

The project was supervised by academic staff at Keele University, who provided the
methodology, the JKTEBOP workflow, and guidance on parameter selection.

## Division of work

Each team member independently analysed their own assigned eclipsing binary systems
using a shared methodology and notebook template, then the results were combined into a
single group dataset and colour-magnitude diagram.

**My contribution (Natnael Musie):**
- End-to-end analysis of TIC349059354 and TIC349480507 (TESS + Gaia processing, JKTEBOP
  modelling across four datasets, model overplotting)
- Additional analysis of TIC307084982, including fitting eccentricity terms
- My individual research report

**Teammates' contributions include:**
- The colour-magnitude diagram plotting code and mass interpolation
- Limb-darkening coefficient research (Daniel Maddock)
- The outlier-removal approach adopted across the group
- Analysis of the remaining systems in the sample

The notebook templates were provided/developed collaboratively with supervisor input.

## Software

- **JKTEBOP** v43 — Southworth (2013)
- **Lightkurve** v2.5.0 — Lightkurve Collaboration (2018)
- **Astropy** — The Astropy Collaboration
- NumPy, pandas, Matplotlib

## Data

- **TESS** photometry (SPOC pipeline), via MAST — Ricker et al. (2014)
- **Gaia DR3** epoch photometry and astrometry — Gaia Collaboration (2023)
- **MIST** isochrones — Dotter (2016); Choi et al. (2016); Paxton et al. (2018)
- **Mamajek (2022)** mean dwarf stellar colour/temperature sequence
- Eclipsing binary catalogue — Prša et al. (2022)

## A note on the reports

The individual report in `reports/` is my own work. The group research note is
co-authored; it is included/referenced with my co-authors' contributions credited above.
