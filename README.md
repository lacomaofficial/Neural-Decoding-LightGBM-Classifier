# Neuroimaging Decoding with LightGBM Classifier
In this project, we'll train a light gradient-boosting machine classifier to decode brain signals using the Haxby dataset.


Here's a quick overview:

1. **Data Preparation**: We fetch the Haxby dataset, set up paths, load functional MRI data, and mask and preprocess it for analysis.

2. **LightGBM Modeling**: We train and fine-tune a LightGBM classifier to predict cognitive categories. Our model excels in identifying faces and rest states.

3. **Performance Assessment**: We evaluate the model's performance

 - **Classification Report**:
   - "Face" predictions show the highest precision (86%).
   - "Rest" predictions also have high precision (86%).
   - "Scrambledpix" and "House" predictions exhibit comparable precision (86% and 79% respectively).
   - "Shoe" predictions display the lowest precision (65%).

 - **Summary**: The model excels in "face" and "rest" prediction, while "shoe" classification can be enhanced.

4. **Feature Importance Visualization**: Visualizing feature importances, we unveil key brain regions driving our model's predictions.

5. **Project Conclusion**: Our model was great at recognizing faces and rest states, with room to improve on shoes. By visualizing key brain areas, we fused data science and neuroscience, uncovering cognitive insights from brain data.




![Screenshot 2](https://github.com/lacomaofficial/Neuro-Decoding-LightGBM-Classifier/assets/132283879/597fbc1b-68d5-4514-b244-91f3320819be)

