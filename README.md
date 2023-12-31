# Avalanche Alert
![Avalanche Alert Logo](https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/078ba9a0-4ad7-425c-a325-ed5164495f6a)

## Mission Statement
  At Avalanche Alert, our mission is to be at the forefront of safeguarding lives and landscapes through cutting-edge avalanche detection software. Committed to innovation and excellence, we strive to develop advanced technologies that provide real-time, accurate, and reliable avalanche detection capabilities. Our software is designed to empower mountain communities, ski resorts, and emergency response teams with the tools they need to proactively manage and mitigate avalanche risks. We prioritize the safety of individuals and the preservation of natural environments, recognizing the critical role that early detection plays in averting potential disasters. With a passionate commitment to pushing the boundaries of technological advancement, Avalanche Alert is dedicated to creating a safer and more secure future for those who live, work, and play in avalanche-prone regions.

## Why It's Important

Avalanche detection software plays a crucial role in mitigating the risks associated with avalanches and safeguarding lives and infrastructure in mountainous regions. The unpredictable nature of avalanches poses a significant threat to both human safety and property. Avalanche detection software utilizes advanced technologies, such as sensors, satellite data, and machine learning algorithms, to monitor environmental conditions and detect potential avalanche precursors in real time. By providing early warning systems, this software empowers communities, ski resorts, and emergency responders to take proactive measures, evacuate at-risk areas, and implement safety protocols swiftly. The timely detection of avalanche threats not only saves lives but also minimizes the impact on critical infrastructure, transportation networks, and recreational areas. In essence, avalanche detection software is a vital tool in the proactive management of avalanche risks, contributing to the overall safety and resilience of mountainous regions.

## The Problem

Avalanches pose significant threats and challenges due to their destructive nature and potential impact on human lives, infrastructure, and the environment. Here are key reasons why avalanches are a serious issue:

1. Life Threatening: Avalanches can be deadly, causing injuries or fatalities to those caught in their path. Skiers, snowboarders, mountaineers, and residents in avalanche-prone areas are particularly at risk.

2. Property Damage: Avalanches can destroy buildings, roads, and other infrastructure in their descent. This not only leads to economic losses but also disrupts essential services and transportation networks.

3. Isolation and Access Issues: Avalanche debris can block roads and trails, isolating communities and hindering access for emergency services, making rescue and relief efforts challenging.

4. Economic Impact: Avalanche incidents can have significant economic consequences for industries dependent on mountainous regions, such as tourism and winter sports. Resorts, businesses, and local economies may suffer due to closures and reduced visitor numbers.

5. Environmental Impact: Avalanches can cause deforestation, alter landscapes, and disrupt ecosystems. The displacement of snow can result in the loss of vegetation and contribute to soil erosion.

6. Search and Rescue Challenges: Recovering individuals buried under avalanche debris is a complex and time-sensitive task. Avalanche rescue operations require specialized skills, equipment, and coordination.

7. Recreational Risks: Outdoor enthusiasts engaging in winter sports and activities may inadvertently trigger avalanches. Lack of awareness, inadequate preparation, or failure to assess avalanche risk can lead to accidents.

8. Climate Change Impact: Changes in climate patterns can affect snowpack stability and increase the frequency and intensity of avalanches. Rising temperatures may lead to more unpredictable conditions and heightened avalanche risks.

9. Population Growth in Mountainous Areas: As more people settle in or visit mountainous regions, the potential impact of avalanches on human life and infrastructure increases, emphasizing the need for effective risk management strategies.

Addressing the challenges associated with avalanches requires a combination of advanced technology, effective communication, public education, and comprehensive risk management strategies to minimize the impact of these natural events on both individuals and communities.

## The Data
These are example images from the deck

Mountain with Avalanche
![Avalanche Slides](https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/8d2732b5-8889-4e70-a127-7c1cc6058812)

Mountain without Avalanche
![AMountain](https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/dfd9c565-170e-47af-9fe5-d8413dea3033)
## Link to Data Deck Slides
https://docs.google.com/presentation/d/1VCm2VcFhpEISGbaMAU13tInZOcuI5w2qtCj1ZeBKtAM/edit?usp=sharing

## Functions
Sure, here are brief definitions for each term in the given order:

1. Python: Python is a high-level programming language widely used in the field of machine learning and deep learning for its simplicity and versatility.

2. Colab: Colab, short for Colaboratory, is a cloud-based platform provided by Google that allows users to run Python code in a Jupyter notebook environment with free access to GPU resources.

3. AlexNet: AlexNet is a pioneering convolutional neural network (CNN) architecture designed for image classification tasks, notable for its success in the ImageNet Large Scale Visual Recognition Challenge.

4. GPU: A Graphics Processing Unit (GPU) is a specialized hardware component that accelerates the training of deep learning models by parallelizing computations, significantly improving performance compared to traditional CPUs.

5. Filters, Feature Map, Pooling: In CNNs like AlexNet, filters are small learnable weights used to convolve over input images, generating feature maps that highlight important patterns, and pooling is a downsampling operation that reduces the spatial dimensions of the feature maps.

6. AlexNet's design: AlexNet's design refers to the specific architectural choices, layer configurations, and parameters used in the construction of the AlexNet model, including convolutional layers, fully connected layers, and other components.

7. GPUs, ReLU, Tensor, Matrix: GPUs (Graphics Processing Units) are hardware accelerators used for parallel computation in deep learning. ReLU (Rectified Linear Unit) is an activation function that introduces non-linearity. Tensors and matrices are data structures used to represent multi-dimensional data in neural networks.

8. RGB, Pixel, Resizing Images: RGB (Red, Green, Blue) is a color representation used in images, with pixels being individual data points representing color values. Resizing images involves adjusting their dimensions to meet specific requirements, a common preprocessing step in deep learning workflows.

## Alexnet
In the code, AlexNet acts like a super-smart image detective. It's been trained on a ton of images, so it knows how to recognize different patterns and features in pictures. When we show it slides from a presentation, AlexNet quickly goes through its memory bank, identifies important details, and helps figure out what's in each image. It's like having a really experienced friend who can spot specific things in pictures without much effort. This makes the code much more efficient because we don't have to teach the model everything from scratch; AlexNet already has a good sense of what's going on in images. So, it's like having a smart assistant that makes the image classification task way easier and faster.
<img width="708" alt="Screenshot 2023-12-06 at 4 57 54 PM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/aae3cafe-c9b8-44bc-a4ff-b7d0c36f58ce">

## Link to Interactive Alexnet Architecture
https://tensorspace.org/html/playground/alexnet.html

## Link to my Code
https://colab.research.google.com/drive/1KwxDKyJ9OKMa6emnG_exnEVpDShimKXt?usp=sharing

## WANDB
The wandb code in the script integrates the Weights and Biases (wandb) tool for experiment tracking and visualization. After installation and project initialization ("oh-ya"), it logs crucial metrics, including training loss and accuracy, using wb.log(). This allows real-time monitoring and analysis through the Weights and Biases interface. By leveraging wandb, the script provides a streamlined approach for tracking and visualizing the training process, enhancing reproducibility and collaboration in deep learning experiments.


<img width="816" alt="Screenshot 2023-12-07 at 2 33 22 PM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/56649b1b-d6db-4b4c-85b1-e01bc213488e">


<img width="903" alt="Screenshot 2023-12-07 at 2 33 32 PM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/a9fc2a20-aca8-4235-b657-f08d2ea4eac1">

## My Weights & Biases

https://wandb.ai/oh-ya/oh-ya/runs/5y7tdnqf?workspace=user-jennakvasnovsky

## Feature Map

The code demonstrates the visualization of feature maps within the context of a pre-trained AlexNet model. It begins by loading the model, preprocessing an image from a given URL, and extracting the weights of specific layers. The script then computes the feature maps by convolving the image with these filters, visualizing the results using the provided plotting functions. Feature maps are further processed through activation functions (ReLU) and pooling layers. The final layers involve linear transformations, resulting in a classification output. The script concludes with a prediction based on the highest activation in the output layer. Additionally, a utility function is included for plotting feature maps with their corresponding filters, offering insights into the learned patterns at different stages of the network. This code provides a comprehensive exploration of how feature maps are computed and manipulated through the layers of a deep neural network, shedding light on the model's understanding of hierarchical image features.

<img width="973" alt="Screenshot 2023-12-07 at 11 20 55 AM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/a0ae035e-3fd1-4ad1-8b4a-b5e47b732f3f">

## Link to my Code
https://colab.research.google.com/github/JennaKvasnovsky/AvalancheAlert/blob/main/Avalanche_Working_Feature_Maps.ipynb

## Pose

The provided code implements human pose estimation using the MoveNet model, designed for single-person pose detection. MoveNet, available on TensorFlow Hub, offers Lightning for low latency and Thunder for high accuracy. The code demonstrates loading the model, running inference on a single image, and extending it to a video. It includes visualization and a cropping algorithm for improved subject focus. The code utilizes TensorFlow, TensorFlow Hub, OpenCV, and Matplotlib. MoveNet's speed and accuracy make it suitable for real-time fitness and wellness applications. The results are presented visually, including a GIF for video pose estimation. The code serves as a concise guide for MoveNet utilization.

<img width="371" alt="Screenshot 2023-12-07 at 12 16 58 PM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/cff5e458-8438-4900-afa6-f16040ccb5e9">

## Link to my Code
https://colab.research.google.com/github/JennaKvasnovsky/AvalancheAlert/blob/main/Avalanche_Pose_Machine.ipynb

## YOLOv5

The presented code introduces YOLOv5, an object detection model implemented by Ultralytics. It starts by cloning the YOLOv5 repository and installing necessary dependencies. The script performs object detection on images using a pre-trained YOLOv5s model, specifying parameters like image size and confidence threshold. The results are visually displayed with Matplotlib, showcasing YOLOv5's ability to identify objects in diverse scenes, such as images of skiers. The code concludes by demonstrating how the model can be applied to user-provided images, either locally stored or downloaded from a URL. This showcases YOLOv5's versatility in handling different image sources for robust object detection.

<img width="836" alt="Screenshot 2023-12-07 at 2 04 02 PM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/93940aa2-46bb-4b21-9228-bacdf7668dbe">

## Link to my Code
https://colab.research.google.com/github/JennaKvasnovsky/AvalancheAlert/blob/main/Avalanche_YOLOv5.ipynb

## SAM Mask Generator
The code showcases SAM (Segment Anything) for automatic mask generation. Utilizing the SamAutomaticMaskGenerator class, SAM efficiently processes prompts, sampling single-point prompts in a grid pattern over an image to predict multiple masks. These masks undergo quality filtering and deduplication, with options for further improvement through parameters like image cropping and postprocessing. The example demonstrates SAM's flexibility by providing various configuration options for mask sampling density, quality thresholds, and post-processing parameters. Finally, visualizations overlay the generated masks on an example image, highlighting SAM's versatility in automatic mask generation tasks.

<img width="773" alt="Screenshot 2023-12-07 at 3 03 23 PM" src="https://github.com/JennaKvasnovsky/AvalancheAlert/assets/143115856/e2c846fc-1b39-4389-ba48-8cf7ac035087">

## Link to my Code
https://colab.research.google.com/github/JennaKvasnovsky/AvalancheAlert/blob/main/Avalanche_SAM.ipynb

## Contact Information 
If you have any questions or concerns please contact us at jkvasnovsky2023@fau.edu

