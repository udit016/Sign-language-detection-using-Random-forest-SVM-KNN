<img width="1202" height="764" alt="image" src="https://github.com/user-attachments/assets/24edfb86-c01a-4e49-b344-46c40f127a25" /># Sign Language Recognition Under Varying Lighting Conditions: A Comparative Analysis of KNN, Random Forest,and SVM

# Experimental tests prove the strength and performance differences of these models, showing their strengths and weaknesses. Given good lighting conditions and a plain background, the overall accuracy results show that KNN shows the highest overall accuracy in all lighting conditions, with up to 95% in sunlight and 89.16% in darkness. 

# Methodology and Research Design
1. Dataset: A subset of 1,000 images from the ASL (American Sign Language) Alphabet Dataset (A to L) was used. Images were explicitly collected or selected to cover three lighting conditions: dim, moderate, and sunlight-exposed.

2. Feature Extraction: MediaPipe was employed to detect and extract 21 hand landmarks per hand (x and y coordinates). The coordinates were concatenated and normalized, resulting in a 42-feature vector for a single hand or 84 features per sample.

3. Model Training: KNN, Random Forest, and SVM classifiers were trained on the extracted features. The dataset was split using an 80% training / 20% testing ratio for model evaluation.

4. Testing: Real-time testing was conducted with three participants performing gestures (A-L) for both the right and left hands across all three lighting conditions. Performance was measured by average confidence scores and overall accuracy
<img width="1202" height="764" alt="image" src="https://github.com/user-attachments/assets/b00cd0e9-5fe7-4579-a454-9652ad2536e5" />


   
