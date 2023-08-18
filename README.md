# Hugging Face CLIP Interrogator

<a href="https://colab.research.google.com/github/RubenGres/huggingface-CLIP-interrogator-colab/blob/main/huggingface_clip_interrogator.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

###

Derived from [pharmapsychotic clip-interrogator](https://github.com/pharmapsychotic/clip-interrogator)'s 
This notebook provides an user-friendly way to label images using OpenAI's CLIP model on an Hugging Face dataset.

### What is CLIP?
CLIP means "Contrastive Language–Image Pre-training." It's a modern model from OpenAI that connects visual data and natural language, making it great for understanding images with text.

### Which CLIP Model to Choose?
Pick the CLIP model based on your "Stable Diffusion" version:

- For **Stable Diffusion version 1.X**: It's recommended to go with the **ViT-L** (Vision Transformer - Large) version of CLIP.
- For **Stable Diffusion version 2.0** and beyond: The **ViT-H** (Vision Transformer - Huge) for best results.
