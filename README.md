## Battery Impedance Analysis - NASA Li-ion Battery Dataset

# Project Overview

This project analyzes the NASA Battery Dataset, which contains data from Li-ion batteries run through different operational profiles such as charge, discharge, and impedance measurements at various temperatures. The dataset includes measurements like battery impedance, electrolyte resistance (Re), and charge transfer resistance (Rct), which provide insights into the internal parameters of batteries as they age.

Repeated charge and discharge cycles result in accelerated aging of the batteries. This project aims to visualize how these battery parameters change over time and age, providing valuable insights into the behavior of batteries as they approach their end-of-life (EOL) criteria.

# Key Parameters Analyzed

- **Battery Impedance**: The overall impedance of the battery.
- **Re (Electrolyte Resistance)**: Estimated electrolyte resistance in ohms.
- **Rct (Charge Transfer Resistance)**: Estimated charge transfer resistance in ohms.

# Steps
1. **Load the Dataset:**
   - Upload the CSV files directly into your Colab environment or link your Google Drive to access the dataset stored there.

2. **Preprocess the Data:**
   - Clean the dataset and handle missing values (e.g., using forward fill).

3. **Create Plots:**
   - Plot **Battery Impedance** over time.
   - Plot **Estimated Electrolyte Resistance (Re)** over time.
   - Plot **Charge Transfer Resistance (Rct)** over time.
