# Sign Language Recognition Under Varying Lighting Conditions: A Comparative Analysis of KNN, Random Forest,and SVM

Experimental tests prove the strength and performance differences of these models, showing their strengths and weaknesses. Given good lighting conditions and a plain background, the overall accuracy results show that KNN shows the highest overall accuracy in all lighting conditions, with up to 95% in sunlight and 89.16% in darkness. 

# Methodology and Research Design
1. Dataset: A subset of 1,000 images from the ASL (American Sign Language) Alphabet Dataset (A to L) was used. Images were explicitly collected or selected to cover three lighting conditions: dim, moderate, and sunlight-exposed.

2. Feature Extraction: MediaPipe was employed to detect and extract 21 hand landmarks per hand (x and y coordinates). The coordinates were concatenated and normalized, resulting in a 42-feature vector for a single hand or 84 features per sample.

3. Model Training: KNN, Random Forest, and SVM classifiers were trained on the extracted features. The dataset was split using an 80% training / 20% testing ratio for model evaluation.

4. Testing: Real-time testing was conducted with three participants performing gestures (A-L) for both the right and left hands across all three lighting conditions. Performance was measured by average confidence scores and overall accuracy
   4.1 <img width="1202" height="764" alt="image" src="https://github.com/user-attachments/assets/785ed4b1-1224-47a4-8332-d656719b3f8f" />Asl sign for Alphabet A for KNN Model in Moderate lighting
   4.2 <img width="1222" height="774" alt="image" src="https://github.com/user-attachments/assets/c5e63b0f-e4cd-4a8c-9aa8-38681d25857d" />Asl sign for Alphabet C for SVM Model in Moderate lighting
   4.3 <img width="1198" height="747" alt="image" src="https://github.com/user-attachments/assets/daf30dd5-a260-4a9f-a3db-650824137871" />Asl sign for Alphabet D for Random Forest Model in Moderate lighting 

5. Results
 <img width="450" height="277" alt="image" src="https://github.com/user-attachments/assets/a8c2c971-4ada-42ca-8d13-41442ab1b3dc" /> Result table under Dark conditions
<img width="865" height="621" alt="image" src="https://github.com/user-attachments/assets/27a7b020-74ed-444d-b235-0ce6102dfe96" />Result table under Sunlight conditions
<img width="865" height="640" alt="image" src="https://github.com/user-attachments/assets/cfeee60d-36ff-473d-8436-927602047560" />Result table under Moderate conditions

6. Overall Model Accuracy
   <img width="864" height="247" alt="image" src="https://github.com/user-attachments/assets/f6d2d916-d827-4534-92e6-455a6ef666ec" />

7. Conclusion: According to the findings, KNN performed better than both SVM and Random Forest models under the three lighting environments with higher stability and responsiveness towards environmental changes. The best performance was recorded during sunlight with an accuracy of 95.00%, while the worst was achieved during moderate illumination for SVM with an accuracy of 64.95%. From these findings, it is inferred that KNN is the best model among those evaluated for use in real-time recognition of static hand signs in the absence of aids or exterior enhancement 
   

    


   
