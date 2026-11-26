# Perdrix — an open norm for filling in DVI records

*[Version française](README.fr.md)*

**Perdrix** says *how to fill in* the dental part of the disaster victim identification (DVI) forms of Interpol, ante mortem (AM) and post mortem (PM), so that records entered by different experts, in different countries, stay comparable. It does not replace the Interpol forms: it is compatible with them.

> **Status: working draft** (version `0.29.0-draft`). The norm changes from one version to the next and has not yet been reviewed by peers: **use fictitious data only.**

## What is here

| Path | Content |
|---|---|
| `norm/perdrix_norm.json` | **The norm**: a single JSON file (vocabularies, rules, parameters of the AM/PM comparison, labels in English, French and Spanish, correspondences with the fields of the Interpol forms and the PlassData codes). |

This repository holds the norm only. Its structure and the reasons for choosing JSON are presented on the site: <https://perdrix-dvi.org/en/standard.html>. The application that applies it, **Perdrix-DVI** (a prototype that keeps its data in the user's browser), is at <https://perdrix-dvi.org/app/>.

## Licence

The norm and the texts of this repository are published under [CC BY 4.0](LICENSE): use, translate, adapt and redistribute them, **crediting the author and indicating any change**. The file carries the credit to give in `meta.attribution`:

> Perdrix, an open norm for filling in DVI records, by Hadrien Diakonoff, <https://perdrix-dvi.org/> (CC BY 4.0).

## Citing

See `CITATION.cff` (GitHub's "Cite this repository" reads it). In short: Diakonoff H. *Perdrix, an open norm for filling in DVI records*, 2026. <https://perdrix-dvi.org/>

## Contributing

Remarks, errors and proposals are welcome as [issues](https://github.com/Forensic-Odontologist/perdrix/issues). Until peer review and a first stable version, the author decides what enters the norm.

## Disclaimers

Perdrix is compatible with the Interpol DVI forms; it is neither produced nor endorsed by Interpol. The norm is provided without warranty (see the licence). Nothing here is medical, forensic or legal advice, and a comparison of AM and PM records never replaces the expert's conclusion.

Contact: <contact@perdrix-dvi.org>
