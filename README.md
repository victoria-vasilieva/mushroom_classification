# Mushroom Classification: Edible or Poisonous?

🍄 Predict whether a mushroom is edible or poisonous using machine learning with domain-specific feature engineering.

## Project Overview

Each mushroom season, thousands of people in Germany are hospitalized from mushroom poisoning. This project aims to build a machine learning model that predicts mushroom edibility based on physical features like cap color, shape, bruises, and population patterns.

The main model is a Random Forest classifier trained on engineered features combining research and domain knowledge to detect subtle cues often missed by simpler methods.

## Key Features

- Counts of “dangerous” vs “safe” colors  
- Cap shape and bruising combinations  
- Population and color pattern interactions  

## Results

- Nearly 90% of edible mushrooms correctly identified  
- Zero poisonous mushrooms misclassified

<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/cd3f571c-296b-45ee-8a88-3f51b4570741" />


## Repository Structure

mushroom-classification/<br />
│<br />
├── [README.md](https://github.com/victoria-vasilieva/mushroom_classification/blob/main/README.md)<br />
├── [mushroom_classification.ipynb](https://github.com/victoria-vasilieva/mushroom_classification/blob/main/mush_classification.ipynb) # Jupyter notebook with code and results<br />
├── [mush_train.csv](https://github.com/victoria-vasilieva/mushroom_classification/blob/main/mush_train.csv) # Dataset file <br />
└── [requirements.txt](https://github.com/victoria-vasilieva/mushroom_classification/blob/main/requirements.txt) # Python dependencies

## Installation

1. Clone the repository
```
git clone https://github.com/yourusername/mushroom-classification.git
cd mushroom-classification
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the notebook
   
Open [`mushroom_classification.ipynb`](https://github.com/victoria-vasilieva/mushroom_classification/blob/main/mush_classification.ipynb) with Jupyter or Google Colab

## License

This project is licensed under the MIT License.
