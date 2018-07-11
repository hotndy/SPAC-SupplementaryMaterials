#Synthetic Rain Dataset with Adobe After Effect

We present a video synthetic rain dataset. \[[download](https://github.com/hotndy/SPAC-SupplementaryMaterials)\] \[[paper](https://arxiv.org/abs/1803.10433)\]

The data category (i.e., training/testing data, and whether the rain is synthetic/real rain), the camera motion (i.e., slow/fast
moving cameras), as well as the labeling details for each data is shown in the table below.
<p align="center">
<img src="https://hotndy.github.io/projects/SPAC/rainDatasetTable.png" width="500px"/>
</p>

We also show the thumbnails for each data entry below.

<p align="center">
<img src="https://hotndy.github.io/projects/SPAC/rainDatasetThumb.png" width="500px"/>
</p>

Please cite both Adobe After Effect [2], and our paper [1] when you use this dataset, or compare with our results.


The details for each folders in the repository:
  
0. Under the folder "SPAC-CNN_code" folder are the executable code for rain removal.     
  
1. Under the "Dataset_Testing_Synthetic" and "Dataset_Training_Synthetic" folders are the synthetic rain dataset for model training, and algorithm testing.
   - Files with names xxx_GT are the scene ground truth.
   - Files with names xxx_Rain are the synthesized rainy scenes with Adobe Affter Effect.
   - Files with names xxx_spacCNN are the derain output from SPAC-CNN (only for the testing dataset).
   
   Please cite both Adobe After Effect [2], and our paper [1] when you use this dataset, or compare with our results.      

2. Under the "Dataset_Testing_realRain" folder are the real rain datset for evaluation of derain performance
   - Files with names xxx_Rain are the rainy frames.
   - Files with names xxx_spacCNN are the derain output from SPAC-CNN.
   
   Please cite our paper [1] when you use this dataset, or compare with our results. 
   
3. Under the "videoDemo" folder are the rain removal video clips used for evaluations in the paper:

   The 8 video files starting with "synthetic_" are the derain results for the synthetic rain dataset used for quantitative evaluations in our paper.
      - The 4 videos with names "Synthetic_slow_axxx.mp4" belongs to group a.
      - The 4 videos with names "Synthetic_fast_bxxx.mp4" belongs to group b.
      
   The 7 video files starting with "realrain_" are derain results for real rain.
      
4. Under the "SupperPixel_Matching_Evaluations" foder are the experiment results of content matching using SP units vs. rectangular patches for the Middleburry Stereo Dataset. Matching results for the SP units are with names "xxx_sp.png", and the results for the rectangular patches are with names "xxx_blk.png".


[1] J. Chen, C.-H. Tan, J. Hou, L.-P. Chau, and H. Li, “Robust video content alignment and compensation for rain removal in a CNN framework,” IEEE Conference on Computer Vision and Pattern Recognition, 2018. \[[pdf](https://arxiv.org/abs/1803.10433)\]

[2] Adobe After Effects Software, available at www.adobe.com/AfterEffects.

