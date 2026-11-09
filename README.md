# SUMOscape

**Open the viewer:** https://atreyapaturi.github.io/sumoscape-viewer/

A browser viewer for site-resolved SUMO2/3 proteomics. For any protein (and any number of
proteins) it draws one lollipop site map per condition — control, MG132 and heat shock in
human cells, or eight mouse organs — above every annotated UniProt feature and Pfam domain,
places the sites in the Z-score landscape of all sites, compares them in a heatmap and shows
them on the AlphaFold structure. Figures download as SVG or PNG with adjustable fonts; links
reproduce the view; the in-page help explains every control.

Everything runs in your browser. Proteins, structures and any table you load stay on your
computer.

**Author:** Atreya Paturi · **© 2026 Pichler Group, ETH Zurich** · MIT licence ([LICENSE](LICENSE))

## Data

- **SUMO2/3 sites:** Hendriks IA, Lyon D, Su D, Skotte NH, Daniel JA, Jensen LJ, Nielsen ML.
  *Site-specific characterization of endogenous SUMOylation across species and organs.*
  Nat Commun 9:2456 (2018), [doi:10.1038/s41467-018-04957-4](https://doi.org/10.1038/s41467-018-04957-4),
  Supplementary Data 1 and 5 (CC BY 4.0).
- **Annotation:** UniProtKB (CC BY 4.0) and Pfam via InterPro (CC0), snapshot recorded in `data/manifest.json`.
- **Structures:** AlphaFold DB (CC BY 4.0), fetched by your browser.

If you use SUMOscape, please cite the data source above and name the SUMOscape version shown at
the top right of the page (see also [CITATION.cff](CITATION.cff)).

This repository holds the published site only and is updated automatically from the development
repository; please do not open pull requests here.
