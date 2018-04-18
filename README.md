# SPAC-SupplementaryMaterials
Supplementary material repository for Robust Video Content Alignment and Compensation framework for rain removal applications.

1. Under the videoDemo folder are the rain removal video clips used for evaluations in the paper:

   The 8 video files starting with "synthetic_" are the derain results for the synthetic rain dataset used for quantitative evaluations in our paper.
      - The 4 videos with names "Synthetic_slow_axxx.mp4" belongs to group a.
      - The 4 videos with names "Synthetic_fast_bxxx.mp4" belongs to group b.
      
   The 7 video files starting with "realrain_" are derain results for real rain.
      
2. Under the SupperPixel_Matching_Evaluations foder are the results of SP units vs. rectangular patches for the Middleburry Stereo Dataset. Matching results for the SP units are with names "xxx_sp.png", and the results for the rectangular patches are with names "xxx_blk.png".

3. Under the Dataset_Testing_Synthetic are the synthetic rain dataset for algorithm testing.
   - Files with names xxx_GT are the scene ground truth.
   - Files with names xxx_Rain are the synthesized rainy scenes with Adobe Affter Effect.
   - Files with names xxx_spacCNN are the derain output from SPAC-CNN.
   
   Please cite both Adobe After Effect [2], and our paper [1] when you use this dataset, or compare with our results.   
   
   [1] J. Chen, C.-H. Tan, J. Hou, L.-P. Chau, and H. Li, “Robust video content alignment and compensation for rain removal in a CNN framework,” IEEE Conference on Computer Vision and Pattern Recognition, 2018.
   
   [2] Adobe After Effects Software, available at www.adobe.com/AfterEffects.

4. Under the Dataset_Testing_realRain are the real rain datset for evaluation of derain performance
   - Files with names xxx_Rain are the rainy frames.
   - Files with names xxx_spacCNN are the derain output from SPAC-CNN.
   
   Please cite our paper [1] when you use this dataset, or compare with our results. 
   
   [1] J. Chen, C.-H. Tan, J. Hou, L.-P. Chau, and H. Li, “Robust video content alignment and compensation for rain removal in a CNN framework,” IEEE Conference on Computer Vision and Pattern Recognition, 2018.
