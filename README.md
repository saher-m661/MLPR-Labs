<h2>Aim</h2>
The aim of this project was to explore distance-based learning and unsupervised clustering techniques through practical image processing tasks. Specifically, the objective was to detect faces in images, extract meaningful color features, cluster detected faces using K-Means based on similarity, and classify a template image into one of the learned clusters.

<h2>Methodology</h2>
The project was implemented using Python libraries including OpenCV, NumPy, Matplotlib, and Scikit-learn. The methodology consisted of the following steps:

1. Image Acquisition and Preprocessing:

   Images were loaded using OpenCV and converted to grayscale for face detection using a Haar Cascade classifier. Detected faces were highlighted with bounding boxes and labeled.

2. Feature Extraction: 

   The detected face regions were converted to HSV color space, and the mean hue and saturation values were computed as numerical feature representations for each face.

3. Clustering: 

   The extracted features were clustered using the K-Means algorithm to group visually similar faces based on color characteristics. Scatter plots and annotated visualizations were generated to analyze cluster distribution and centroids.

4. Template Classification: 

   A template image was processed similarly by extracting hue and saturation features and predicting its cluster membership using the trained K-Means model.

5. Visualization and Evaluation: 

   Results were visualized through plots showing cluster separation, centroids, and template placement.

<h2>Results and Visualizations</h2>

<h5>Detected faces in Plaksha Faculty image</h5>

<img width="712" height="504" alt="image" src="https://github.com/user-attachments/assets/d6ffcfc0-fa03-4fd0-92e7-af85f8764cc8" />

<h5>Face clustering based on Hue and Saturation</h5>

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/6858dab6-12df-441e-a3be-01e6cd3d7e85" />

<h5>Face clustering based on Hue and Saturation - Scatter plot</h5>

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/25f3702f-255b-4aed-9aa9-57e942268619" />

<h5>Face Detection of Template Image</h5>

<img width="389" height="389" alt="image" src="https://github.com/user-attachments/assets/8596673e-4530-4073-9895-f3da3f84ba5c" />

<h5>Template Face Cluster Prediction</h5>

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/e49b03f7-a6e3-4639-8d23-7d3ddbf06444" />

<h5>Cluster Visualization-Scatter plot</h5>

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/01fa099c-ca1b-4733-a32c-4243db1a6fef" />

<h2>Key Findings</h2>

- Face detection using Haar Cascades successfully identified regions of interest for feature extraction.

- Hue and saturation values provided a simple yet effective low-dimensional representation for clustering visual data.

- K-Means clustering grouped faces based on similarity in color features, demonstrating how distance metrics influence grouping behavior.

- The template image was successfully processed and positioned within the clustering space, showing that the implemented framework could generalize to unseen input and associate it with an appropriate cluster based on feature similarity.

<h2>Conclusion</h2>

This project demonstrated the use of face detection, color-based feature extraction, and K-Means clustering for analyzing visual data without labeled supervision. Haar Cascade detection successfully isolated relevant facial regions, while hue and saturation features provided an effective low-dimensional representation for clustering. The successful clustering of the template image further validated the reliability of the implemented framework. Overall, the results highlighted the importance of preprocessing, feature representation, and visualization in improving interpretability and performance in unsupervised learning tasks.

   
