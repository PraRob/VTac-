# VTac

The dataset comprises image sequences that represent the texture of different objects grasped by a vision-based sensor, and can be used for the purposes of object classification amongst other things. The dataset is divided by the use of either a gel-type sensor, or a pneumatic-type sensor. The details of the construction of these two types of sensors can be found in the papers referenced at the end.  

![Data_collection_Tools](https://github.com/PraRob/VTac-/assets/131763612/3503129d-21c6-44df-947e-7d678eb71100) 

![Data_colltectcion_3Dinfill](https://github.com/PraRob/VTac-/assets/131763612/97c9f59e-8cdf-4cb8-8d5d-5cef3a6b0acf)

The gel-type vision-based tactile sensor section contains 2000 PNG images for each of 9 different carbide tools, each image having pixel dimensions 228x228.  

Complementing the gel-type sensor data, the dataset also contains image sequences collected using a pneumatic-type sensor. This includes the textures of 7 types of 3D priting infill patterns, as well as profiles of 11 types of handtools. Each object is represented by 250 PNG images of pixel dimension 228x228. 

This comprehensive dataset, has applications in robotics, automation, and the broader spectrum of tactile sensing. 

This structure reflects the hierarchy of the dataset, with each level representing a different aspect of the data (e.g., images) and subdirectories further organising the data based on types. 



# VTac 

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





 
# Publications

```latex
@inproceedings{rayamane2023pnutac,
  title={PnuTac: A vision-based pneumatic tactile sensor for slip detection and object classification},
  author={Rayamane, Prasad and Herbert, Peter and Munguia-Galeano, Francisco and Ji, Ze},
  booktitle={2023 29th International Conference on Mechatronics and Machine Vision in Practice (M2VIP)},
  pages={1--6},
  year={2023},
  organization={IEEE}
}
```

```latex
@inproceedings{rayamane2023towards,
  title={Towards smooth human-robot handover with a vision-based tactile sensor},
  author={Rayamane, Prasad and Munguia-Galeano, Francisco and Tafrishi, Seyed Amir and Ji, Ze},
  booktitle={Annual Conference Towards Autonomous Robotic Systems},
  pages={431--442},
  year={2023},
  organization={Springer}
}
```

