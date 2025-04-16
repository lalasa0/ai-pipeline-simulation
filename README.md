# AI Assignment 

This repository contains a simulation of an AI pipeline that transforms a user prompt into a 3D model using mock AI components. The assignment demonstrates the ability to design and structure an end-to-end AI app flow, with simulated modules representing LLMs, text-to-image generation, and image-to-3D conversion.

## Overview

The notebook walks through a 3-stage simulated AI process:

1. **Prompt Expansion (LLM Simulation)**  
   Takes a simple user prompt and expands it into a more detailed and creative version.

2. **Text-to-Image Generation (Simulated)**  
   Uses the expanded prompt to generate a placeholder image (as a stand-in for real T2I models like Stable Diffusion).

3. **Image-to-3D Model Generation (Simulated)**  
   Converts the generated image into a mock 3D `.obj` model.

## Files Included

- `ai_assignment_notebook.ipynb` – Main notebook with all logic and output
- `mock_image_*.png` – Generated placeholder image
- `3d_model_*.obj` – Simulated 3D model filename

## Requirements

Python 3.x, Pillow, IPython

Install using:

```
pip install pillow ipython

```
