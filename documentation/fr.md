<!-- ELUCENIA technical documentation · apgar · fr · no clinical/professional/rights approval -->

# Score d’Apgar

[conditions, sources et autorisations](https://elucenia.org/fr/outils/apgar)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Fréquence cardiaque

`fc`

- `0` — Absent
- `1` — \< 100 bpm
- `2` — ≥ 100 bpm

### Effort respiratoire

`resp`

- `0` — Absent
- `1` — Lent, irrégulier
- `2` — Bon, cri vigoureux

### Tonus musculaire

`tonus`

- `0` — Flasque
- `1` — Une certaine flexion
- `2` — Mouvements actifs

### Réactivité aux stimulations

`reflexo`

- `0` — Aucune réponse
- `1` — Grimace
- `2` — Cri, toux ou éternuement

### Couleur

`cor`

- `0` — Cyanose ou pâleur
- `1` — Corps rose, extrémités cyanosées
- `2` — Entièrement rose

## Édition de la méthode

Apgar 1953 : 5 signes 0–2 ; suivi AAP/ACOG 2015 à 1/5 min, répéter si \<7

## Formule documentée

Cinq signes, 0 à 2 : fréquence cardiaque, effort respiratoire, tonus, réactivité réflexe, couleur. Total 0 à 10 à 1 et 5 minutes ; si à 5 minutes \<7, répéter toutes les 5 jusqu’à 20 minutes.

## Limites et population

Apgar décrit l’état du nouveau-né et la réponse à la réanimation ; il ne définit pas les étapes initiales de la réanimation, ne diagnostique pas l’asphyxie et ne prédit pas à lui seul la mortalité ou l’issue neurologique individuelle. Le score attribué pendant la réanimation n’équivaut pas à celui obtenu en respiration spontanée. La prématurité, les médicaments maternels et la variabilité de l’examen peuvent influencer le résultat.

## Références

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
