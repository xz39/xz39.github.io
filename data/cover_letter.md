My biggest areas of expertise are generative AI and video understanding with AI. 

With Generative AI, my early works include
- Arbitrary Style Guidance for Enhanced Diffusion-Based Text-to-Image Generation
- Fast Diffusion Probabilistic Model Sampling through the lens of Backward Error Analysis.
- Diffusion Motion: Generate Text-Guided 3D Human Motion by Diffusion Model.
- GBSD: Generative Bokeh with Stage Diffusion
These works investigate the statistical aspects of styles for diffusion, speeding up the optimization process, the generation of motion sequences and getting Bokeh effects with time-varying prompts. After the wide availability of SD models, in applications, we focused on various customization / consistency methods. We were one of the first to investigate the idea of inference-time customization, now hundreds of papers have emerged in this area.
- Retrieving Conditions from Reference Images for Diffusion Models
We study generation consistency both from a data, method and evaluation perspective. We collected multi-level same identity data and proposed a network structure to more effectively inject information into the denoising Unet. Ongoing,

My other area of expertise is in video understanding:
- Feature Combination Meets Attention
- ASM-Loc: Action-Aware Segment Modeling for Weakly-Supervised Temporal Action Localization
- SoccerNet-Tracking: Multiple Object Tracking Dataset and Benchmark in Soccer Videos
- SoccerNet 2022 Challenges Result
- SoccerNet game state reconstruction: End-to-end athlete tracking and identification on a minimap
In these works, we processed videos with distributed pipelines. We applied tranformers, state of the art multi-modal models, detection models and so on to process Soccer videos.

Current interests:
- Video generation: Solving the object rigidity problem. Diffusion UNet (DiT to be investigated) are not good at maintaining structure. VLM agent driven 3D generation enables easy generation of consistent long videos. 
- Structure vs texture: Image and videos can be decomposed as structures and textures. 3D engine driven videos can provide structural input into video generation. A lot of success has been had with works such as ControlNet, Animate Anyone, StableTryOn. Another posibiility is to accelerate the diffusion process when structuress are present.
- Agent for GUI workflow: Extracting GUI -> structured -> actions workflows from existing tutorials and make useful workflows. This also ties in with 1 for more powerful applications of 3D engines. (Action models should replace GUI eventually).
