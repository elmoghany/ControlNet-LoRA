# Attaching controlNet into Stable Diffusion to finetune the model

## ControlNet Architecture
![picture](controlNetData/assets/controlnet-operation-principle.jpg)

# 1. Using Circle Fill50K Dataset
[fusing/fill50k](https://huggingface.co/datasets/fusing/fill50k)
## SDXL Results
### Before Finetuning
![picture](controlNetData/Circle-SDXL-Before-Training.png)

## ControlNet Results
### After Finetuning via condition 1
![picture](controlNetData/controlNet-Circle-Output/After-fill50k-ControlNet-condition1.png)
### After Finetuning via condition 2
![picture](controlNetData/controlNet-Circle-Output/After-fill50k-ControlNet-condition2.png)

# 2. Using Pose Dataset
[merlinyx/pose-controlnet](https://huggingface.co/datasets/merlinyx/pose-controlnet)
## SDXL Results
### Before Finetuning
![picture](controlNetData/Pose-SDXL-Before-Training.png)

## ControlNet Results
### After Finetuning via condition 1
![picture](controlNetData/controlNet-Pose2-Output/After-pose_merlinyx-ControlNet-condition1.png)
### After Finetuning via condition 2
![picture](controlNetData/controlNet-Pose2-Output/After-pose_merlinyx-ControlNet-condition2.png)

### Disclaimer:
1. All of the code is inside the Jupyter notebook file.
2. Parts of the code are copied from unsolved assignments of Prof. Minhyuk Sung @ KAIST, a graduate course about diffusion models.
3. Work is done during KAUST internship with KAUST GPUs @ Prof. Mohamed Elhoseiny Lab, as part of the learnings to create a diffusion project.
