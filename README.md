<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 spaCy Project: Span categorization for a resume certification section.

This project uses spaCy span categorizer to categorize certification section entities to 4 classes (CERTIFICATE, ORG, DATE, LOC)

## 📋 project.yml

The [`project.yml`](project.yml) defines the data assets required by the
project, as well as the available commands and workflows. For details, see the
[spaCy projects documentation](https://spacy.io/usage/projects).

### ⏯ Commands

The following commands are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run).
Commands are only re-run if their inputs have changed.

| Command | Description |
| --- | --- |
| `preprocess` | Convert data/corpus to spaCy format |
| `train` | Train spaCy pipline |
| `evaluate` | Evaluate the trained model and export metrics |
| `package` | Package the trained model as a pip package |
| `clean` | Remove intermediate files |


### ⏭ Workflows

The following workflows are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run)
and will run the specified commands in order. Commands are only re-run if their
inputs have changed.

| Workflow | Steps |
| --- | --- |
| `all` | `preprocess` &rarr; `train` &rarr; `evaluate` &rarr; `package` |

<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->