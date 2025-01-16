# Car Price Prediction in Israel

This project demonstrates predictive modeling using car price data from two sources: Yad2 and Autoboom. The data was previously collected and prepared, and this repository focuses on preprocessing, modeling, and evaluating car price predictions.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- Demonstrates predictive modeling on car price datasets from Yad2 and Autoboom.
- Uses separate machine learning models for each dataset.
- Provides insights into price prediction for vehicles in Israel.

## Project Structure

```
car-price-prediction-israel
│
├── data/                      # Data storage (optional; no raw data if large files)
│   ├── yad2/                  # Processed or sample data from Yad2
│   └── autoboom/              # Processed or sample data from Autoboom
│
├── notebooks/                 # Jupyter notebooks for both datasets
│   ├── yad2_preprocessing_modeling.ipynb     # Notebook for Yad2 data processing and modeling
│   ├── autoboom_preprocessing_modeling.ipynb  # Notebook for Autoboom data processing and modeling
│
├── models/                    # Saved model files
│   ├── yad2_model.pkl         # Trained model for Yad2 data
│   ├── autoboom_model.pkl     # Trained model for Autoboom data
│
├── README.md                  # Main project documentation
├── requirements.txt           # Dependencies
├── .gitignore                 # Ignore unnecessary files
└── LICENSE                    # License for your project (if applicable)
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction-israel.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-price-prediction-israel
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running Notebooks

Open and run the Jupyter notebooks for data preprocessing and modeling:

- `notebooks/yad2_preprocessing_modeling.ipynb`
- `notebooks/autoboom_preprocessing_modeling.ipynb`

These notebooks include steps for preprocessing the data and building predictive models.

## Contributing

1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

See `CONTRIBUTING.md` for more details (if applicable).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Tiurin Mikhail - [LinkedIn]([https://www.linkedin.com/in/tiurin-mikhail](https://www.linkedin.com/in/mikhail-tiurin-775a752a7/))  
- Email - tyurin.mihails@gmail.com
