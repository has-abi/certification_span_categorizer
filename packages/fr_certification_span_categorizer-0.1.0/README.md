# 🪐 spaCy Project: Span categorization for a resume certification section.

This project uses spaCy span categorizer to categorize certification section entities to 4 classes (CERTIFICATE, ORG, DATE, LOC)

### Package description

| Feature | Description |
| --- | --- |
| **Name** | `fr_certification_span_categorizer` |
| **Version** | `0.1.0` |
| **spaCy** | `>=3.4.4,<3.5.0` |
| **Default Pipeline** | `tok2vec`, `spancat` |
| **Components** | `tok2vec`, `spancat` |
| **Vectors** | 0 keys, 0 unique vectors (0 dimensions) |
| **License** | MIT |
| **Author** | Hassane Abida |

### Label Scheme

<details>

<summary>View label scheme (4 labels for 1 components)</summary>

| Component | Labels |
| --- | --- |
| **`spancat`** | `DATE`, `CERTIFICATE`, `ORG`, `LOC` |

</details>

### Accuracy

| Type | Score |
| --- | --- |
| `SPANS_SC_F` | 79.09 |
| `SPANS_SC_P` | 91.73 |
| `SPANS_SC_R` | 69.51 |
| `TOK2VEC_LOSS` | 124.96 |
| `SPANCAT_LOSS` | 71919.33 |