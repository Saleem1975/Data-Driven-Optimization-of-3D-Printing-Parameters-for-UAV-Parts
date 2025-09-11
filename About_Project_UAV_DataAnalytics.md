# Project: Data Analytics for Optimizing 3D Printing of UAV Parts

This repository documents a **data-driven analytics project** where all
datasets were **designed, generated, and collected in-house** through
physical 3D printing experiments. Unlike pre-cleaned or public datasets,
this project required building the entire pipeline: from **experimental
design and raw data collection** to **statistical modeling,
optimization, and visualization**.

------------------------------------------------------------------------

## 📌 Overview

The project focused on optimizing **3D printing parameters** for
unmanned aerial vehicle (UAV) parts, aiming to achieve a balance between
**low mass** and **high tensile strength**. To do so, I combined:\
- **Design of Experiments (DoE)** for structured data generation\
- **Response Surface Methodology (RSM)** for regression modeling\
- **Python-based NSGA-II Pareto front analysis** for multi-objective
optimization\
- **Visualization tools** to interpret trade-offs and parameter effects

------------------------------------------------------------------------

## 🔑 Data Analytics Contributions

-   **In-House Data Generation:** Designed and executed experiments to
    produce datasets on infill percentage, layer height, number of
    walls, and build plate temperature. Each run produced raw
    measurements for **mass** and **tensile strength**.\
-   **Data Preprocessing:** Collected raw measurements from lab
    instruments, organized them into analyzable formats, and ensured
    quality through validation tests.\
-   **Statistical Modeling:** Built regression models with strong
    predictive accuracy:
    -   **R² = 98.2%** for mass prediction\
    -   **R² = 88.5%** for tensile strength prediction\
-   **Optimization & Trade-off Analysis:** Applied **multi-objective
    optimization** (NSGA-II in Python + Minitab Response Optimizer) to
    explore the balance between competing outcomes.\
-   **Data Visualization:** Created Pareto fronts, contour plots, and
    optimizer dashboards to guide decision-making.

------------------------------------------------------------------------

## 📊 Tools & Skills Demonstrated

-   **Python**: platypus (NSGAII, Problem, Real, Integer, Solution), Matplotlib\
-   **Statistical Analysis**: Regression, interaction effects, quadratic
    modeling using (Minitab softwar)\
-   **Optimization**: Multi-objective (Pareto analysis, Response
    Optimizer)\
-   **Data Engineering**: Designing and collecting experimental data
    in-house\
-   **Data Visualization**: Communicating results with charts and plots\
-   **Validation**: Confirmed predictive models with \<5% error margins

------------------------------------------------------------------------

## 🌍 Applications

-   Demonstrates **end-to-end data analytics workflow**: from raw data
    collection → preprocessing → modeling → optimization →
    visualization.\
-   Applicable to fields where **data is not readily available** and
    must be generated, including **manufacturing, aerospace, energy, and
    healthcare**.

------------------------------------------------------------------------

## 👨‍💻 Authors

-   **Dr. Saleem Ramadan** -- Al Hussein Technical University\
-   **Dr. Mohammad Abu-Shams** -- German Jordanian University

------------------------------------------------------------------------

## 📜 License

Released under the **Creative Commons Attribution License (CC BY 4.0)**.
