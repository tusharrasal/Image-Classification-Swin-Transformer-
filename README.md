# Image-Classification-Swin-Transformer-
Image Classification (Swin Transformer (large-sized model))
Swin Transformer model pre-trained on ImageNet-21k (14 million images, 21,841 classes) at resolution 224x224. It was introduced in the paper Swin Transformer: Hierarchical Vision Transformer using Shifted Windows by Liu et al. and first released in this repository.

Disclaimer: The team releasing Swin Transformer did not write a model card for this model so this model card has been written by the Hugging Face team.

Model description
The Swin Transformer is a type of Vision Transformer. It builds hierarchical feature maps by merging image patches (shown in gray) in deeper layers and has linear computation complexity to input image size due to computation of self-attention only within each local window (shown in red). It can thus serve as a general-purpose backbone for both image classification and dense recognition tasks. In contrast, previous vision Transformers produce feature maps of a single low resolution and have quadratic computation complexity to input image size due to computation of self-attention globally.

model image

Source

Intended uses & limitations
You can use the raw model for image classification. See the model hub to look for fine-tuned versions on a task that interests you.
