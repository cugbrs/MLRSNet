# MLRSNet: A Multi-label High Spatial Resolution Remote Sensing Dataset for Semantic Scene Understanding 

MLRSNet provides different perspectives of the world captured from satellites. That is, it is composed of high spatial resolution optical satellite images. MLRSNet contains 109,161 remote sensing images that are annotated into 46 categories, and the number of sample images in a category varies from 1,500 to 3,000. The images have a fixed size of 256×256 pixels with various pixel resolutions (~10m to 0.1m). Moreover, each image in the dataset is tagged with several of 60 predefined class labels, and the number of labels associated with each image varies from 1 to 13. The dataset can be used for multi-label based image classification, multi-label based image retrieval, and image segmentation. The dataset is also published on the [Mendeley Data](https://data.mendeley.com/datasets/7j9bv9vwsx/2), and the trained models have uploaded to [Google Cloud Drive](https://drive.google.com/file/d/1T9lsYsE95KV2iOYEnWV9Qj008prMT_5S/view?usp=sharing).

## The Dataset includes:
1.	Images folder: 46 categories, 109,161 high-spatial resolution remote sensing images.
2.	Labels folders: each category has a . csv file.
3.	Categories_names. xlsx: Sheet1 lists the names of 46 categories, and the Sheet2 shows the associated multi-label to each category.

The Models folder includes eight CNN models which are trained on the MLRSNet dataset with the training-validation-testing ratio is 40%-10%-50%. 

## Requirements：
· Python = 3.6  
· Tensorflow = 1.14.0  
· Keras = 2.3.1  

**More details are described in our paper**:  
Qi, Xiaoman, et al. "[MLRSNet: A multi-label high spatial resolution remote sensing dataset for semantic scene understanding.](https://www.sciencedirect.com/science/article/abs/pii/S0924271620302677)" ISPRS Journal of Photogrammetry and Remote Sensing 169 (2020): 337-350.
