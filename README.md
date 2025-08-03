# A Generalized Framework for the “Core” Thalamocortical Circuit Computation

## Abstract

This thesis explores a biologically inspired computational framework based on a common
excitatory-inhibitory circuit in the superficial layers of the cortex. By varying the strength
of local feedback inhibition, this single circuit gives rise to distinct unsupervised learn-
ing behaviors: strong inhibition leads to clustering and hierarchical clustering, while weak
inhibition produces principal component-like representations. From this principle, we de-
velop three algorithms: Lateral Inhibition Clustering (LI-C), Lateral Inhibition Hierarchical
Clustering (LI-HC), and Antipodal Iterative Mean Estimation (AIME).

LI-C performs clustering without requiring a predefined number of clusters, using a com-
petitive learning rule to extract dominant patterns from data. LI-HC extends this mech-
anism by incorporating biologically plausible masking and recursive inhibition, enabling
multi-level structure discovery. To enhance interpretability, we introduce a suite of cluster
engineering strategies that refine cluster outputs in a data-driven way.

AIME operates under low-inhibition dynamics and serves as an efficient, interpretable alternative to traditional Principal Component Analysis (PCA). It produces diverse, meaning-
ful components that span the principal subspace and scales linearly with input dimension,
making it suitable for high-dimensional settings. Empirical and theoretical results show
that AIME not only recovers principal directions but also offers redundancy and robustness
not available in standard PCA.

Together, these models uncover a surprising computational unification: clustering and
PCA, often viewed as distinct, emerge from the same circuit under different inhibitory
regimes. We explore this relationship both conceptually and mathematically, highlighting
its implications for unsupervised learning and neural computation.
