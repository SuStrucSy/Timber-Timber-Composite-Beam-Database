# Timber–Timber Composite Beam Database

A harmonized experimental database of timber–timber composite (TTC) beams, developed to support comparative assessment, analytical-model evaluation, numerical modelling, and future experimental design.

**Current release:** Version 1.0.0  
**Last updated:** 2026-07-24

## Overview

This repository contains experimental and analytical data for 79 full-scale TTC beam specimens reported in 16 studies published between 2010 and 2026.

The database combines specimen-level information concerning:

- beam configuration and loading arrangement;
- CLT flange layup, dimensions, and elastic properties;
- rib product, grade or species, geometry, and modulus of elasticity;
- flange-to-rib connection type, spacing, angle, and slip modulus;
- experimentally measured or derived flexural stiffness;
- back-calculated effective flange width;
- Eurocode 5 effective flange width;
- Gamma-method flexural-stiffness predictions; and
- applicability of the Eurocode 5 effective-flange-width provisions.

The compiled population includes 60 single-rib beams, 17 double-rib beams, and two floor-system specimens. Fifty-seven specimens use discrete mechanical connections and 22 use glued connections.

## Purpose

The database was developed to:

1. characterize the range of TTC beam configurations investigated experimentally;
2. identify underrepresented combinations of geometry, material properties, and connection stiffness;
3. evaluate Eurocode 5 effective-flange-width predictions;
4. assess Gamma-method predictions of short-term elastic flexural stiffness; and
5. provide traceable inputs for analytical and numerical investigations.

## Repository Contents

- `TTC_Beam_Database_v1.0.0.xlsx` – the specimen-level database and supporting analytical calculations.

## Data Classification

Where applicable, values in the workbook may be identified as:

- **Reported** – stated directly in the source publication.
- **Digitized** – extracted from a published graph or load–displacement curve.
- **Derived** – calculated from reported experimental information.
- **Code-derived** – calculated using a standard or design-code provision.
- **Assumed** – adopted where the original study did not report the required input.
- **Back-calculated** – obtained by solving the analytical model against measured flexural stiffness.

## Scope and Limitations

The database primarily supports assessment of short-term elastic flexural response. It does not establish characteristic material properties or validate the included analytical methods for ultimate capacity, vibration, creep, environmental cycling, or long-term performance.

The compiled specimens do not uniformly satisfy all applicability limits of the Eurocode 5 effective-flange-width formulation. EC5-compliant and noncompliant specimens are therefore identified separately. Results obtained from the complete database should not be interpreted as validation of EC5 outside its stated applicability domain.

The database is provided for research and educational use and does not replace project-specific engineering analysis, applicable design standards, or professional judgment. Users should verify critical values against the original publications.

## License

The database and accompanying documentation are licensed under the [Creative Commons Attribution 4.0 International License](LICENSE).
