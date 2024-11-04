# Crop Disease Detection for Sub-Saharan Africa
    # Introduction
In Sub-Saharan Africa, crop diseases and pests are responsible for up to a 40% reduction in crop yields each year, posing a significant threat to food security and economic stability. With agriculture employing over 60% of the population and contributing roughly 23% of the region's GDP, these losses are especially detrimental. The increasing prevalence of crop diseases, driven by climate change and limited access to advanced agricultural technologies, has severely impacted key crops. Diseases such as tomato leaf curl virus and pepper blight are leading to major yield reductions, putting millions of livelihoods at risk.

This project aims to develop a machine learning solution capable of accurately detecting and identifying diseases in three essential crops: corn, pepper, and tomato. By providing an accessible and reliable disease detection tool, this project hopes to support subsistence farmers in diagnosing crop issues early, minimizing losses, and enhancing food security in the region.

    #Objective
The primary objectives of this project are to:

Accurately Detect Multiple Diseases: Identify different diseases in corn, pepper, and tomato crops with high precision. The model will aim to generalize well to various conditions, even detecting previously unseen diseases.
Deploy Efficiently on Edge Devices: Optimize the model for performance on low-cost smartphones, which are commonly used by subsistence farmers in Sub-Saharan Africa, enabling easy and quick disease identification in the field.
By combining data insights with advanced machine learning, this project aims to deliver a solution that enhances crop productivity, sustainability, and food security for millions in the region.

    #Exploratory Data Analysis (EDA)
The project begins with a comprehensive Exploratory Data Analysis (EDA) phase. This step is crucial to understand the patterns, distributions, and potential outliers in the dataset, which includes labeled images of corn, pepper, and tomato crops affected by various diseases. EDA will uncover underlying trends such as:

The frequency of each disease type.
Diversity within each crop class.
Any imbalances in the dataset that may impact model performance.
Through EDA, insights into the dataset’s structure will inform data preprocessing steps, such as balancing classes and augmenting data, to ensure the model generalizes well to new cases and performs robustly across different disease categories.

     # Model Selection: YOLO (You Only Look Once)
To tackle the challenge of disease detection, this project uses the YOLO (You Only Look Once) object detection model. YOLO is selected for its speed and accuracy, making it suitable for real-time detection on edge devices, including entry-level smartphones accessible to small-scale farmers. Key features of YOLO that make it ideal for this project include:

-Single-Stage Detection: YOLO’s architecture allows it to detect multiple objects within an image in a single pass, enabling real-time disease detection.
-Robustness and Precision: YOLO can handle complex images with multiple disease types, making it effective in agricultural environments where diverse conditions are common.
-Compatibility with Edge Devices: Optimized for performance on low-resource devices, YOLO can be deployed on affordable smartphones widely used by farmers.
The YOLO model will be fine-tuned to recognize specific diseases in corn, pepper, and tomato crops, enabling it to identify multiple disease types in a single image, even in challenging agricultural settings.

       #Features
This project includes:

Automated Disease Detection: A YOLO-based model trained to detect multiple diseases in corn, pepper, and tomato crops.
Real-Time Detection: The model’s architecture enables fast processing, providing results in real time, which is critical for field use.
Edge Device Compatibility: Optimized to run on low-cost smartphones, making it accessible to farmers with limited resources.
Exploratory Data Analysis (EDA): Comprehensive data analysis to understand disease distribution and class diversity, guiding model development for better accuracy.




