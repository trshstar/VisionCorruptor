# VisionCorruptor
VisionCorruptor is an end-to-end image corruption classification pipeline built using PyTorch. It classifies 64×64 images from the Tiny ImageNet-C dataset into 15 corruption types (e.g., gaussian_noise, motion_blur, jpeg_compression) using a CNN architecture.

Includes:
<ul>
	<li>Custom PyTorch Dataset for Tiny ImageNet-C (non-standard nested structure)</li>
	<li>ResNet-18 training with early stopping, validation tracking, and test evaluation</li>
	<li>Visualization: loss/accuracy plots, confusion matrix, misclassified images</li>
</ul>

## 📊 Results Summary

| Model       | Validation Accuracy | Test Accuracy | Parameters | Notes                      |
|-------------|---------------------|---------------|------------|----------------------------|
| ResNet-18   | 97.43%              | 96.96%        | ~11M       | Baseline CNN               |

- Best model checkpoint: [`best_model.pth`]([https://huggingface.co/your-model-link](https://huggingface.co/trshstar/VisionCorruptor/blob/main/best_model.pth))
- Trained on 15 corruption types from Tiny ImageNet-C
- Image size: 64×64 | Batch size: 64 | Optimizer: Adam | Early stopping: 3 epochs
