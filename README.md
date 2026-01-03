# EcoLoop AI: A gamified waste segregator using Google AI.
 AI Integration
This project is powered by a custom-trained model via **Google Teachable Machine**. 

- **Model Training:** Trained using image samples of Plastic, Paper, and Metal.
- **Inference Engine:** The model is loaded into the app using **TensorFlow/Keras** for real-time waste classification.
- **Image Processing:** Uses **Pillow (PIL)** to resize and normalize camera frames before they are analyzed by the AI.
