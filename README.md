# Dynamic Pricing Engine for Urban Parking Spaces

This project simulates a real-time dynamic pricing engine for 14 urban parking spaces. Static pricing often leads to overcrowding or underutilization of parking lots. By analyzing real-time data streams and using demand modeling, this engine adjusts parking prices intelligently — improving space utilization and revenue.

Built as part of a Summer Analytics Course, this project demonstrates the practical application of Python, Pandas, NumPy, and data science concepts in solving urban infrastructure problems.

---

## Tech Stack

- Python (Core programming)
- Pandas & NumPy (Data manipulation, feature engineering)
- Bokeh (Interactive data visualization)
- Google Colab (Notebook-based development)
- (Optional): Pathway (for stream processing in advanced extensions)

---

## Project Architecture and Workflow

```mermaid
graph TD
    A[Raw Dataset: 14 Parking Lots] --> B[Data Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Model 1: Baseline Linear Pricing]
    C --> E[Model 2: Demand-Based Pricing]
    D & E --> F[Pricing Output]
    F --> G[Bokeh Visualization]
