# Segmentation of Satellite Imagery using CNNs and SAM


The goal of this Google Colab project is to accurately automatically segment a satellite imagery.

To achieve this, a Convolutional Neural Network (CNN) is employed in conjunction with the [Segment Anything Model (SAM)](https://segment-anything.com/), a sophisticated segmentation algorithm known for its strong performance.

This Python-based implementation utilizes the leafmap library to handle and process the geospatial data, allowing users to select specific regions of interest for analysis. The algorithm has demonstrated its effectiveness in segmenting the differents objects mainly buildings.


```
# Make sure you use GPU runtime for this notebook. For Google Colab, go to Runtime -> Change runtime type and select GPU as the hardware accelerator.
```
 ## Core Technical Skills:

- Convolutional Neural Networks (CNNs): For object detection tasks.
- Segment Anything Model (SAM): For advanced image segmentation.
- Image Segmentation Algorithms: Demonstrates understanding of the underlying techniques.
- Object Detection: The primary task being addressed.
- Geospatial Data Analysis: Working with satellite imagery.
- Python Programming: The primary language used.

## Tools & Libraries:

- Google Colab: The development environment.
- leafmap: For geospatial data handling and visualization in Colab.
- Deep Learning Frameworks (Implicit): While not explicitly stated, it's implied you're using a framework like TensorFlow or PyTorch with CNNs. You could mention this if you want to be more specific (e.g., "TensorFlow/PyTorch").

## Conceptual Understanding:

- Region of Interest (ROI) Analysis: The ability to focus on specific areas.
- Remote Sensing: Understanding of satellite imagery and its applications.


# Results:

  <table style="border-collapse: collapse;">
  <tr>
    <td><img src="https://github.com/fadodo/Satellite_image_segmentation/blob/main/comparison_map.jpeg" alt="Image 1 Description" width="500"></td>
    <td><img src="https://github.com/fadodo/Satellite_image_segmentation/blob/main/segment_mask.png" alt="Image 2 Description" width="500"></td>
  </tr>
</table>
