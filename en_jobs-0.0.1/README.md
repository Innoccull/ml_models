Named entity recognition and linking to extract skills from job advertisements

| Feature | Description |
| --- | --- |
| **Name** | `en_jobs` |
| **Version** | `0.0.1` |
| **spaCy** | `>=3.4.3,<3.5.0` |
| **Default Pipeline** | `sentencizer`, `tok2vec`, `ner`, `entity_linker` |
| **Components** | `sentencizer`, `tok2vec`, `ner`, `entity_linker` |
| **Vectors** | 0 keys, 0 unique vectors (0 dimensions) |
| **Sources** | n/a |
| **License** | n/a |
| **Author** | [Chris Rodgers]() |

### Label Scheme

<details>

<summary>View label scheme (1 labels for 1 components)</summary>

| Component | Labels |
| --- | --- |
| **`ner`** | `Skill` |

</details>

### Accuracy

| Type | Score |
| --- | --- |
| `ENTS_F` | 70.47 |
| `ENTS_P` | 76.40 |
| `ENTS_R` | 65.38 |
| `TOK2VEC_LOSS` | 23394.31 |
| `NER_LOSS` | 38198.04 |