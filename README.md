# Colorectal-tumor-segmentation
Abstract: Automated Segmentation of Colorectal Tumor in 3D MRI Using 3D Multiscale Densely Connected Convolutional Neural Network
The main goal of this work is to automatically segment colorectal tumors in 3D T2-weighted (T2w) MRI with reasonable accuracy. For such a purpose, a novel deep learning-based algorithm suited for volumetric colorectal tumor segmentation is proposed. The proposed CNN architecture, based on densely connected neural network, contains multiscale dense interconnectivity between layers of fine and coarse scales, thus leveraging multiscale contextual information in the network to get better flow of information throughout the network. Additionally, the 3D level-set algorithm was incorporated as a postprocessing task to refine contours of the network predicted segmentation. The method was assessed on T2-weighted 3D MRI of 43 patients diagnosed with locally advanced colorectal tumor (cT3/T4). Cross validation was performed in 100 rounds by partitioning the dataset into 30 volumes for training and 13 for testing. Three performance metrics were computed to assess the similarity between predicted segmentation and the ground truth (i.e., manual segmentation by an expert radiologist/oncologist), including Dice similarity coefficient (DSC), recall rate (RR), and average surface distance (ASD). The above performance metrics were computed in terms of mean and standard deviation (mean ± standard deviation). The DSC, RR, and ASD were 0.8406 ± 0.0191, 0.8513 ± 0.0201, and 2.6407 ± 2.7975 before postprocessing, and these performance metrics became 0.8585 ± 0.0184, 0.8719 ± 0.0195, and 2.5401 ± 2.402 after postprocessing, respectively. We compared our proposed method to other existing volumetric medical image segmentation baseline methods (particularly 3D U-net and DenseVoxNet) in our segmentation tasks. The experimental results reveal that the proposed method has achieved better performance in colorectal tumor segmentation in volumetric MRI than the other baseline techniques.




Reference: Mumtaz Hussain Soomro, Matteo Coppotelli, Silvia Conforto, et al., “Automated Segmentation of Colorectal Tumor in 3D MRI Using 3D Multiscale Densely Connected Convolutional Neural Network,” Journal of Healthcare Engineering, vol. 2019, Article ID 1075434, 11 pages, 2019. https://doi.org/10.1155/2019/1075434.
