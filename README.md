# Predictive Analytics for Stock Prices

## Overview
This project aims to predict future stock prices using historical data through the application of machine learning techniques, specifically Long Short-Term Memory (LSTM) neural networks. The model is trained and evaluated on historical stock data of Apple Inc. (AAPL) obtained from Yahoo Finance.

## Features
- Data Collection: Download historical stock data using the `yfinance` library.
- Data Preprocessing: Handle missing values, create moving averages, and scale data.
- Model Development: Build and train an LSTM model to predict stock prices.
- Model Evaluation: Test the model on unseen data and visualize the predictions.
- Visualization: Plot actual vs. predicted stock prices to assess model performance.

## Libraries and Tools
- `yfinance`: For downloading historical stock price data.
- `pandas`: For data manipulation and preprocessing.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `sklearn`: For data scaling.
- `tensorflow`: For building and training the LSTM model.

## Project Structure
- `Predictive_Analytics_for_Stock_Prices.ipynb`: The main Jupyter notebook containing the entire workflow, from data collection to model evaluation.
- `README.md`: Project description and instructions.
- `requirements.txt`: List of dependencies required to run the project.

## Getting Started

### Prerequisites
Ensure you have the following libraries installed:
- `yfinance`
- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`
- `tensorflow`

You can install these libraries using pip:
```bash
pip install yfinance pandas numpy matplotlib sklearn tensorflow
```

### Running the Project
1. Clone the repository:
```bash
git clone https://github.com/your-username/Predictive-Analytics-for-Stock-Prices.git
```

2. Navigate to the project directory:
```bash
cd Predictive-Analytics-for-Stock-Prices
```

3. Open the Jupyter notebook:
```bash
jupyter notebook Predictive_Analytics_for_Stock_Prices.ipynb
```

4. Follow the steps in the notebook to execute the code.

## Methodology

1. **Data Collection**: Historical stock price data for Apple Inc. (AAPL) is downloaded from Yahoo Finance.
2. **Data Preprocessing**: 
   - Handle missing values.
   - Add moving averages (50-day and 200-day).
   - Split the data into training and testing sets.
3. **Model Development**:
   - Scale the data.
   - Create training datasets.
   - Build and train an LSTM model using TensorFlow.
4. **Model Evaluation**:
   - Prepare test data.
   - Make predictions using the trained model.
   - Visualize the actual vs. predicted stock prices.
   
## Results
The project demonstrates the ability to predict stock prices with a reasonable level of accuracy using LSTM neural networks. The visualizations provide a clear comparison between actual and predicted stock prices.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License
This project is licensed under the MIT License.

## Contact
For any questions or inquiries, please contact me at:
- **Email**: mostafasamirdarahem@gmail.com
- **LinkedIn**: [Mostafa Darahem](https://www.linkedin.com/in/mostafa-darahem/).

