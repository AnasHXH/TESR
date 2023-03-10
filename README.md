# Block Diagram
<img src="https://github.com/AnasHXH/TESR-Two-stage-approach-for-Enhancement-and-Super-Resolution-of-Remote-Sensing-Images/blob/main/fig_1.png" width="600" height="400"/>

# TESR-Two-stage-approach-for-Enhancement-and-Super-Resolution-of-Remote-Sensing-Images
we design a new architecture called TESR (Two-stage approach for Enhancement and Super Resolution) leveraging the power of Vision Transformers (ViT) and Diffusion Model (DM) to increase the resolution of RS images artificially. The first stage is Vision Transformer (ViT) based model, which serves for resolution increase. The second stage is an iterative Diffusion Model (DM) pre-trained on a larger dataset and that serves for quality image enhancement. Every stage is trained separately on the given task using a separate dataset. 
# Remote Sensing Dataset
link of [UC Merced Land Use Dataset](http://weegee.vision.ucmerced.edu/datasets/landuse.html)
# Pre-train Models
SwinIR pre-train weights [swinIR_weights](https://github.com/JingyunLiang/SwinIR), 
Diffusion model pre-train weights [DM_weights](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement)
# TESR Algorithm
<img src="https://github.com/AnasHXH/TESR-Two-stage-approach-for-Enhancement-and-Super-Resolution-of-Remote-Sensing-Images/blob/main/Algorithm.png" width="400" height="300"/>
# Result
<img src="https://github.com/AnasHXH/TESR-Two-stage-approach-for-Enhancement-and-Super-Resolution-of-Remote-Sensing-Images/blob/main/Res_1_1_1.png" width="700" height="300"/>
<img src="https://github.com/AnasHXH/TESR-Two-stage-approach-for-Enhancement-and-Super-Resolution-of-Remote-Sensing-Images/blob/main/Table_res_3.3.png" width="400" height="200"/>
<img src="https://github.com/AnasHXH/TESR-Two-stage-approach-for-Enhancement-and-Super-Resolution-of-Remote-Sensing-Images/blob/main/res_2.png" width="600" height="400"/>
