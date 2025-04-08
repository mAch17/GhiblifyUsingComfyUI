# GhiblifyUsingComfyUI
Use ComfyUI to do a ghibli transform on a consumer GPU { Tested on Nvidia 3050 }

Uses open models to create a Ghibli transform like what is trending these days. We use Comfy UI for this.

The following is how you use this

- Install Comfy UI from [here](https://github.com/comfyanonymous/ComfyUI/releases)
- Install Comfy UI manager from [here](https://github.com/Comfy-Org/ComfyUI-Manager)
- Use manager to install custom node comfyui-nikosis-preprocessors
- Download the Realistic Vision model {version of SD 1.5} from [here](https://civitai.com/models/4201?modelVersionId=130072) and place it on Unets directory in comfyuiinstallationdirectory/ComfyUI/models/unets/ 
- Download the vae model from [here](https://civitai.com/models/276082/vae-ft-mse-840000-ema-pruned-or-840000-or-840k-sd15-vae) and place it in comfyuiinstallationdirectory/ComfyUI/models/vae 
- Download the anime and ghibli loras from [here](https://civitai.com/models/617225?modelVersionId=689993) and [here](https://civitai.com/models/6526/studio-ghibli-style-lora) respectively and place them in comfyuiinstallationdirectory/ComfyUI/models/loras 
- Download the canny COntrolnet model from [here](https://huggingface.co/lllyasviel/control_v11p_sd15_canny) and place it in comfyuiinstallationdirectory/ComfyUI/models/controlnet 
- download the json config from this repo and load it using comfyui load {workflow} option
- Set input image and predd queue prompt for comfyui to run and create ghiblified images
- This is a light setup and doesn't block my laptop with a 3050 GPU

- 