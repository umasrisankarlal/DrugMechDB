---
title: "Cefamandole - Pneumonia"
sidebar: mydoc_sidebar
permalink: cefamandolepneumonia.html
toc: false 
---

{% include image.html url="images/cefamandolepneumonia.png" file="cefamandolepneumonia.png" alt="cefamandolepneumonia" %}

## Concepts

|------------|------|---------|
| Identifier | Name | Type    |
|------------|------|---------|
| MESH:D002435 | Cefamandole | Drug |
| InterPro:IPR001460 | Penicillin-binding protein, transpeptidase | GeneFamily |
| GO:0018104 | Cross-linking of the peptidoglycan | BiologicalProcess |
| GO:0009273 | Peptidoglycan-based cell wall biogenesis | BiologicalProcess |
| GO:0005618 | Cell wall | CellularComponent |
| NCBITaxon:2 | Bacteria | OrganismTaxon |
| MESH:D011014 | Pneumonia | Disease |
|------------|------|---------|

## Relationships

|---------|-----------|---------|
| Subject | Predicate | Object  |
|---------|-----------|---------|
| Cefamandole | DECREASES ACTIVITY OF | Penicillin-Binding Protein, Transpeptidase |
| Penicillin-Binding Protein, Transpeptidase | POSITIVELY REGULATES | Cross-Linking Of The Peptidoglycan |
| Cross-Linking Of The Peptidoglycan | POSITIVELY REGULATES | Peptidoglycan-Based Cell Wall Biogenesis |
| Peptidoglycan-Based Cell Wall Biogenesis | HAS OUTPUT | Cell Wall |
| Cell Wall | OCCURS IN | Bacteria |
| Bacteria | CAUSES | Pneumonia |
|---------|-----------|---------|

Reference: [https://go.drugbank.com/drugs/DB01326#mechanism-of-action](https://go.drugbank.com/drugs/DB01326#mechanism-of-action){:target="_blank"}