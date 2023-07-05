#  Low-Power Computer-Vision-based Pedestrian Counting Research

This repository contains the code and documentation for the Low-Power Computer-Vision-based Pedestrian Counting research project. The project aims to develop a low-power computer vision system for accurately counting pedestrians in urban environments. The system utilizes advanced computer vision techniques, including Gaussian Process Regression (GPR) and YOLOv5 object detection, to achieve real-time pedestrian counting with low energy consumption.

## Introduction

The utilization of computer vision techniques for pedestrian counting presents an imperative tool for city planners and management agencies to comprehend pedestrian flows. This data facilitates informed decision-making processes and aids in averting crowd-related incidents. The information gained through computer vision monitoring also provides invaluable insights for market research by assessing the flow and busyness of commercial areas. Moreover, a real-time pedestrian counting system can optimize urban layout and enhance public transportation systems. The deployment of advanced computer vision techniques for pedestrian counting provides a path for long-term benefits.

![Data](https://github.com/Subarashiihibi/LPCV_CAP_Deliverables/blob/main/img/device.jpeg "Coral Dev and Camera")

## Data

The data collection methodology for this research project is comprehensive and built upon the principles applied in similar research endeavors. The selection of data collection locations was guided by strategic location selection processes inspired by previous research. Pedestrian dynamics models, including statistical-physical approaches such as fluid dynamics, gas dynamics, and social force models, were taken into account to choose busier neighborhood entrances for data collection.

The data collection locations were selected based on considerations of land use, population density, and specific requirements for the shooting environment. The chosen locations include Elmer Holmes Bobst Library, 370 Jay Street, John A. Paulson Center, and Whole Foods Market at 4 Union Square South. These locations provide essential geographical and demographic data that enhance the precision of pedestrian traffic simulations and analysis.

![locations](https://github.com/Subarashiihibi/LPCV_CAP_Deliverables/blob/main/img/spots.png "Locations")

Data collection was carried out continuously for a month at the selected locations, from 10 a.m. to 8 p.m. Videos were captured at frame rates between 15 and 30 FPS and at a resolution of 640 x 480 pixels. The data collection apparatus comprised an edge device (Coral Dev Board), a USB camera, a power source, and data cables. Data was directly saved on the board, creating CSV files for subsequent analysis.

![Data](https://github.com/Subarashiihibi/LPCV_CAP_Deliverables/blob/main/img/video.jpeg "Video Sample")

## Data Ethics

Privacy considerations are of utmost importance when deploying edge devices for monitoring and predicting pedestrian counts. Precautions have been integrated into the system to minimize potential privacy violations. The system utilizes a low-resolution camera that cannot capture distinct facial features, reducing the possibility of unauthorized identification. The algorithm used for pedestrian counting is based on Gaussian Process Regression (GPR) models, which only provide outputs related to pedestrian counts and do not collect personal information. The data collected is strictly used for monitoring pedestrian traffic patterns and adheres to guidelines for ethical data collection and privacy preservation.

## Methodology

The system utilizes Gaussian Process Regression (GPR) for pedestrian counting. GPR is a powerful and flexible Bayesian non-parametric approach used for regression tasks. It models complex and non-linear relationships between variables by treating the underlying relationship as a distribution over functions. The GPR model uses training data to learn the mean and covariance structure of the target variable and provides predictions based on observed data.

The system also employs YOLOv5 (You Only Look Once version 5), a state-of-the-art object detection algorithm. YOLOv5 offers improved speed, accuracy, and versatility for real-time object detection tasks. It can detect and localize objects within images or videos with remarkable precision. The system leverages the power of YOLOv5 to address the object detection challenge in the pedestrian counting domain.

To assess the performance of the algorithm, a comparison is made with the State-of-the-Art (SOTA) computer vision model for counting pedestrians. Mean Absolute Percentage Error (MAPE) is used as a metric to evaluate the difference between the two series of outputs. The comparison helps optimize the algorithm to ensure low power consumption and optimal results.

## Results

The project includes video recordings captured with the Coral Dev Board, which can be used for testing the effectiveness and performance of the edge device. A comparison is made between the outputs from the LPCV device and the SOTA model to evaluate the accuracy of the algorithm. The results are measured using MAPE to assess the difference between the two series of outputs.

The project also features an LPCV dashboard prototype that provides information on pedestrian counting distribution, location maps, and cumulative pedestrian counting distribution. The dashboard offers a visualization of pedestrian flow patterns and can be further enhanced with real-time data updates from the edge device for more accurate analysis.

![Dashboard](https://github.com/Subarashiihibi/LPCV_CAP_Deliverables/blob/main/img/dashboard.jpg "Dashboard Prototype")

## Application

The research project has the potential to serve as the foundation for numerous transformative applications influencing the future of urban living. The low-power computer vision system developed in this project can be applied in various domains, including:

A. Safer and healthier commuting: The system can contribute to understanding factors that discourage walking to school, such as safety concerns, and inform targeted policies and interventions to promote healthier commuting habits among school-going children and their parents.

B. Environmental management: By collaborating with air quality and weather sensors, the system can provide insights into the relationships between traffic levels, flow, and air quality, leading to informed environmental policy decisions.

C. Urban planning and regeneration: The system can be an analytical ally in designing effective urban regeneration strategies by delivering quantifiable and real-time data on the impact of these strategies.

D. Transportation logistics and stakeholder communication: The system can identify and study low-traffic neighborhoods, providing insights into their effects on residents' lives, local economies, and logistics transportation. This information enhances stakeholder communication and enables data-driven decision-making processes.

The project contributes to creating safer, more efficient, and more sustainable urban environments by offering accurate and easily accessible data.

## Recommendations

Based on the findings and challenges identified in the research, the following recommendations are proposed for future work:

A. Battery Enhancement: Further research should explore optimizing the use of solar power to extend the battery life of the devices. This includes developing adaptive power management systems and exploring efficient energy storage solutions.

B. Camera Customization: Future research should consider developing or customizing cameras better suited to the project's requirements. Customized cameras should offer higher resolution, wider adaptability, and reduced power consumption.

C. Model Optimization: Integration of unsupervised and generative models, in addition to supervised learning algorithms, should be explored to cut down initial investment and enhance adaptability to complex environments.

D. Data Collection and Analysis: Expand the deployment of the device to different locations and develop more sophisticated data analysis and visualization techniques to gain a comprehensive understanding of pedestrian flow patterns.

These recommendations aim to improve the system's performance, energy efficiency, and data analysis capabilities.

## Conclusion

The Low-Power Computer-Vision-based Pedestrian Counting research project has developed an innovative system for monitoring and analyzing pedestrian flows in urban environments. The system's real-time data collection and analysis capabilities provide valuable insights for urban planning, transportation management, and environmental policy decisions. The project's findings highlight the potential impact of advanced urban technology and contribute to creating safer, more efficient, and sustainable urban environments.

We hope that this repository serves as a valuable resource for researchers and practitioners interested in low-power computer vision systems and pedestrian counting applications.
