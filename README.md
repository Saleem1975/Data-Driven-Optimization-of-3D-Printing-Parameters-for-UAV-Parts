# Data Analytics for Optimizing 3D Printing of UAV Parts

This project uses data analytics to **optimize** 3D printing parameters for UAV components, targeting **longer flight** times by achieving a balance of **low weight** and **high strength**. In-house data were generated using response surface methodology (**DOE**) to build two** regression models**: one for **strength** and one for **mass**. Treated as conflicting objectives—maximize strength, minimize mass—they were solved with the **NSGA-II algorithm** to find optimal **trade-offs**. The result is a lightweight, durable UAV body suitable for applications such as PV field monitoring, demonstrating a complete pipeline from data generation to visualization.
## Pipeline
`Data Generation → Preprocessing → Modeling → Optimization → Visualization`

------------------------------------------------------------------------

## 📌 Overview

-   **Goal:** Achieve UAV parts that are both lightweight and strong.\
-   **Methods:** Design of Experiments (DoE), Response Surface
    Methodology (RSM), regression modeling, and **Python-based NSGA-II
    multi-objective optimization**.\
-   **Key Outcomes:**
    -   R² = 98.2% for mass prediction\
    -   R² = 88.5% for tensile strength prediction\
    -   Optimal balance achieved at **47.08 MPa tensile strength** and
        **1.60 g mass**.

------------------------------------------------------------------------

## 🔑 Skills Demonstrated

-   **Data Engineering:** Designing and collecting experimental data.\
-   **Statistical Modeling:** Regression, response surface analysis, and DOE.\
-   **Optimization:** Multi-objective trade-off analysis with NSGA-II.\
-   **Visualization:** Pareto fronts, contour plots, regression plots.\
-   **Tools:** Python (Matplotlib,platypus) and Minitab.

------------------------------------------------------------------------

## 📂 Repository Contents

-   **About_Project_UAV_DataAnalytics.md** -- Detailed case study.\
-   **/data** -- Minitab file containing Raw dataset along with the analysis.\
-   **/scripts** -- Python script for multi-objective optimization\
-   **/figures** -- Charts and plots illustrating results.

------------------------------------------------------------------------

## 👨‍💻 Authors

-   **Dr. Saleem Ramadan** -- Al Hussein Technical University\
-   **Dr. Mohammad Abu-Shams** -- German Jordanian University

------------------------------------------------------------------------

## 📜 License

Released under the **Creative Commons Attribution License (CC BY 4.0)**.
