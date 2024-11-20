# Smart-Grid-Stability
![download](https://github.com/user-attachments/assets/e432f695-2eda-4d45-a9fd-65288667791d)


# **Introduction to Smart Grid Technology and Grid Stability Analysis**

The integration of renewable energy sources into modern electrical grids marks a revolutionary shift in the global energy landscape. Unlike traditional fossil fuel-based systems, renewable energy provides a sustainable and eco-friendly solution to the ever-growing energy demands of modern societies. However, this transition is not without challenges. 

A critical aspect of smart grid technology is maintaining stability in a system characterized by fluctuating energy generation and consumption patterns. Grid frequency, a fundamental metric in alternating current (AC) systems, plays a pivotal role in monitoring this stability. Deviations in frequency signify imbalances between energy supply and demand, which must be addressed to prevent disruptions. This dynamic management of supply-demand equilibrium, influenced by economic parameters like energy pricing, forms the cornerstone of smart grid systems.


# **Modeling and Predicting Grid Stability**

To analyze grid stability, researchers have developed models such as the Decentralized Smart Grid Control (DSGC) system. This differential equation-based approach leverages parameters such as power balance, reaction times of grid participants, and price elasticity to determine whether a system is stable or unstable. However, these mathematical models often rely on simplifying assumptions, which may limit their practical applicability.

An alternative approach involves leveraging machine learning to predict grid stability. By generating a synthetic dataset from simulations of a reference 4-node star grid architecture, researchers have trained learning models to classify grid states as "stable" or "unstable." These simulations provide a robust dataset for training, consisting of key features such as reaction times, power generation and consumption, and price elasticity coefficients for each node in the grid. The dataset enables machine learning models to generalize and predict stability outcomes without relying on restrictive assumptions.

![image](https://github.com/user-attachments/assets/37f14efc-d50e-42e3-a49d-a509e86f2241)

***Objectives of This Study***

The primary aim of this study is to advance grid stability predictions by applying a cutting-edge machine learning technique: the CatBoost algorithm. CatBoost, a gradient-boosting framework optimized for categorical and numerical data, offers the flexibility to perform both classification and regression tasks. Specifically, the goals are:

Binary Classification: To predict whether the grid is *"stable"* or *"unstable"* based on the dataset's predictive features. This will utilize the stabf categorical label.

Regression Analysis: To predict the precise stability score *(stab)* to gain a deeper understanding of the stability dynamics.
By utilizing the synthetic "Electrical Grid Stability Simulated Dataset," this study focuses on building high-performing predictive models that can contribute to smarter and more resilient grid management systems. 

The dataset, enriched by augmentation techniques, allows for a diverse exploration of grid behavior under varying scenarios. SInce there are no missing values and all features being numerical, this dataset provides an ideal starting point for deploying machine learning models.
