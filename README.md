
# Fixed Income Modeling: Zero-Coupon Bonds and Swaption Pricing

This repository presents a comprehensive Jupyter notebook that delves into fixed income modeling, specifically focusing on zero-coupon bond pricing, forward rate derivation, and swaption pricing using the Hull-White model. Developed collaboratively by Martín Pasche and Hugo Yeremian, the notebook serves as both an educational resource and a practical toolkit for fixed income analysis.

## 📘 Notebook Overview

* **Title**: Fixed-Income-Yeremian-Pasche.ipynb
* **Authors**: Martín Pasche, Hugo Yeremian
* **Language**: Python 3
* **Libraries Used**:

  * `pandas`
  * `numpy`
  * `scipy`
  * `matplotlib`
  * `dataclasses`

## 🧾 Contents

The notebook is structured into the following sections:

### 1. Zero-Coupon Bond Pricing and Forward Rate Derivation

* Bootstrapping techniques to construct the zero-coupon yield curve from market data.
* Calculation of forward rates implied by the zero-coupon curve.
* Visualization of the term structure of interest rates.

### 2. Swaption Pricing Using the Hull-White Model

* Calibration of the Hull-White model parameters to market swaption prices.
* Pricing of European swaptions using the calibrated model.

## 🚀 Getting Started

To run the notebook locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/martinpasche/FixedIncome.git
   cd FixedIncome
   ```

2. **Install the required libraries**:

   Ensure you have Python 3 installed. Then, install the dependencies:

   ```bash
   pip install pandas numpy scipy matplotlib
   ```

3. **Launch the Jupyter Notebook**:

   ```bash
   jupyter notebook Fixed-Income-Yeremian-Pasche.ipynb
   ```


## 🤝 Collaborators

| Name             | Role                      | GitHub                                          |
| ---------------- | ------------------------- | ----------------------------------------------- |
| Martin Pasche    | Team member | [martinpasche](https://github.com/martinpasche) |
| Hugo Yeremian  | Team member     | [h-yer](https://github.com/h-yer)           |


## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
