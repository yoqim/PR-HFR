# Physical-based Rendering for NIR-VIS Face Recognition
# Training




# Testing
## Preparation
- Data (112 x 112)
    - CASIA / LAMP-HQ (only fold 1 provided)
    - Oulu / BUAA
- TestImg Lists
    - At './data/$dataset'
- Models
    - Put pretrain model at models/pretrain/
    - Put finetune model at models/finetune/$dataset/

Testing data & Models can be downloaded from [Google drive]{}

## How to run?
sh eval.sh
