README

This dataset is based on the MultiCaRe Dataset (1). The citation information from the case reports that were used to create this dataset can be found in the file case_report_citations.json.

Dataset Information:
- Name: tuberculosis_dataset
- Type: multimodal
- Date: 2024-01-30 22:15
- Filters: [{'field': 'case_strings', 'string_list': ['tuberculosis', 'tb'], 'operator': 'any'}, {'field': 'caption', 'string_list': ['ct', 'lung', 'chest'], 'operator': 'any'}, {'field': 'normalized_extractions', 'string_list': ['ct', 'lung']}]

1. Nievas Offidani, M., & Delrieux, C. (2023). The MultiCaRe Dataset: A Multimodal Case Report Dataset with Clinical Cases, Labeled Images and Captions from Open Access PMC Articles (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.10079370
