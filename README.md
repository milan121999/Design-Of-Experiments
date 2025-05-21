# Design-Of-Experiments
This project focused on optimizing the design of a LEGO car to maximize the distance it could travel down a ramp, simulating a mini "Desert Classic Phoenix Grand Prix." Using DOE principles, we aimed to identify the most influential design factors impacting performance while keeping cost-effectiveness in mind.

## Introduction
The objective was to analyze and improve the performance of a LEGO-based race car using factorial design. We explored five design factors (wheel size, car length, width, number of wheels, and weight distribution) and evaluated their influence on the travel distance.

## Objective
* Determine the most significant factors impacting travel distance
* Maximize distance while minimizing cost
* Validate experimental setup using statistical rigor and Minitab-based modeling

## Data
Factors considered for this experiment were:

1) wheel Size 
2) Length of the car
3) Width of the car
4) Number of wheels
5) Load position

These factors were systematically manipulated to create a well-designed set of experiments.

## Minitab Implementation 
Minitab played a central role in designing and analyzing the LEGO car experiment using a full factorial 2⁵ design. It helped generate a randomized run order to eliminate bias and provided a structured platform to input the distance data collected from each trial. The software facilitated the analysis of main effects and interactions between factors such as wheel size, car length, and number of wheels. Diagnostic tools like residual plots and normal probability plots confirmed model assumptions, ensuring the accuracy of the results. Through Minitab’s regression analysis, the initial model captured significant trends and helped visualize the impact of each factor on the response variable.

In the refinement phase, Minitab was used to simplify the model by removing non-significant factors and interactions. This process highlighted key contributors to performance—specifically wheel size, car length, and their interaction. Adjusted R² values guided the model optimization, balancing complexity with predictive power. Contour and cube plots generated in Minitab made it easy to interpret how factor combinations influenced the outcome. The final model, supported by residual analysis, proved statistically sound and interpretable. Ultimately, Minitab enabled data-driven decision-making to recommend the most efficient and cost-effective LEGO car design.

## Procedure
We designed a ramp-based test environment with consistent height, angle, and surface. A full factorial 2⁵ design was implemented in Minitab, with randomized trials to reduce bias. Measurements were recorded in inches across 32 runs, and responses were analyzed for significance and interactions.

## Results and Conclusion
* Significant Factors: Smaller wheels, longer cars, and fewer wheels significantly improved performance.
* Best Configuration: Small wheels, long body, and 4-wheel setup yielded the highest travel distance.
* Model Fit: A simplified model (A, B, D, and A*B interaction) explained most of the variability (Adjusted R² ≈ 56%).
* Cost Insight: The optimal design cost $27,100, highlighting trade-offs between performance and expense.

This DOE project demonstrated that minimizing rolling resistance (via small wheels and fewer contacts) and improving stability (via longer car bodies) significantly enhance car performance. The experiment effectively showcased how statistical design methods and Minitab can guide engineering decisions in a controlled and insightful way.
