﻿**Hugging Face (BLOOM) - total: 34/48**

- Data sources
   - 4 points: Dataset pipeline is disclosed as a singular dataset derived from ROOTS with all relevant preprocessing, with ROOTS itself being documented extensively (including dataset size and fine-grained sourcing) in the associated paper and datasheet. ROOTS has an extensive data viewer as well, which goes beyond the requirements for improving transparency. 
   - Sources: <https://arxiv.org/pdf/2211.05100.pdf> and <https://arxiv.org/pdf/2303.03915.pdf> and <https://huggingface.co/spaces/bigscience-data/roots-search> 
- Data governance
   - 4 points: The subject of data governance and curation is raised extensively, with concrete measures to reduce bias and other harms. A separate paper on data governance as well.
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> and <https://arxiv.org/pdf/2303.03915.pdf> and <https://arxiv.org/pdf/2206.03216.pdf> 
- Copyrighted data
   - 3 points:  Significant discussion of PII and adjacent data, though specifics on the separation between copyright vs. non-copyright is not perfectly clear.
   - Source: <https://arxiv.org/pdf/2211.05100.pdf>
- Compute (additive)
   - 4 points: The model size, training time, hardware, and FLOPs are disclosed. 
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> 
- Energy (additive)
   - 4 points: The energy usage, emissions, energy sources, and measurement methodology are clear. No extensive discussion is provided of energy usage mitigation, though various decisions are taken to improve efficiency that do contribute to reduced energy use. Separate dedicated paper to energy.
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> and <https://arxiv.org/pdf/2211.02001.pdf> 
- Capabilities and limitations
   - 3 points: Capabilities and limitations are extensively enumerated with several concrete examples, though concreteness on limitations could be improved across paper and model card. 
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> and <https://huggingface.co/bigscience/bloom> 
- Risks and mitigations (additive)
   - 2 points: Explicit discussion of risks and mitigations, though unmitigated risks go undiscussed and unjustified.
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> and <https://huggingface.co/bigscience/bloom> 
- Evaluations (additive)
   - 3 point: Extensive evaluation for accuracy, evaluations for unintentional harm (bias on CrowS-Pairs) and robustness, but not evaluations for malicious (e.g. disinformation) harms.
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> 
- Testing (additive)
   - 2 points: Significant discussion of internal testing or evaluations development internally, but no red teaming or external evaluation documented.
   - Source: <https://arxiv.org/pdf/2211.05100.pdf> and <https://huggingface.co/bigscience/bloom> 
- Machine-generated content
   - 3 points: RAIL license prohibits “To generate or disseminate information or content, in any context (e.g. posts, articles, tweets, chatbots or other kinds of automated bots) without expressly and intelligibly disclaiming that the text is machine generated”. No enforcement mechanism or watermarking however.
   - Source: <https://huggingface.co/spaces/bigscience/license> 
- Member states
   - 0 points: No known country-level restrictions with no clarification of deployment differences across EU member states.
   - Sources: <https://huggingface.co/spaces/bigscience/license> 
- Downstream documentation
   - 4 points: Documentation of model and data in the form of model card + multiple technical papers. Further documentation appears in the RAIL license.
   - Source: <https://huggingface.co/spaces/bigscience/license> 