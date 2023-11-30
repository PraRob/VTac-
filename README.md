# VTac-

The dataset comprises image sequences that represent the texture of different objects grasped by a vision-based sensor, and can be used for the purposes of object classification amongst other things. The dataset is divided by the use of either a gel-type sensor, or a pneumatic-type sensor. The details of the construction of these two types of sensors can be found in the papers referenced at the end.  



The gel-type vision-based tactile sensor section contains 2000 PNG images for each of 9 different carbide tools, each image having pixel dimensions 228x228.  

Complementing the gel-type sensor data, the dataset also contains image sequences collected using a pneumatic-type sensor. This includes the textures of 7 types of 3D priting infill patterns, as well as profiles of 11 types of handtools. Each object is represented by 250 PNG images of pixel dimension 228x228. 

 This comprehensive dataset, has applications in robotics, automation, and the broader spectrum of tactile sensing. 

This structure reflects the hierarchy of the dataset, with each level representing a different aspect of the data (e.g., images) and subdirectories further organising the data based on types. 



**VTac **

|—-gel_type_vision 

|  |—-images 

|  |  |—-carbide_tools 

|  |  |  |—-type_1 

|  |  |  |  |—-#sequence_index#.png (Image of type 1, 228x228) 

|  |  |  |  |—-...... 

|  |  |  |—-type_2 

|  |  |  |  |—-# sequence_index #.png (Image of type 2, 228x228) 

|  |  |  |  |—-...... 

|  |  |  |—-… 

| 

|—-pneumatic_tactile 

|  |—-images 

|  |  |—-3d_printing_infill 

|  |  |  |—-type_1 

|  |  |  |  |—-# sequence_index#.png (Image of type 1, 228x228) 

|  |  |  |  |—-...... 

|  |  |  |—-type_2 

|  |  |  |  |—-# sequence_index#.png (Image of type 2, 228x228) 

|  |  |  |  |—-...... 

|  |  |  |—-… 

| 

|  |  |—-hand_tools 

|  |  |  |—-type_1 

|  |  |  |  |—-# sequence_index#.png (Image of type 1, 228x228) 

|  |  |  |  |—-...... 

|  |  |  |—-type_2 

|  |  |  |  |—-# sequence_index#.png (Image of type 2, 228x228) 

|  |  |  |  |—-...... 

|  |  |  |—-... 





 
**Publications  **

1. Design and development of a robust vision-based tactile sensor- https://orca.cardiff.ac.uk/id/eprint/149803/ 

2. PnuTac: A vision-based pneumatic tactile sensor for slip detection and object classification - https://orca.cardiff.ac.uk/id/eprint/162820/ 

