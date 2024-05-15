# StarDist Segmentation Project

This repository contains code for training and using the StarDist model for segmentation of microscopy images, utilizing both custom-trained and pre-trained models.

### Custom-Trained Model

The custom-trained model is tailored to specific datasets. By training on custom data, the model learns to accurately segment images based on unique features and structures present in the user's dataset. 

### Pre-trained Model

The trained StarDist model offers a quick and effective solution for segmentation without the need for extensive training. It is particularly useful for users who need reliable segmentation results on standard datasets.

## Results

The segmented images are saved in the specified output directory, with filenames appended by `_segmentation.png`. This provides a visual representation of the segmentation overlayed on the original images, facilitating easy comparison and analysis. Example results include segmented versions of typical microscopy images, showcasing the model's ability to accurately delineate complex structures.

### Example Results

- **Pretrained Model Trained Segmented Image**: ![Alt text](https://github.com/shuchismita-anwar/Custom-StarDist-Model/blob/master/segmentation_results_pretrained/Muc1_Ecad_SPC_x20_2_XY10_00016_CH3_segmentation.png)
- **Custom Model Trained Segmented Image**: ![Alt text](https://github.com/shuchismita-anwar/Custom-StarDist-Model/blob/master/segmentation_results/Muc1_Ecad_SPC_x20_2_XY10_00016_CH3_segmentation.png)

## Installation

To run this project, ensure you have the following Python packages installed:

```bash
tensorflow==2.4.0
stardist==0.7.0
csbdeep==0.6.2
tifffile==2021.4.8
opencv-python==4.5.1.48
```

**Python Version**: This project is compatible with Python 3.8 and above.
