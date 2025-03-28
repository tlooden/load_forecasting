# Load Forecasting Project

This toy project focuses on developing and implementing load forecasting models for electrical power systems. The project is structured to analyze historical weather and load data and use gradient boosting to forecast future electricity demand. Individual regression and classifier models are learned for each forecasting window, enabling straightforward scope expansion and timewindow-specific feature learning.

## Getting Started

### Option 1: Using pip
1. Clone this repository
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the main notebook `code/load_forecasting.ipynb` to view the analysis

### Option 2: Using conda
1. Clone this repository
2. Create and activate the conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate load_forecasting
   ```
3. Open the main notebook `code/load_forecasting.ipynb` to view the analysis

## Project Contents

- **Code**: Contains the main implementation in Jupyter notebook format
- **Data**: Historical load data 

## Usage

The main analysis is contained in the Jupyter notebook `code/load_forecasting.ipynb`. This notebook includes:
- Data loading and preprocessing
- Feature engineering
- Model development
- Performance evaluation
- Visualization of results

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is proprietary 

