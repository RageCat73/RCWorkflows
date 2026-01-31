I'm creating this folder to help organize this repo. I'll place new workflows here from now on. This weekend I'll add a version 3 of the LTX-2 workflow where you can add your own audio and image for lipsyncing.


Version 3 Notes 31Jan2026:

replaced the Tiled VAE decode with the 🅛🅣🅧 LTXV Tiled VAE Decode

Replaced the Static Camera Lora with the LTX-2-Image2Vid-Adapter.safetensors Lora
Model card:
https://huggingface.co/MachineDelusions/LTX-2_Image2Video_Adapter_LoRa
https://huggingface.co/MachineDelusions/LTX-2_Image2Video_Adapter_LoRa/resolve/main/LTX-2-Image2Vid-Adapter.safetensors?download=true

Rearranged the Model Loading and Loras and put them at the top. Color Coded all areas where you have to download or input something as a RED group.

Added an API key version of the workflow

Models and Lora List

*checkpoints**

- [ltx-2-19b-dev-fp8.safetensors]

https://huggingface.co/Lightricks/LTX-2/resolve/main/ltx-2-19b-dev-fp8.safetensors

**text_encoders - Quantized Gemma or use whatever smaller or larger Gemma you prefer and that will work with this workflow

- [gemma_3_12B_it_fp8_e4m3fn.safetensors]

https://huggingface.co/GitMylo/LTX-2-comfy_gemma_fp8_e4m3fn/resolve/main/gemma_3_12B_it_fp8_e4m3fn.safetensors?download=true


**latent_upscale_models***

- [ltx-2-spatial-upscaler-x2-1.0.safetensors]

https://huggingface.co/Lightricks/LTX-2/resolve/main/ltx-2-spatial-upscaler-x2-1.0.safetensors

**Mel-Band RoFormer Model - For Audio***

- [MelBandRoformer_fp32.safetensors]

https://huggingface.co/Kijai/MelBandRoFormer_comfy/resolve/main/MelBandRoformer_fp32.safetensors?download=true




**Important loras**

LTX-2-Image2Vid-Adapter.safetensors (Read the model card here)

https://huggingface.co/MachineDelusions/LTX-2_Image2Video_Adapter_LoRa/resolve/main/LTX-2-Image2Vid-Adapter.safetensors?download=true

- [LTX-2-19b-LoRA-Camera-Control-Static]

https://huggingface.co/Lightricks/LTX-2-19b-LoRA-Camera-Control-Static/resolve/main/ltx-2-19b-lora-camera-control-static.safetensors?download=true

- [ltx-2-19b-distilled-lora-384.safetensors]

https://huggingface.co/Lightricks/LTX-2/resolve/main/ltx-2-19b-distilled-lora-384.safetensors?download=true



