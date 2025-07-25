## Food Recognition & Calorie Estimation Datasets

This repository contains three datasets used for training and evaluating models for food recognition and calorie estimation tasks. The datasets focus on 10 commonly consumed Goan food items: **Dosa, Poha, Samosa, Bhaji, Idli, Rice Bhakri, Upma, Dhokla, Medu Vada, and Roti**.


##  1. Food_Classification_Unannotated_Dataset

- **Purpose**: Used for training classification models like **InceptionV3**, **VGG19**, and a **Custom CNN model**.
- **Annotation**: Not annotated (image-level classification only).
- **Split**:
  - Training: 70%
  - Validation: 15%
  - Testing: 15%


##  2. Food_Detection_Annotated_Dataset

- **Purpose**: Used for training detection models like **YOLOv8**.
- **Annotation**: Instance-based segmentation using **Roboflow**.
- **Supports**: Object detection with bounding boxes and segmentation masks.
- **Split**:
  - Training: 70%
  - Validation: 15%
  - Testing: 15%
- **Access Dataset**: [Download from Roboflow](https://app.roboflow.com/ds/f5U8U8g9ca?key=CIwpEFTqYM) 


##  3. Nutrition Dataset (NutritionData.csv)

- **Purpose**: Used for **calorie estimation** based on predicted food type and volume.
- **Format**: CSV file where each row represents a food item with the following nutritional attributes:
  - Carbohydrates (g)
  - Protein (g)
  - Fat (g)
  - Sugar (g)
  - Fiber (g)
  - Density (g/cm³)
- These values are used to compute total calories using estimated food volume.


##  License

This dataset is licensed under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/). You are free to use, share, and adapt the material with attribution.


##  Acknowledgements

Food detection annotations were created using [**Roboflow**](https://roboflow.com). The nutritional values were curated for research purposes in calorie estimation.



