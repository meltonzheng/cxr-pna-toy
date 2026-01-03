# cxr-pna-toy

### Project: Pneumonia Detection Confidence Visualizer

What you'd build: A tool that takes a chest X-ray, runs it through a pre-trained pneumonia detection model, and visualizes what the model is "looking at" using gradient-weighted class activation mapping (Grad-CAM). It would show the original image, the model's prediction (normal/pneumonia with confidence score), and a heat map overlay showing which regions influenced the decision.

# updates

tensorflow doesn't work on windows...
installed wsl2, remounted on my big drive
so many missing dependencies...
ok so tensorflow   2.19 requires  
cuDNN	CUDA
9.3	    12.5

