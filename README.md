# Premise Selection For Automated Theorem Proving in Metamath

### Abstract

Humans use interactive theorem provers like Metamath to manually prove theorems
in mathematics. The fundamental step to prove any theorem in Metamath, starting
from the goal statement, is to assign a label (premise selection) of an hypothesis,
axiom, or an already proved theorem to the sub-goals at every step of the proof.
In this work, we use neural networks to predict and automate the process of
premise selection to enable automatic proof construction. We do further analysis
to understand the bottlenecks of this approach and suggest methods to overcome
them.

**How to run**:    
1. Dataset generation: Upload dataset-generation.ipynb to any python notebook (eg Colab) and run directly. You can also download the dataset directly from:
https://drive.google.com/file/d/1_0mweAJ-5ElS8Kt20Hb2UVHpRlqroTfr/view?usp=sharing

2. Upload atp-mm.ipynb to any python notebook and run directly.

Optuna version:  
python3 atp-mm-optuna.py
