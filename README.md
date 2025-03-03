# UAV-based Image Segmentation of Crop Lands into Crop/Weed Classes using Self-Constructed UNET

## (1) Image Segmentation

Image segmentation is a computer vision task that involves dividing an image into multiple segments or regions based on certain criteria. The goal is to simplify or change the representation of an image into more meaningful and easier-to-analyze parts. Segmentation is valuable because it allows computers to understand and interpret images more effectively, facilitating various applications like object recognition, image editing, medical diagnosis, and more.

## (2) Crop Lands
### UAV Captured Field vs. Segmented Field

<p align="center">
  <img src="cropland.jpg" alt="UAV Captured Field" width="45%"/>
  <img src="001_frame0038_GroundTruth_color.jpg" alt="Segmented Field" width="45%"/>
</p>

Efficient crop land maintenance is crucial for optimal agricultural outcomes, especially during growth and harvest seasons. According to the World Bank, agriculture can significantly impact poverty reduction, income elevation, and food security for the majority of the world's poor residing in rural areas. Artificially intelligent solutions, such as weed detection in crop lands using computer vision, can streamline weed identification processes, reducing manual efforts. Additionally, semi-autonomous drones and UAVs prove invaluable in surveying entire farmlands during the vulnerable growth phase, enhancing overall efficiency in weed management.


## (3) U-Net Architecture

The U-Net architecture, proposed by O. Ronneberger et al., is a convolutional neural network (CNN) designed for biomedical image segmentation, featuring a distinctive U-shaped structure. Its encoder path captures context and extracts features, while the decoder path facilitates precise localization. The network’s expansive field of view aids in comprehensive image understanding. Skip connections between encoder and decoder layers enhance information transfer, mitigating information loss during downsampling.

U-Net has proven efficacy in tasks like semantic segmentation, particularly in medical imaging where it excels at delineating structures and regions of interest with remarkable accuracy. Importantly, the U-Net architecture proves vital in accurately segmenting crops and weeds in precision farming applications. By leveraging its capabilities, it enhances the overall productivity of farms, allowing for precise identification and management of crops and weeds.

## (4) Dataset

The dataset used in this work is derived from the research conducted by I. Sa, M. Popovic, R. Khanna, Z. Chen, P. Lottes, F. Liebisch, J. Nieto, C. Stachniss, A. Walter, and R. Siegwart. Their paper, titled "WeedMap: A large-scale semantic weed mapping framework using aerial multispectral imagery and deep neural network for precision agriculture," provides the basis for our model's training and evaluation.
