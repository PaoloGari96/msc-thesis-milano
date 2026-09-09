# General Relativistic MHD Simulations of Binary Neutron Star Mergers

Master's thesis — Corso di Laurea Magistrale in Fisica Teorica, Scuola di Scienze Matematiche, Fisiche e Naturali, Università degli Studi di Milano-Bicocca.

- **Author:** Paolo Garimberti
- **Supervisor:** Prof. Bruno Giacomazzo

## Abstract

Binary neutron star mergers are unique multi-physics laboratories, probing strong-field gravity, relativistic magnetohydrodynamics, supranuclear matter, gamma-ray bursts, heavy-element nucleosynthesis, and multi-messenger cosmology. Their first combined gravitational-wave and electromagnetic detection in August 2017 marked a milestone for multi-messenger astronomy, underscoring the need for accurate computational models that link observations to the underlying physics.

In this work, simulations of binary neutron star mergers are performed using the general relativistic magnetohydrodynamic code **Spritz** and the general relativistic hydrodynamic code **WhiskyTHC**, both within the publicly available **Einstein Toolkit** framework. The first part investigates a fast-inspiral anomaly encountered when evolving systems described by tabulated equations of state with Spritz, testing different initial-data codes (LORENE vs. Kadath), equations of state (BL hot and DD2), grid resolutions, and spacetime formulations (BSSN and CCZ4). The second part presents successful WhiskyTHC evolutions of the same systems, following the merger and post-merger dynamics — including black-hole collapse in the BL hot case and a long-lived remnant in the DD2 case. Gravitational-wave signals and ejecta properties are extracted and analyzed using the post-processing libraries **PostCactus** and **Kuibit**, with implications for kilonova electromagnetic counterparts.

## Content

- [`thesis.pdf`](./thesis.pdf) — full thesis text
