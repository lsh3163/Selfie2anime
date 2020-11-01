# Selfie2anime
Image Translation Selfie to Anime Project

## How to Use

### Selfie2anime Dataset
.
+-- datasets
|   +-- <Your Dataset Name>
|   |    +-- trainA
|   |    +-- trainB
|   |    +-- testA
|   |    +-- testB
+-- cyclegan.py
+-- datasets.py
+-- models.py
+-- utils.py

### Clone & Train 
`python cyclegan.py --dataset_name=selfie2anime --checkpoint_interval=10`