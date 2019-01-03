# 		Classify subcellular protein patterns in human cells



# 						Data Processing Folder

####       Features_Augmentand_Vizualization.ipynb
 
 - This notebook is an explroation of different feature augmentation methods and their vizualization. The features augmentations that were implemented include normaed gradient using Sobel kernel, directional gradient, normed gradient with constant thresholds, and reducing images size wtih blocks. 
 
 
 # 					Pipeline and Models Folder
 
 ####       Training_Spoon_Model_with_pipeline.ipynb
 
 - This notebook contains a VGG-Network implementation with images and U-Net-Network implementation with 4-channels images but also a combinaison of both that led to the creation of the "Spoon-Net".
 
 - It also contains a customizable pipeline with all features augmentation implemented in the other notebook and data augmentation methods. It goes into depth into probablity of predicting a given label, the mean predictions for a given class, the standard deviations for the predictions of any given class, and provides graphs illustrating all of the results.

 # 					Papers and Illustrations Folder
  
   ####       Final_paper.pdf

- This is a formal write up for the project with everything from introduction explanation to models and results.
