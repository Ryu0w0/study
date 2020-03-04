# Finetuning FasterRCNN

This file perform finetuning based on the pre-trained FasterRCNN model (fasterrcnn_resnet50_fpn).

The purposes of this implementation are understanding the 4 points below.

1. Whole process of finetuning
2. Way to create own Dataset, Dataloader, Transformer and training iterations
3. Structures and implementation of FasterRCNN in PyTorch
4. Get used to read PyTorch raw codes to know the typical implementation of models