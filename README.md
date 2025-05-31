# BLIP-2-Fine-Tuning---Image-Captioning


-Developed an image captioning system by fine-tuning a large pre-trained VLM (BLIP-2 OPT 2.7B) on a dataset of 20,000+ images.
-Implemented PEFT using LoRA to adapt the model efficiently, training only a small fraction of parameters.
-Employed QLoRA, leveraging 4-bit quantization to reduce memory footprint (VRAM).
-Developed an inference pipeline to generate captions for unseen test images, including beam search for improved caption quality.
-Successfully generated high-quality image captions, as demonstrated by strong performance on a Fréchet Inception Distance (FID) based semantic similarity metric.

