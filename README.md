# California Housing Prediction

Predict California housing prices using Linear Regression. This project leverages the **California Housing Dataset** (Kaggle) to estimate median house values based on features like income, house age, rooms, population, and proximity to the ocean. It includes data cleaning, exploratory analysis, feature selection, model training, evaluation, and visualization of predicted vs actual values.

## Dataset
Key features:
- `longitude` / `latitude`: Geographic coordinates
- `housingMedianAge`: Median house age in a block
- `totalRooms` / `totalBedrooms`: Count of rooms and bedrooms
- `population` / `households`: Residents and households in a block
- `medianIncome`: Median household income (in $10k)
- `medianHouseValue`: Target variable (USD)
- `oceanProximity`: House location relative to the ocean  
Link: [Kaggle California Housing](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Setup & Usage
```bash
# Clone the repository
git clone https://github.com/abderrazakmahiii/California-Housing-Prediction-using-Linear-Regression.git
cd Housing

# Install dependencies
pip install -r requirements.txt
> Make sure you have Python 3.x installed.

## Usage
# Run the main script to train and test the Linear Regression model
python price_prediction.ipynb

The script will:
- Load and preprocess the dataset
- Train the Linear Regression model
- Evaluate the model's performance

## Results
The model predicts California housing prices with reasonable accuracy. Key results include:
- Performance metrics on test data
- Visualization comparing predicted and actual prices
- Insights on feature importance

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for improvements.

## License
This project is open-source and available under the MIT License.
```
