# VisionCorruptor
VisionCorruptor is an end-to-end image corruption classification pipeline built using PyTorch. It classifies 64×64 images from the Tiny ImageNet-C dataset into 15 corruption types (e.g., gaussian_noise, motion_blur, jpeg_compression) using a CNN architecture.

Includes:
<ul>
	<li>Custom PyTorch Dataset for Tiny ImageNet-C (non-standard nested structure)</li>
	<li>ResNet-18 training with early stopping, validation tracking, and test evaluation</li>
	<li>Visualization: loss/accuracy plots, confusion matrix, misclassified images</li>
</ul>	
