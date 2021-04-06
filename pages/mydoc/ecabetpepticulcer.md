---
title: "ecabet - Peptic ulcer"
sidebar: mydoc_sidebar
permalink: ecabetpepticulcer.html
toc: false 
---

{% include image.html url="images/ecabetpepticulcer.png" file="ecabetpepticulcer.png" alt="ecabetpepticulcer" %}

## Concepts

|------------|------|---------|
| Identifier | Name | Type    |
|------------|------|---------|
| MESH:C061681 | ecabet | Drug |
| CHEBI:16412 | lipopolysaccharide | ChemicalSubstance |
| REACT:R-HSA-166016 | Toll Like Receptor 4 (TLR4) Cascade | Pathway |
| GO:0006954 | inflammatory response | BiologicalProcess |
| GO:0070254 | mucus secretion | BiologicalProcess |
| UBERON:0001276 | epithelium of stomach | GrossAnatomicalStructure |
| InterPro:IPR017950 | Urease active site | GeneFamily |
| GO:0009039 | urease activity | MolecularActivity |
| NCBITaxon:210 | Helicobacter pylori | OrganismTaxon |
| MESH:C047874 | gastric mucus glycoproteins | GeneFamily |
| MESH:D009093 | Mucus | MacromolecularComplex |
| MESH:D005753 | Gastric Mucosa | GrossAnatomicalStructure |
| MESH:D010437 | Peptic ulcer | Disease |
|------------|------|---------|

## Relationships

|---------|-----------|---------|
| Subject | Predicate | Object  |
|---------|-----------|---------|
| Ecabet | MOLECULARLY INTERACTS WITH | Gastric Mucus Glycoproteins |
| Gastric Mucus Glycoproteins | LOCATED IN | Gastric Mucosa |
| Gastric Mucosa | PRODUCES | Mucus |
| Mucus | NEGATIVELY CORRELATED WITH | Peptic Ulcer |
| Ecabet | POSITIVELY CORRELATED WITH | Peptic Ulcer |
| Ecabet | NEGATIVELY CORRELATED WITH | Mucus Secretion |
| Mucus Secretion | NEGATIVELY CORRELATED WITH | Peptic Ulcer |
| Ecabet | MOLECULARLY INTERACTS WITH | Lipopolysaccharide |
| Lipopolysaccharide | POSITIVELY REGULATES | Toll Like Receptor 4 (Tlr4) Cascade |
| Toll Like Receptor 4 (Tlr4) Cascade | POSITIVELY CORRELATED WITH | Inflammatory Response |
| Inflammatory Response | LOCATED IN | Epithelium Of Stomach |
| Epithelium Of Stomach | LOCATION OF | Peptic Ulcer |
| Ecabet | NEGATIVELY REGULATES | Urease Active Site |
| Urease Active Site | POSITIVELY REGULATES | Urease Activity |
| Urease Activity | IN TAXON | Helicobacter Pylori |
| Helicobacter Pylori | CAUSES | Peptic Ulcer |
|---------|-----------|---------|

Reference: [https://go.drugbank.com/drugs/DB02701#mechanism-of-action](https://go.drugbank.com/drugs/DB02701#mechanism-of-action){:target="_blank"}