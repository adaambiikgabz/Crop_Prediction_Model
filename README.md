# Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

This project aims to assist farmers in selecting the best crops for their fields using machine learning techniques. By analyzing soil metrics such as nitrogen, phosphorous, potassium levels, and pH value, the project predicts the optimal crop for a given field.

## Dataset
The dataset `soil_measures.csv` contains the following columns:
- **N**: Nitrogen content ratio in the soil
- **P**: Phosphorous content ratio in the soil
- **K**: Potassium content ratio in the soil
- **ph**: pH value of the soil
- **crop**: categorical values representing various crops (target variable).

## Project Structure
- `soil_measures.csv`: Dataset containing soil metrics and crop labels.
- `crop_prediction.ipynb`: Jupyter Notebook containing the machine learning model implementation.
- `README.md`: This file, providing an overview of the project.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries (listed in the notebook)

## Usage
1. Ensure you have Python and Jupyter Notebook installed on your system.
2. Install the required libraries by running `pip install -r requirements.txt`.
3. Open `crop_prediction.ipynb` in Jupyter Notebook.
4. Follow the steps outlined in the notebook to explore the data, build the classification model, and evaluate its performance.
5. Modify the code or experiment with different machine learning algorithms as needed.
6. After finalizing your changes, save the notebook.

## License
This project is licensed under the [MIT License](LICENSE).
