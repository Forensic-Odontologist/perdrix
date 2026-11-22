# Perdrix — une norme ouverte pour remplir les fiches DVI

*[English version](README.md)*

**Perdrix** dit *comment remplir* la partie dentaire des formulaires d'identification des victimes de catastrophes (DVI) d'Interpol, ante mortem (AM) et post mortem (PM), pour que des fiches saisies par des experts différents, dans des pays différents, restent comparables. Elle ne remplace pas les formulaires d'Interpol : elle est compatible avec eux.

> **Statut : version de travail** (version `0.27.3-draft`). La norme change d'une version à l'autre et n'a pas encore été relue par des pairs : **n'utiliser que des données fictives.**

## Contenu

| Chemin | Contenu |
|---|---|
| `norm/perdrix_norm.json` | **La norme** : un seul fichier JSON (vocabulaires, règles, paramètres de la comparaison AM/PM, libellés en anglais, français et espagnol, correspondances avec les champs des formulaires d'Interpol et les codes PlassData). |

Ce dépôt ne contient que la norme. Sa structure et les raisons du choix de JSON sont présentées sur le site : <https://perdrix-dvi.org/fr/norme.html>. L'application qui l'applique, **Perdrix-DVI** (un prototype qui garde ses données dans le navigateur de l'utilisateur), est à l'adresse <https://perdrix-dvi.org/app/>.

## Licence

La norme et les textes de ce dépôt sont publiés sous licence [CC BY 4.0](LICENSE) : les utiliser, les traduire, les adapter et les redistribuer, **en citant l'auteur et en indiquant toute modification**. Le fichier porte la mention à donner dans `meta.attribution` :

> Perdrix, an open norm for filling in DVI records, by Hadrien Diakonoff, <https://perdrix-dvi.org/> (CC BY 4.0).

**Le nom.** La licence CC BY 4.0 ne concède pas le nom. « Perdrix » désigne la norme telle que publiée ici : une version modifiée doit le dire et ne doit pas s'appeler Perdrix. Ce qui peut s'appeler « compatible avec Perdrix », et comment, est dans [NAME-POLICY.fr.md](NAME-POLICY.fr.md).

## Citer

Voir `CITATION.cff` (la fonction « Cite this repository » de GitHub le lit). En bref : Diakonoff H. *Perdrix, an open norm for filling in DVI records*, version 0.27.3-draft, 2026. <https://perdrix-dvi.org/>

## Contribuer

Remarques, erreurs et propositions sont les bienvenues sous forme d'[issues](https://github.com/Forensic-Odontologist/perdrix/issues). Jusqu'à la relecture par des pairs et à une première version stable, l'auteur décide de ce qui entre dans la norme.

## Avertissements

Perdrix est compatible avec les formulaires DVI d'Interpol ; elle n'est ni produite ni approuvée par Interpol. La norme est fournie sans garantie (voir la licence). Rien ici ne constitue un avis médical, médico-légal ou juridique, et une comparaison de fiches AM et PM ne remplace jamais la conclusion de l'expert.

Contact : <contact@perdrix-dvi.org>
