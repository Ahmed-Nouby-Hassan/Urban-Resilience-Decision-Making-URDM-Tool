# Urban Resilience Decision-Making Tool (URDM)
Urban Resilience Decision Making supports early-stage prefeasibility comparison of energy and green infrastructure resilience strategies for buildings and neighborhoods. It helps stakeholders explore objectives, compare strategies, and identify priorities for deeper analysis in later design stages.

Four decision-making aspects are considered. First and second, strategies contributions to resilience capacities and objectives is considered as strategies differ in their benefits or concerns for long- and short-term capacities and for energy and thermal resilience objectives.

<img width="5007" height="766" alt="08 - Copy" src="https://github.com/user-attachments/assets/e16fdc04-57ba-4230-bec1-3e70302c0430" />

<img width="5201" height="1709" alt="09 - Copy" src="https://github.com/user-attachments/assets/80040780-cee0-4da7-8405-9edd00d54703" />

Third, the characteristics of strategies represented in technical, economic, environmental, and social dimensions are also considered.

<img width="5915" height="878" alt="10 - Copy" src="https://github.com/user-attachments/assets/ab6da159-8e40-443c-bd0e-34cd61d94f0f" />

Fourth, strategies interact together in the larger resilience network. Two strategies can enhance the performance of each other in synergy or hinder one another in conflict. Finally, resilience indicators are performance metrics used to compare between strategies.

<img width="5916" height="636" alt="11 - Copy" src="https://github.com/user-attachments/assets/0e11deda-c726-4515-b03a-b9b06eed7a86" />

The tool integrates probabilistic simulations for resilience capacities and objectives as well as strategies dimensions. Network analysis theory is used for strategies interactions. Simplified physics-based equations and simulations are used for resilience indicators. More details about the methodology can be found in the thesis, kindly contact the author.
This guide provides step-by-step instructions on how to use the tool.
The tool involves simple steps of user input, background processes, and results generation. The tool utilizes Python-based desktop application development approach. Initially, the user selects the urban level (building and neighborhoods) and project type (new or existing) from two drop down lists. According to these inputs, three different modules appear.

# Module 1: Strategy Comparative Assessment Module
Module 1, strategy comparative assessment module, represents the user input of building level existing project. The goal is to compare a proposed strategy with an existing one in a retrospective process, bringing performance metrics in early decision-making. From the strategies database, the user select the baseline strategy they want to compare to, alternative strategies, and resilience indicators to be included in the analysis. From the module database, weather scenarios and coefficients and thresholds required for the methodology, mentioned in 5.1.1. Methodology section of the thesis, are called. Using simplified physics-based equations and simulations, a Python code runs in the background and generates weather scenarios analysis and comparison results in bar charts.

<img width="915" height="523" alt="image" src="https://github.com/user-attachments/assets/f60f50e0-393a-4c41-a083-306a5bcf6185" />

Methodology:


# Module 2: Strategy Ranking Module
Module 2, strategy ranking module, represents the user input of building or neighborhood levels new projects. The goal is to prioritize strategies for a new urban development project based on different stakeholders’ profiles and strategies interactions. The user selects the decision-making aspects they want to include and formulate their preference profile, which happens by either selecting a predefined stakeholder profile with ready-to-use preferences or by inputting pairwise comparisons of the strategies dimensions according to AHP method and ranking resilience objectives to use ROC method. The Python code uses these weights to calculate objectives achievement (OA) and dimensions suitability (DS) scores according to the methodology mentioned 5.2.1. Methodology section of the thesis. Strategies interactions are also studied using network analysis theory. Results include heatmaps and bar charts for OA, DS, and adoption (A) scores.

<img width="7357" height="4960" alt="18 - Copy (2)" src="https://github.com/user-attachments/assets/461e87ca-fb0d-4a3e-b711-8bdc27cb3b41" />

Methodology:


# Module 3: Strategy Addition Module
Module 3, strategy addition module, represents the user input of building or neighborhood levels existing projects. The goal is to prioritize strategies that can be added to an existing urban development project to enhance resilience. The user identify the existing strategies in the urban project from the strategies database. Then, the Python code follows the methodology mentioned in 5.3.1. Methodology section of the thesis to generate resilience gap analyses for different decision-making aspects, rank new strategies from the database based on their performance in addressing the identified gaps, and Pareto analysis to identify non-dominated sequential strategies.



Methodology:





