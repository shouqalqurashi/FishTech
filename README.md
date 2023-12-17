# FishTech
T5-Bootcamp  - Capstone Project  
# Abstact
The project aims to develop a computer vision model that can
identify different types of fish and analyze their capture duration
by analyzing their eye images. Additionally, the model is designed
to provide market price averages based on the identified fish
types.
# Objective 
- Develop a robust computer vision model for fish identification.
- Analyze eye images to estimate the capture duration of the fish accurately.
- Provide market price information for identified fish types.
# Data Sources
- Image Dataset: Images collected through on-site photography during visits to the local fish market. This ensures a firsthand and diverse representation of various fish species in the market ,In addition to some Images from the Internet.
- Market Data: Pricing information obtained individually from the local fish market during each visit. This includes the cost of different fish species, allowing for real-time market insights.
# Methodology
1. Image Annotation: The Annotation Tool Computer Vision Annotation (CVAT) was employed for meticulous annotation.
2. Image Augmentation: We utilized the robust image augmentation tool, Roboflow, to enhance the diversity and richness of our image dataset.
3. Computer Vision Model for Fish Identification and Freshness: The selection for the Computer Vision Model for Fish Identification and freshness centered around the YOLOv8 (You Only Look Once) algorithm. This choice stems from its efficiency in real-time object detection, making it well-suited for the identification of diverse fish species and assessment of freshness in images.
4. Implementation Steps: Programming Languages and Development Tools, Python and Dart programming language, along with popular libraries for computer vision tasks, as well Google Colab and Visual Studio Code used for implementation.
- Interface Design: Figma was utilized for interface design, ensuring a user-friendly and visually appealing presentation.
- Deployment Platform: Flatter Application was employed for the deployment of the project, offering a streamlined and accessible user experience.
- Market Data Integration: The inclusion of a hard-coded price further fortifies the integration, providing a baseline for comprehensive market insights.
