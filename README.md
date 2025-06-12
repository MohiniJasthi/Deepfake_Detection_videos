# Deepfake Detection Using Temporal Modeling

This project focuses on detecting deepfake videos by leveraging temporal modeling techniques to improve detection accuracy over frame-based models.

---

## Key Takeaways

- **Frame-based models alone are inadequate:**  
  Deepfake alterations often produce small inconsistencies that are not visible in individual frames but become apparent when viewed over time. Therefore, incorporating temporal modeling is essential for improving detection accuracy.

- **Data augmentation dramatically improves generalization:**  
  Techniques such as random rotations, brightness adjustments, and horizontal flips help the model become more robust against variations in facial expressions, lighting, and positioning, enhancing performance on unseen data.

- **Prioritizing recall for deepfakes is crucial in real-world applications:**  
  In scenarios like media verification, legal evidence authentication, and misinformation detection, missing a fake video (false negative) can have serious consequences. Hence, optimizing the model for high recall on the deepfake class is a key design goal.

---

## Future Work

There are several promising avenues to enhance the current approach:

- **Exploring more complex architectures such as 3D CNNs:**  
  3D convolutional neural networks can simultaneously capture spatial and temporal features directly from videos, potentially improving performance beyond the current CNN + LSTM pipeline.

- **Integrating Attention Mechanisms:**  
  Attention models could allow the system to focus on specific facial regions (e.g., lips, eyes, jawline) where manipulations are most evident, further boosting detection accuracy.

- **Expanding the dataset:**  
  Incorporating a wider variety of deepfake generation techniques and more diverse datasets will improve model robustness against emerging manipulation methods and enhance real-world applicability.

---

## Usage

*Include instructions on how to run your project, e.g.:*

1. Clone the repository
   ```bash
   git clone https://github.com/MohiniJasthi/Deepfake_detection_videos.git 
   cd Deepfake_detection_videos
2. Install dependencies: `pip install -r requirements.txt` 
---
