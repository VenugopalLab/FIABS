This project is licensed under the terms of the MIT license.

FIABS stands for Functional Interactomes Across Brain Scale. FIABS are custom network graph models in neuroscience. They are novel ways to create networks of molecular interactions of intercellular signaling resulting in systems-levels functional crosstalk.

FIABS consist of evidence-based connections between nodes. Such evidence from published work offer validated cause-effect interactions between two nodes. Thus, FIABS is a directed graph. 

Nodes depict biomolecular diversity (e.g., amino acids, nucleotides, proteins, reactive oxygen species etc.). Edges represent evidence for causal effects (e.g., Biomolecule A changing the level of expression of another biomolecule B). 
Nodes are annotated with shapes depicting cell type and node colors depicting the function of the biomolecule in the interaction (e.g., TNF-a is a neuroinflammatory cytokine produced and released by Microflia; Glutamate is a neurotransmitter present in and released by neurons)

Edges are annotated by solid lines depicting a positive interaction while dashed line denoting a negative interaction (e.g., TNF-a increasing the Nav1.7 sodium channel subunit expression is a solid edge, while TNF-a decreasing the Cav2.1 calcium channel subunit is a dashed edge.
Edge color denotes different types of functional effects due to A-->B interactions. These could be expression changes, excitability changes, synaptic plasticity, neurotoxicity etc. 
Edge thickness representing a Function Interaction Score (FIS) reflects the strength of empirical evidence including reproducibility and the significance of the molecular interaction to functional crosstalk at the systems level.

FIABS network graphs are created by scientists using curated NCBI PubMed database, assembling persistent identifiers from UniProt, PubChem and ontologies of brain regions from the Allen Brain Atlas.
