+++
date = 2026-09-24
title = "Frequency Assignment in Mobile Networks via the Bandwidth Coloring Problem: A Hybrid Quantum-Classical Approach"

[extra]
authors = "Adriana Archanjo, Luca Borges, Daniel Meneguin, Daniel Lima de Sousa, Matheus do Ó, and Éricles Lima"
where = "Brazilian Congress on Quantum Sciences and Technologies"
#doi =
pdf = "coloring-problem-quantum-classical.pdf"
+++

Dense mobile networks must reuse radio spectrum while limiting interference among nearby transmitters, a requirement formalized by the Frequency Assignment Problem (FAP). We model the FAP as a Graph Coloring Problem (GCP) and as a Bandwidth Coloring Problem (BCP), where edge weights encode minimum spectral separations. We present a hybrid quantum-classical pipeline for the Noisy Intermediate-Scale Quantum (NISQ) regime: Louvain partitioning decomposes the interference graph into qubit-compatible subgraphs; a VQE-inspired routine with a Reconfigurable-Beam-Splitter (RBS) ansatz colors each subgraph while preserving one-hot feasibility; and a greedy classical stage merges the partial colorings and repairs boundary conflicts. The workflow follows the decomposition, local-optimization, and reconciliation structure of hierarchical hybrid coloring methods, but extends the study to weighted BCP constraints. On small synthetic graphs, the pipeline produced valid final colorings and removed all detected conflicts for both formulations.
