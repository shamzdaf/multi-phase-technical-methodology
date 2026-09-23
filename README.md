# Methodology for Executing My Project
To operationalize my proposed endeavor that focuses on enhancing the safety, reliability, and lifecycle performance of U.S. highway infrastructure through better use of infrastructure performance data, deterioration and service-life modeling, predictive maintenance, and Lean maintenance practices. The methodology addresses a recognized problem in transportation asset management: infrastructure condition records may be incomplete or limited, while deterioration itself is affected by uncertainty and variability. These limitations can affect the reliability of pavement-performance prediction and the maintenance and rehabilitation decisions that depend on those predictions (Yamany et al., 2025a).
The methodology therefore does not assume that the availability of inspection records automatically provides sufficient information for predictive asset management. It begins with the available performance records and their limitations before selecting deterioration models and using the resulting predictions to support maintenance decisions.
The methodology is organized into six phases: infrastructure performance-data characterization and treatment; deterioration and service-life modeling; uncertainty analysis and risk-based maintenance prioritization; Lean maintenance process optimization; integration with existing DOT asset-management systems; and performance monitoring and validation.
## Scholarly and Professional Feedback
To contribute, please navigate to the **Discussions** at the top of this repository. Specific technical concerns proposed changes may also be submitted through the **Issues** tab.

## Phase I: Infrastructure Performance Data Assessment
The first phase focuses on limitations of infrastructure performance data. Reliable pavement-management analysis depends on the quality and availability of condition information, and probabilistic approaches are particularly relevant where pavement-condition data contain imperfections or limitations (Federal Highway Administration [FHWA], 2020; Yamany et al., 2025a). Data limitations also remain a practical problem in applied pavement research. For example, Yamany et al. (2025b) reported generating substantial additional data to achieve their research objectives because the available pavement data were insufficient for the scale of the proposed preventive-maintenance optimization.
These limitations will first be characterized to determine how the available records can be prepared and used for deterioration and service-life analysis. The purpose is not simply to create a standardized database, but to understand what portions of asset performance are represented by the available data, where important gaps occur, and how those limitations affect subsequent analysis.
## Key Method Components
This phase includes:
-	Integration of available inspection, condition, maintenance, rehabilitation, traffic, environmental, and asset inventory data where appropriate
-	Assessment of data completeness, inspection intervals, missing observations, and consistency of condition records
-	Identification of gaps in historical asset performance data
-	Evaluation of whether the available records adequately represent different stages of asset deterioration
-	Review of differences in condition indicators, measurement procedures, and reporting practices that may affect comparison of the data
### Measurable Outputs
-	Assessed and organized infrastructure performance dataset
-	Identification of missing or limited performance records
-	Defined condition indicators for deterioration and service-life analysis
-	Documentation of data limitations that may affect subsequent modeling
## Phase II: Deterioration and Service-Life Modeling
The second phase focuses on understanding how infrastructure condition changes over time and estimating remaining service life. Pavement-management systems use condition and performance information to model pavement behavior, forecast future condition, estimate remaining service life, and inform treatment strategies and timing (FHWA, 2023).
The modeling approach will be selected according to the type, quantity, temporal structure, and limitations of the performance data established in Phase I. Different Markov model formulations and transition-probability estimation methods have different data requirements and limitations; consequently, model selection should reflect the condition data and explanatory information available for the analysis (Yamany et al., 2025a).
A single deterioration model will not be assumed to be appropriate for every asset or dataset. Statistical, probabilistic, and data-driven methods will be evaluated according to the available data and intended application. Markov-chain models may be considered where condition-state observations support transition-based analysis. Other methods may be considered where they provide a more appropriate representation of the available performance records.

### Key Method Components
This phase includes:
-	Development of deterioration relationships from historical condition and performance data
-	Evaluation of appropriate statistical, probabilistic, and data-driven deterioration methods
-	Evaluation of Markov-chain models where condition-state data support their application
-	Estimation of future asset condition and remaining service life
-	Evaluation of model assumptions and prediction accuracy
### Measurable Outputs
-	Deterioration models for the selected asset type
-	Predicted condition over time
-	Remaining service-life estimates
-	Measures of model accuracy and uncertainty
## Phase III: Uncertainty Analysis and Risk-Based Maintenance Prioritization
Infrastructure deterioration is affected by several factors, including traffic loading, environmental conditions, maintenance history, and variability in measured condition. For this reason, future asset conditions cannot always be represented adequately by a single predicted value. For example, probabilistic pavement-performance models provide a means of representing the stochastic nature of pavement deterioration and limitations in condition information (Yamany et al., 2025a). Research on pavement maintenance optimization has also demonstrated the importance of incorporating uncertainty in pavement deterioration and maintenance effectiveness when developing long-term maintenance schedules (Yamany et al., 2025b; Yao et al., 2022).
The third phase will therefore evaluate uncertainty associated with deterioration and service-life estimates and determine how that uncertainty affects maintenance decisions.
Probabilistic methods will be used where supported by the available data and selected deterioration model. Monte Carlo simulation may be applied where technically appropriate to examine a range of possible future condition or service-life outcomes. Simulation will be used to represent uncertainty within an established analytical framework rather than being treated as a substitute for adequate performance information.
The resulting predictions will then support risk-based maintenance prioritization. This is consistent with the broader transportation asset-management framework in which condition, performance forecasts, lifecycle considerations, risk, and investment strategies inform maintenance and rehabilitation planning (FHWA, 2023).
### Key Method Components
This phase includes:
-	Evaluation of uncertainty in condition measurements and deterioration estimates
-	Consideration of traffic, environmental exposure, maintenance history, and other relevant factors
-	Use of probabilistic simulation where appropriate
-	Prioritization of assets based on predicted condition, risk, asset importance, and consequences of delayed maintenance
-	Comparison of preventive and reactive maintenance alternatives
-	Identification of appropriate intervention periods
### Measurable Outputs
-	Probabilistic estimates of future condition and service life
-	Risk-based asset prioritization
-	Recommended maintenance intervention periods
-	Maintenance scheduling information
## Phase IV: Lean Maintenance Process Optimization
The fourth phase applies Lean principles to the maintenance process. The purpose is to identify where delays, repeated activities, unnecessary process steps, or inefficient use of resources occur between inspection, maintenance planning, and field implementation.
Lean methods have previously been applied within state transportation maintenance operations to identify waste and improve operational efficiency. An INDOT-sponsored applied research program, for example, examined the use of Lean tools and methodology within maintenance operations and used process-improvement projects to address existing operational problems and opportunities (Padfield, 2018).
The purpose of this phase is to identify delays, duplication, repeated activities, unnecessary process steps, rework, and inefficient use of resources between inspection, maintenance planning, and field implementation.
Lean process improvement will therefore complement the deterioration and predictive-maintenance analysis rather than replace it. The objective is to improve the process through which data is converted into maintenance action.

### Key Method Components
This phase includes:
-	Mapping existing inspection and maintenance processes
-	Identifying delays, duplication, rework, and non-value-added activities
-	Evaluating opportunities to standardize common maintenance processes where appropriate
-	Developing clearer inspection-to-intervention workflows
-	Evaluating information flow between inspection, asset management, maintenance planning, and field operations
-	Tracking maintenance cycle time, cost, and resource use
### Measurable Outputs
-	Improved maintenance process maps
-	Recommended maintenance procedures and workflows
-	Maintenance cycle-time measures
-	Maintenance cost
## Phase V: Integration with Existing DOT Asset Management Systems
The methodology is intended to work with existing DOT asset management systems rather than create a separate system that agencies would have to adopt. Federal transportation asset-management practice emphasizes the use of quality information, lifecycle planning, risk management, performance forecasting, and investment strategies to support systematic maintenance, preservation, rehabilitation, and replacement decisions (FHWA, 2023).
The condition, deterioration, service-life, uncertainty, and maintenance-prioritization information developed through the preceding phases will therefore be organized so that it can support existing agency asset-management, maintenance-planning, programming, and investment activities.
The methodology will also recognize differences in data availability and characteristics when models are applied in different settings. Recent research evaluating the transferability of pavement-performance models has shown that direct model transfer can vary across deterioration stages and operating contexts, while similarity in relevant covariates and updating with available local data can improve transferred-model performance (Obonguta et al., 2026). Application across agencies will therefore require consideration of local data and operating conditions rather than assuming that identical models and parameters can be transferred directly.

### Key Method Components
This phase includes:
-	Alignment with existing DOT databases and asset management systems
-	Development of reporting formats for condition, deterioration, risk, and maintenance information
-	Development of performance dashboards where useful
-	Preparation of implementation guidance for engineering, inspection, and maintenance personnel
-	Consideration of differences in agency data structures and maintenance practices
### Measurable Outputs
-	Asset performance and maintenance dashboards
-	Decision-support and reporting templates
-	Guidance for implementing the methodology within existing DOT processes
## Phase VI: Performance Monitoring and Validation
The final phase evaluates whether the methodology produces reliable predictions and useful maintenance information. Where sufficient historical data are available, predicted deterioration and service-life estimates will be compared with observed asset performance. The need for validation is particularly important when the quantity or quality of available data limits the ability to establish model applicability. Yamany et al. (2025b), for example, identified lack of sufficient validation data as a limitation of their probabilistic preventive-maintenance optimization model and recommended validation when sufficient data become available.
Maintenance outcomes will also be monitored to determine whether recommended interventions produce the expected changes in asset performance. As additional condition and maintenance data become available, the models can be reviewed and updated. Monitoring and feedback are also consistent with transportation asset-management principles in which performance results are evaluated to determine the effectiveness of management and investment decisions (FHWA, 2023).
Broader application of the methodology will depend on validation using data and operating conditions representative of the intended transportation network rather than assuming that a model developed from one dataset can be transferred unchanged to another. Evidence from pavement-performance model transfer research reinforces the need to evaluate transferability and, where appropriate, incorporate local information when models are applied to new settings (Obonguta et al., 2026).

### Key Method Components
This phase includes:
-	Comparison of predicted and observed asset condition
-	Evaluation of prediction error and model reliability
-	Monitoring of preventive maintenance and emergency repair trends
-	Evaluation of maintenance cycle time and cost
-	Updating of deterioration models as additional performance data become available
-	Evaluation of whether the methodology can be transferred to other DOTs or transportation networks
### Measurable Outputs
-	Model validation results
-	Performance and maintenance evaluation reports-
-	Updated deterioration models where necessary
-	Documented limitations and areas requiring improvement
-	Guidance for applying the methodology to other transportation agencies
Distinction from Routine Employment Duties
This work goes beyond routine inspection or construction engineering activities performed for a single project or employer. The proposed endeavor integrates infrastructure performance data, deterioration and service-life modeling, uncertainty analysis, risk-based maintenance prioritization, Lean process improvement, and asset-management implementation into a structured methodology for improving maintenance planning and decision-making. The feasibility of integrating inspection and maintenance-related decisions within pavement-management frameworks has been demonstrated in prior research (Shon & Lee, 2021) 
## Anticipated National Impact
The proposed methodology is intended to:
-	Improve prediction of infrastructure deterioration and remaining service life
-	Support earlier identification of assets approaching poor or critical condition
-	Improve the timing and prioritization of maintenance and rehabilitation
-	Improve the use of available resources
-	Reduce unnecessary delays and inefficiencies in maintenance processes
-	Improve the safety and reliability of highway infrastructure

# References
- Federal Highway Administration. (2020). Successful practices for quality management of pavement surface condition data collection and analysis: Phase I, Task 2—Document of successful practices (FHWA-RC-20-007). U.S. Department of Transportation.
- Federal Highway Administration. (2023). Transportation asset management. U.S. Department of Transportation.
- Obonguta, F., Mizutani, D., Sovanneth, N., & Kaito, K. (2026). Transferability of pavement performance models: Evaluation of direct and updated Markov model transfer. Results in Engineering, 29, 109020. https://doi.org/10.1016/j.rineng.2026.109020
- Padfield, J. R. (2018). Implementation of continuous improvement for INDOT maintenance (training and tracking process improvements) (Joint Transportation Research Program Publication No. FHWA/IN/JTRP-2018/19). Purdue University. https://doi.org/10.5703/1288284316864
- Shon, H., & Lee, J. (2021). Integrating multi-scale inspection, maintenance, rehabilitation, and reconstruction decisions into system-level pavement management systems. Transportation Research Part C: Emerging Technologies, 131, 103328. https://doi.org/10.1016/j.trc.2021.103328
- Yamany, M. S., Abraham, D. M., Nantung, T. E., Labi, S., & Abaza, K. A. (2025a). Probabilistic modelling of pavement performance using Markov chains: A critical review. International Journal of Pavement Engineering, 26(1), 2548321. https://doi.org/10.1080/10298436.2025.2548321
- Yamany, M. S., Abraham, D. M., Ventresca, M., Nantung, T. E., & Labi, S. (2025b). Probabilistic optimization of pavement preventive maintenance using multi-objective genetic algorithm. Innovative Infrastructure Solutions, 10, 194. https://doi.org/10.1007/s41062-025-01963-6
- Yao, L., Leng, Z., Jiang, J., & Ni, F. (2022). Large-scale maintenance and rehabilitation optimization for multi-lane highway asphalt pavement: A reinforcement learning approach. IEEE Transactions on Intelligent Transportation Systems, 23(11), 22094–22105. https://doi.org/10.1109/TITS.2022.3161689

