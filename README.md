
Transformer Fault Detection & Visualization

This project focuses on analyzing transformer sensor data to understand and visualize **alarm conditions** and operational behavior using Python (Pandas, Seaborn, Matplotlib) in Google Colab.



## File Structure

- `transformer_fault.ipynb`: Colab notebook containing the full code for importing, analyzing, and visualizing transformer alarm data.

## Objective

The goal of this project is to:
- Visualize key transformer alarm indicators such as:
  - OTI_A: Oil Temperature Indicator Alarm
  - WTI_A: Winding Temperature Indicator Alarm
  - ATI_A: Ambient Temperature Indicator Alarm
  - MOG_A: Magnetic Oil Gauge Alarm
- Understand the distribution and severity of faults through:
  - Count plots
  - Pie charts
  - Correlation heatmaps (if included)

## Technologies Used

- **Python 3**
- **Google Colab**
- **Pandas** – data loading and manipulation
- **Seaborn** – statistical visualizations
- **Matplotlib** – plotting charts
- **NumPy** – numerical operations

---

##  Visualizations

The notebook includes visual analysis for:
- Alarm signal counts (`countplot`)
- Proportional alarm status (`pie chart`)
- Correlation (if implemented)
- Timestamp sorting and sensor-level insights



##  Future Work (Suggestions)

- Add time-series analysis for each sensor
- Use ML models for predictive fault classification
- Merge with real-time transformer logs for deployment

---

##  Getting Started

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload your transformer CSV file
3. Run all cells to visualize fault patterns

---

## 🧑‍💻 Author

**Mudit Lodha**  
Electrical Engineering  
IIT (BHU) Varanasi  
[GitHub Profile](https://github.com/MuditLodha)

