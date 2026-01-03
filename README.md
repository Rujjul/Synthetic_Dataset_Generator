#🎲 Synthetic Dataset Generator

A constraint-aware synthetic dataset generator powered by Meta Llama 3.1 (8B Instruct), optimized using 4-bit quantization, and deployed with an interactive Gradio UI on Google Colab (T4 GPU).

This tool allows users to generate structured, row-wise JSON datasets by simply describing columns and constraints in natural language.

#✨ Features

✅ Generates row-oriented JSON (production-ready)

✅ Enforces strict schema adherence

✅ Supports custom constraints (ranges, formats, categories)

✅ Logical correlation between attributes (e.g., age ↔ occupation)

✅ No columnar JSON output (explicitly prevented)

✅ Lightweight inference via 4-bit NF4 quantization

✅ Interactive Gradio-based UI
