# Stable Diffusion Webui Mask Clothes
Mask Clothes Extension for Automatic1111's Stable Diffusion Web Ui

Extension for [webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui). Tts creating transparent png masks for all clothes in uploaded image.

Find "Create Mask of Clothes" in the Extras tab after installing the extension.

# Usage:

Create mask 
Upload mask to img2img > inpaint upload > mask
Start Creating new photos

# Models:

1- Rembg: u2net_cloth_seg ([download](https://github.com/danielgatis/rembg/releases/download/v0.0.0/u2net_cloth_seg.onnx), [source](https://github.com/levindabhi/cloth-segmentation)): A pre-trained model for Cloths Parsing from human portrait. Here clothes are parsed into 3 category: Upper body, Lower body and Full body.

2- Opencv2 Dilation: ([source](https://docs.opencv.org/3.4/db/df6/tutorial_erosion_dilatation.html)) You can extend a little pixels created mask.



# Credits:

- rembg library that does all the work: https://github.com/danielgatis/rembg

- automatic1111 rembg extension (i used this) : https://github.com/AUTOMATIC1111/stable-diffusion-webui-rembg
