# Automated Pavement Distress Detection using YOLOv8 and ASPDI

# Dataset
Name: MAPSIA (Manual Asphalt Pavement Surface Image Annotation)  
Images: 7,099 (Annotated for 13 classes)  
Train: 5,485  
Validation: 1,073  
Test: 544  
link : https://repositorio.unican.es/xmlui/handle/10902/26615  

# Preprocessing & Augmentation
Mosaic, MixUp, HSV transformations  
Geometric transforms (flips, scaling, shifting)  

# Model
Model Used: YOLOv8 Medium (yolov8m.pt)  
Backbone: C2f modules  
Neck: FPN  
Head: Multi-scale bounding box prediction  

# Training Details
Epochs: 30  
Batch Size: 16  
Image Size: 640×640  
Box Loss: 0.89  
Classification Loss: 0.89  
DFL Loss: 1.17  

# Results
Precision:	63.7%  
Recall:	59.7%  
mAP@0.5:	61.5%  
mAP@0.5:0.95:	42.5%  

