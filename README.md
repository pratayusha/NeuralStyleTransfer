# NeuralStyleTransfer
Using Neural Style Transfer and background modification to stylize portrait images keeping background unchanged.

Algorithm 
1. Used MODNet Segmentation model to seperate background and portrait object by generating alpha layer.
2. Feature Extraction of Style image (pattern) and content image (facial features) are done using FaceNet, FaceMesh ang VGG-19 architectures.
3. Finally, features are merged with segmented image to keep background intact and stylized the featured part.

Helpful references:
http://cs231n.stanford.edu/reports/2017/pdfs/416.pdf
https://www.fritz.ai/style-transfer/



