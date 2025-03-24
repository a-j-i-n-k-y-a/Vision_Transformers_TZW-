# Vision Transformer for Waste Classification (TrashNet Dataset)

## Overview
This project utilizes a Vision Transformer (ViT) model to classify waste materials using the TrashNet dataset. The goal is to develop an efficient deep learning model that can accurately distinguish different types of waste, aiding in automated waste segregation for sustainable waste management in Team Zero Waste.

## Dataset
The TrashNet dataset consists of images categorized into six classes:
1. **Cardboard**
2. **Glass**
3. **Metal**
4. **Paper**
5. **Plastic**
6. **Trash** (miscellaneous waste)

Each image in the dataset is labeled according to its category, making it suitable for supervised learning tasks.

## Model Architecture
The project employs a **Vision Transformer (ViT)**, a deep learning architecture that applies self-attention mechanisms to image classification. Unlike traditional CNNs, ViTs process images as sequences of patches, capturing global dependencies effectively.

### Key Features:
- **Pretrained ViT Model:** Uses a pretrained ViT model (e.g., ViT-B/16 from Hugging Face or TensorFlow) for transfer learning.
- **Fine-tuning on TrashNet:** The model is fine-tuned on the TrashNet dataset to optimize classification accuracy.
- **Data Augmentation:** Techniques such as random cropping, flipping, and normalization are applied to enhance model generalization.
- **Optimization:** Uses AdamW optimizer with learning rate scheduling.
- **Evaluation Metrics:** Accuracy, precision, recall, and F1-score are used to assess performance.

## Future Improvements
- **Model Optimization:** Further fine-tuning for better performance.
- **Real-world Deployment:** Integrating the model into IoT waste sorting systems.
- **Data Augmentation:** Expanding the dataset to improve robustness.

## Contributors
- **Ajinkya** – Team Zero Waste, IIT Bombay
- Team Members

## License
This project is licensed under the MIT License.

---
For any questions or contributions, feel free to reach out or raise an issue in the repository!

