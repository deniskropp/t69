# Initial Task-Agnostic Steps (TAS) for Semantic Drift Analysis

This document outlines the foundational Task-Agnostic Steps (TAS) identified for the self-updating system that tracks and analyzes semantic drift between TAS using embeddings.

## Core TAS Definitions:

1.  **Define System Objective**: Articulate the primary goal and scope of the system. (e.g., 'Create a self-updating system that tracks and analyzes semantic drift between Task-Agnostic Steps (TAS) using embeddings.')
2.  **Identify and Extract TAS**: Recognize and isolate distinct, fundamental actions from a given workflow or goal description, independent of specific roles or contexts.
3.  **Record TAS Details**: Store the extracted TAS text, associated role context (if applicable), and a timestamp for each identified step.
4.  **Generate Embeddings**: Convert the recorded TAS text into numerical vector representations using a specified embedding model (e.g., 'text-embedding-3-large').
5.  **Establish Baseline Similarity**: Calculate and record the semantic similarity between the initial set of TAS embeddings to create a reference point.
6.  **Monitor for Semantic Drift**: Periodically compare new TAS embeddings against the established baseline to detect significant changes in meaning or concept.
7.  **Analyze Drift Patterns**: Investigate the nature and extent of detected semantic drift, identifying potential causes (e.g., conceptual evolution, linguistic shifts).
8.  **Update System State**: Incorporate new TAS, their embeddings, and analysis results into the system's ongoing record.
9.  **Refine Extraction Criteria**: Adjust the process or guidelines for identifying and extracting TAS based on analysis and observed drift.
10. **Refine Embedding Model/Parameters**: Evaluate and potentially update the embedding model or its configuration for improved drift detection.
11. **Report Drift Analysis**: Summarize findings on semantic drift, including trends, anomalies, and implications for the workflows being tracked.