# Changelog

The version next to the title is raised with every change of what SUMOscape can do: the
minor number for new features, the patch number for smaller changes and fixes. The entries
say what changed for the person using the viewer. This file is the only place the history is
written; the Changelog page of the in-page help renders it.

## 0.3.1 — 2026-11-09
- **SUMOscape is online.** The viewer is published at https://atreyapaturi.github.io/sumoscape-viewer/ —
  anyone with the link can open it; nothing needs to be installed.
- SUMOscape is now open source under the MIT licence (© Pichler Group, ETH Zurich); the data keep
  their CC BY 4.0 attribution.

## 0.3.0 — 2026-11-06
- **Figure fonts.** *Aa Fonts*, next to the download buttons, sets the font of the figures and,
  separately for the site labels, the axes and the chart labels (condition, track and domain
  names, quadrants, headers), the size, bold and italic. *Black text* turns grey labels black for
  print; presets for a journal (Arial 7 pt), a presentation and a poster. The site map, landscape
  and heatmap change as you go, the SVG and PNG downloads carry the same fonts, and margins and
  label rows grow with the text so that larger labels do not overlap.
- The residue caption under each site map now reads *Residue position*; the mouse hints moved to
  the help.

## 0.2.0 — 2026-11-06
- **Domains on the structure.** *Colour protein by* in the Structure view paints the UniProt domains
  or the Pfam domains on the AlphaFold model. Every domain that contains a SUMO site gets its own
  colour and a label with its number of sites; domains without sites are pale grey. A legend lists
  the domains with sites (range, sites, how many with q < 0.05) and those without; a click zooms to
  a domain. The confidence (pLDDT) colouring moved into the same menu.

## 0.1.0 — 2026-11-06
First release of SUMOscape, the successor of the SUMO Site Map app, as a viewer for any protein.

- **Any protein, any number of proteins.** Add proteins by gene or UniProt accession, paste a
  list, or browse every protein of the dataset and add a selection or all shown (up to 60 at a
  time). Proteins that are not in the dataset are looked up in UniProt and drawn with their
  domains and lysines.
- **One site map per condition.** Control, MG132 and heat shock each get their own lollipop
  panel on a shared Z-score scale, instead of one ratio against control. For the mouse dataset
  there is one panel per organ. Every site can be labelled (auto, all, significant, none).
- **Every domain, labelled.** All UniProt domains, repeats, zinc fingers, DNA-binding regions,
  coiled coils, regions, motifs, compositional bias, topology, signal and transit peptides,
  active and binding sites and lysine modifications (SUMO and ubiquitin cross-links, acetyl,
  methyl), plus the Pfam domains from InterPro. Isoforms now show the annotation too, mapped
  from the canonical entry by sequence. A lysine track marks every lysine and the ψKxE, KxE and
  inverted motifs.
- **Z-score landscape.** Any two conditions as axes (MG132 against heat shock by default), all
  sites of the dataset in grey, the proteins shown in colour and labelled, iso-control lines,
  quadrant names; click a grey point to add its protein.
- **Heatmap** of the sites of the proteins shown across conditions.
- **Structure.** The AlphaFold DB model of the active protein with the sites, coloured by the
  Z-score of a condition or by motif, UniProt knowledge or domain context; confidence colouring.
- **SUMO-conjugate modelling input.** For each site, a Boltz-2 or AlphaFold 3 input file with
  SUMO2 bonded to the lysine — the first step towards comparing modified and unmodified
  structures.
- Colourings by condition and significance, Z-score, motif, cell lines, UniProt knowledge and
  domain context; legend entries switch sites off and on.
- Site table with sorting and filters, site details with sequence window and annotation.
- Your own table (CSV/TSV) as a further dataset, read in the browser only.
- SVG, PNG and CSV export; links that reproduce the view; in-page help with search and this
  changelog; an Overview window with counts.
