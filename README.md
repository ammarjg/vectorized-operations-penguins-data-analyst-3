# Penguins Data Analysis

This repository contains an in-depth analysis of the Palmer Penguins dataset, a widely used dataset for data science and machine learning. The project showcases data preprocessing, feature engineering, and exploratory data analysis using Python.

---

## Dataset Description

The **Palmer Penguins dataset** provides physical measurements of three penguin species observed in Antarctica. It is an excellent alternative to the Iris dataset for learning about data analysis.

### Columns in the Dataset
- **rownames**: Row numbers for indexing.
- **species**: Species of penguins (`Adelie`, `Gentoo`, `Chinstrap`).
- **island**: The island where the penguins were observed (`Torgersen`, `Biscoe`, `Dream`).
- **bill_length_mm**: Length of the penguin's bill in millimeters.
- **bill_depth_mm**: Depth of the penguin's bill in millimeters.
- **flipper_length_mm**: Length of the penguin's flipper in millimeters.
- **body_mass_g**: Body mass of the penguin in grams.
- **sex**: Gender of the penguin (`Male`, `Female`).
- **year**: Year of observation.

---

## Key Insights

1. **Species Characteristics**:
   - The `Gentoo` species has the highest average body mass compared to `Adelie` and `Chinstrap`.
   - Flipper lengths vary significantly across species.

2. **Body Mass Distribution**:
   - Penguins' body mass is strongly correlated with flipper length and bill size.

3. **Gender-based Patterns**:
   - Males generally have larger body mass and flipper lengths than females across all species.

4. **Feature Engineering**:
   - Created derived features such as the ratio of bill length to depth, flipper length categories, and percentage differences between measurements.

---

## Project Highlights

- **Feature Engineering**:
  - Added new columns to enhance dataset usability, such as:
    - `body_mass_mean_centered`
    - `flipper_length_mm_plus_50`
    - `bill_length_to_depth_ratio`
    - `log_body_mass_g`
  - Categorized flipper length into bins (`Short`, `Medium`, `Long`) using quantile-based bucketing.

- **Exploratory Analysis**:
  - Explored relationships between species and physical characteristics.
  - Investigated gender-based differences and computed various metrics.

- **Data Preprocessing**:
  - Handled missing values.
  - Normalized key numeric columns for analysis.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/penguins-data-analysis.git
   cd penguins-data-analysis

2. Install required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn

  3. Run the Jupyter Notebook for full analysis:
     ```bash
     jupyter notebook penguins_analysis.ipynb
 
