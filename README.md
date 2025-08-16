# RealAC: A Domain-Agnostic Framework for Realistic and Actionable Counterfactual Explanations
📜 Overview

RealAC is a domain-agnostic framework for generating realistic and actionable counterfactual explanations (CFs) for machine learning models.
Unlike existing methods, RealAC:

Preserves complex inter-feature dependencies without requiring explicit domain knowledge or causal graphs.

Respects user-defined feasibility constraints, enabling “frozen” features that cannot be changed.

Balances realism, actionability, and prediction validity, achieving state-of-the-art results on multiple metrics.

Counterfactual explanations describe minimal changes to input features that flip a model’s prediction. RealAC ensures these changes are plausible and implementable in practice.

🚀 Key Features

Dependency Preservation:
Maintains statistical and structural integrity by minimizing divergence in mutual information between feature pairs in factual and counterfactual data.

Actionability via Binary Masking:
Allows users to mark features as immutable (structural or personal preference) so they remain unchanged during optimization.

Domain-Agnostic:
Works without handcrafted constraints or expert-provided causal diagrams.

Comprehensive Evaluation:
Outperforms state-of-the-art and LLM-based CF generators across metrics such as:

1. Validity
2. Causal Edge Score (CES)
3. Dependency Preservation Score (DPS)
4. IM1 realism metric

📜 Citation

If you use RealAC in your research, please cite:

    @inproceedings{Arefeen2025RealACAD,
      title={RealAC: A Domain-Agnostic Framework for Realistic and Actionable Counterfactual Explanations},
      author={Asiful Arefeen and Shovito Barua Soumma and Hassan Ghasemzadeh},
      year={2025}
    }
