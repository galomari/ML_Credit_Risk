# Lauki Finance: Credit Risk Modelling

Lauki Finance is a credit risk modelling application designed to help users evaluate the risk of a loan based on various parameters. This app provides an intuitive user interface for entering loan details, borrower profiles, and other financial metrics to calculate the potential risk associated with a loan.

---

## Features

- **Dynamic Input Fields**: Enter and adjust parameters like age, income, loan amount, loan tenure, and more.
- **Loan to Income Ratio**: Automatically calculates the ratio based on loan amount and income.
- **Risk Calculation**: Provides a risk score based on delinquency ratio, credit utilization, and other key metrics.
- **Customizable Loan Types**: Choose between secured or unsecured loans and specify the loan purpose.
- **Real-Time Insights**: Get immediate feedback on the potential risk associated with a loan profile.

---

## Demo



---

## Installation

To run the app locally, follow these steps:

### Prerequisites

1. Python 3.10 or later is required.
2. Ensure `pip` is installed and updated:
   ```bash
   python -m pip install --upgrade pip
   ```

### Clone the Repository

```bash
git clone https://github.com/galomari/ML_Credit_Risk.git
cd ML_Credit_Risk
```

### Install Dependencies

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

### Run the App

Start the Streamlit app:

```bash
streamlit run main.py
```

Open the provided local URL in your web browser to access the app.

---

## Usage

1. Enter values for the following parameters:

   - Age
   - Income
   - Loan Amount
   - Loan Tenure (months)
   - Average DPD (Days Past Due)
   - Delinquency Ratio
   - Credit Utilization Ratio
   - Open Loan Accounts
   - Residence Type (Owned/Rented)
   - Loan Purpose (e.g., Education, Home Improvement)
   - Loan Type (Secured/Unsecured)

2. Click the **Calculate Risk** button to compute the loan risk score.

3. Analyze the results displayed on the screen to make informed decisions.

---

## File Structure

```plaintext
ML_Credit_Risk/
├── main.py                # Main application script
├── requirements.txt       # Python dependencies
├── .streamlit/            # Streamlit configuration
│   └── config.toml
├── artifacts/             # Any pre-trained models or intermediate files
├── README.md              # Project documentation
└── image.png              # Screenshot of the app
```

---

## Requirements

The project requires the following Python libraries:

- `numpy`
- `pandas`
- `streamlit`
- `joblib`

These are included in the `requirements.txt` file.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Describe your changes"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

For any questions or feedback, please contact the project maintainer:

- **Name**: Ghaith M. Alomari
- **Email**: [Insert Email Here]
- **GitHub**: [@galomari](https://github.com/galomari)

---

## Acknowledgements

- Streamlit for providing an excellent framework for building interactive web apps.
- Contributors to the Python libraries used in this project.

---

Enjoy using the Lauki Finance Credit Risk Modelling app!

