# Data in the Wild project
This repo contains the files necessary to perform our preprocessing and produce the figures from our analysis.

## Folder structure
```
├───data
│   ├───images
│   ├───interim
│   │   ├───annotation
│   │   │   ├───annotations
│   │   │   └───spacy
│   │   ├───geographical_tags
│   │   └───scraping
│   ├───processed
│   └───raw
├───ml_models
│   ├───annotation
│   │   └───models
│   │       ├───model-best
│   │       │   ├───ner
│   │       │   ├───tok2vec
│   │       │   └───vocab
│   │       └───model-last
│   │           ├───ner
│   │           ├───tok2vec
│   │           └───vocab
│   └───images
├───notebooks
│   ├───analysis_and_visualization
│   ├───machine_learning
│   ├───preprocessing
│   │   ├───annotation
│   │   └───geographical_tags
│   └───scraping
├───src
└───visualizations
    ├───geographical_tags
    ├───images
    └───ingredients
```