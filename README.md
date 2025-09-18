# end2end_celltracker
Object tracking and segmentation over time in one model.

Exploratory repo hacking into pytorch maskrcnn, computing features over the identified blobs, and linking like blobs across frames using Hungarian matching. Thus the model can simultaneously segments and tracks of objects that change morphology over time model of cells/PSF 

## Example of tracking and segmenting shapes with temporal morphology evolution using an end2end network combining object tracking
![resnet18_simulated_movie](https://github.com/user-attachments/assets/f4944b70-4956-46c7-ac57-45f6c75b58f8)


## Segmenting tracked dot removing dots in vicinity for better dot intensity vs background estimation 
https://github.com/user-attachments/assets/7ae32166-64a1-43c0-8893-4f26cecb76a5

