🎲 SYNTHETIC DATASET GENERATOR

A constraint-aware synthetic dataset generator powered by Meta Llama 3.1 (8B Instruct), optimized using 4-bit quantization, and deployed with an interactive Gradio UI on Google Colab (T4 GPU).

This tool allows users to generate structured, row-wise JSON datasets by simply describing columns and constraints in natural language.

✨KEY FEATURES

✅ Strict Row-wise JSON Output
Always returns data as an array of objects (never columnar).

✅ Schema & Constraint Enforcement
Enforces column names, value ranges, formats, and categories.

✅ Logical Attribute Correlation
Ensures realistic relationships (e.g., age aligns with occupation).

✅ Natural Language Dataset Specification
Define datasets using simple text instructions.

✅ 4-bit Quantized Inference (NF4)
Efficient GPU usage with minimal VRAM footprint.

✅ Interactive Gradio Web Interface
Generate, preview, and validate datasets in real time.

✅ Production-Ready Output
Clean JSON suitable for ML pipelines, APIs, and testing.
