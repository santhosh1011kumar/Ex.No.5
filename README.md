
# **EXP 5: COMPARING PROMPTING TECHNIQUES THROUGH ENGINEERING PROBLEM-SOLVING SCENARIOS**

### NAME : SANTHOSH KUMAR A
### REG NO : 212224230250

## **1. Aim**

To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using an ongoing engineering project. The experiment focuses on understanding how different prompting techniques influence the quality, accuracy, completeness, clarity and usefulness of AI-generated responses.

## **2. Project Title**

**AI-Driven Geospatial Analysis for Air Pollution Monitoring and Prediction**

## **3. Problem Statement**

Air pollution is one of the major environmental problems affecting human health and the environment. Traditional air quality monitoring systems depend on monitoring stations installed at specific locations.

However, these monitoring stations are not available everywhere, resulting in gaps in air pollution data. Some locations may also have missing, delayed or inaccurate measurements.

Therefore, there is a need for an intelligent system that combines Artificial Intelligence, Machine Learning and Geospatial Analysis to monitor pollution levels, identify pollution patterns and predict future air quality.

The proposed project aims to use historical air quality measurements, geographical information and optional satellite-derived environmental data to analyze pollution patterns and predict short-term air pollution levels.

## **4. Selected Engineering Scenario**

**Scenario:** Developing an AI-based system to monitor and predict PM2.5 air pollution levels across different geographical locations.

The system should:

1. Collect air quality data from available monitoring stations.
2. Process and clean the collected data.
3. Identify geographical pollution patterns.
4. Apply Machine Learning models to predict future PM2.5 levels.
5. Visualize pollution levels using geographical maps.
6. Handle missing and incomplete environmental data.
7. Evaluate the accuracy of the prediction model.

## **5. AI Tool Required**

- ChatGPT – For generating and evaluating solutions using different prompting techniques.
- Python – For data processing and visualization.
- Pandas – For handling environmental datasets.
- Matplotlib – For generating bar graphs.
- Scikit-learn – For implementing Machine Learning models.

## **6. Base Prompt (Naïve Prompt)**

A naïve prompt is a simple question given to an AI system without providing detailed instructions, context or constraints.

**Prompt:**

Suggest a method to monitor and predict air pollution using AI and geospatial analysis.

&#x20;Copy prompt

**Expected AI-generated response:**

We can develop an air pollution monitoring system using Artificial Intelligence and Geospatial Analysis. First, collect air quality data such as PM2.5, PM10 and NO2 from monitoring stations. Then preprocess the data and apply Machine Learning algorithms such as Random Forest or Linear Regression to predict future pollution levels. Finally, display the pollution levels on geographical maps using visualization tools.

**Observation:**

The response provides a basic solution but does not explain data preprocessing, missing data handling, model validation or implementation steps in detail.

## **7. Improved Prompts Using Different Prompting Techniques**

### **Technique 1 – Role-Based Prompting**

**Prompt:**

Act as an environmental data scientist and geospatial AI engineer. Propose a practical workflow for monitoring and predicting PM2.5 air pollution using air quality station readings and geospatial data. Explain the required datasets, preprocessing techniques, suitable Machine Learning models, validation methods and expected outputs.

**Expected AI-generated response:**

A suitable air pollution monitoring system can be developed using environmental datasets and geospatial technologies.

The system involves the following stages:

1. Data Collection: Collect PM2.5, PM10, NO2 and weather information from air quality monitoring stations.
2. Data Preprocessing: Remove duplicate records, handle missing values and normalize the data.
3. Feature Extraction: Extract geographical coordinates, temperature, humidity and historical pollution values.
4. Model Development: Use Random Forest, XGBoost or LSTM models for pollution prediction.
5. Model Evaluation: Evaluate the model using MAE, RMSE and R².
6. Visualization: Display pollution levels using geographical maps.

**Observation:**

Role-based prompting provides more technical information because the AI system responds from a specific professional perspective.

### **Technique 2 – Context-Rich Prompting**

**Prompt:**

I am developing a student engineering project titled "AI-Driven Geospatial Analysis for Air Pollution Monitoring and Prediction." Monitoring stations may be sparse and readings may contain missing values. Suggest a feasible system that uses available station data and optional satellite-derived features to estimate spatial pollution patterns and predict PM2.5 levels for the next 24 hours. Include limitations and validation methods.

**Expected AI-generated response:**

The proposed system can combine ground-level air quality measurements, geographical information and environmental variables.

The implementation can be divided into:

1. Collect historical air pollution data from monitoring stations.
2. Collect meteorological data such as temperature, humidity and wind speed.
3. Use geographical coordinates to identify the spatial distribution of pollution.
4. Use satellite-derived aerosol information as an additional environmental feature.
5. Apply Machine Learning algorithms such as Random Forest or XGBoost to predict PM2.5 values.
6. Validate predictions using historical observations.
7. Visualize pollution distribution and predicted values on an interactive map.

Satellite aerosol measurements should be treated as indirect environmental indicators rather than direct ground-level PM2.5 measurements.

**Observation:**

Context-rich prompting generates more relevant answers because the AI understands the project's actual problem, objectives and requirements.

### **Technique 3 – Step-by-Step Prompting**

**Prompt:**

Solve this engineering problem in ordered steps:

1. Identify the required air quality and geographical datasets.
2. Clean and align the data based on time and location.
3. Create useful spatial and temporal features.
4. Select a baseline and an improved prediction model.
5. Validate the model using a time-based data split.
6. Display measured and predicted pollution levels on a geographical map.

For every step, explain its purpose and one possible challenge.

**Expected AI-generated response:**

**Step 1: Data Collection**

Collect air pollution measurements and geographical coordinates from available monitoring stations.

**Step 2: Data Preprocessing**

Remove duplicate values and handle missing or incorrect measurements.

**Step 3: Feature Engineering**

Generate useful features such as historical PM2.5 levels, temperature, humidity, wind speed and geographical location.

**Step 4: Model Selection**

Use Linear Regression as a baseline model and Random Forest as an improved prediction model.

**Step 5: Model Evaluation**

Use chronological training and testing datasets. Calculate MAE, RMSE and R².

**Step 6: Visualization**

Display measured and predicted pollution values using geographical maps.

**Observation:**

Step-by-step prompting provides an organized solution and makes the implementation process easier to understand.

### **Technique 4 – Constraint-Based Prompting**

**Prompt:**

Recommend a low-cost and feasible approach for a college project to predict short-term PM2.5 levels and display pollution patterns on a geographical map. Assume limited computing resources, incomplete monitoring station readings and no guarantee of continuous live data. Prefer accessible datasets and open-source tools. Explain the limitations of satellite-derived information.

**Expected AI-generated response:**

A cost-effective air pollution prediction system can be developed using Python and open-source technologies.

Recommended technologies:

- Python for programming.
- Pandas for data processing.
- Scikit-learn for Machine Learning.
- Matplotlib for data visualization.
- Folium for geographical mapping.
- Historical air quality datasets for training.

Random Forest can be used as the primary prediction model. Missing values can be handled using suitable imputation methods.

The system can operate using historical datasets when live data is unavailable. Satellite-derived aerosol information can provide additional spatial information but should not be considered an exact measurement of ground-level pollution.

**Observation:**

Constraint-based prompting produces realistic and practical solutions by considering budget, computing resources and data availability.

### **Technique 5 – Few-Shot / Structured-Output Prompting**

**Prompt:**

Use the following example format:

Input: Hourly air pollution readings + timestamp + latitude + longitude.

Output: Cleaned dataset + predicted PM2.5 + geographical pollution map + evaluation metrics.

Now propose a complete workflow for an air pollution monitoring and prediction project.

Return the response using the following headings:

1. Data Collection
2. Preprocessing
3. Feature Engineering
4. Model Selection
5. Validation
6. Map Visualization
7. Limitations

**Expected AI-generated response:**

**1. Data Collection:** Collect air quality, weather and geographical information.

**2. Preprocessing:** Handle missing values, remove duplicates and normalize data.

**3. Feature Engineering:** Generate spatial and temporal features.

**4. Model Selection:** Apply Random Forest or XGBoost for PM2.5 prediction.

**5. Validation:** Evaluate model performance using MAE, RMSE and R².

**6. Map Visualization:** Display pollution levels using geographical maps.

**7. Limitations:** Consider incomplete datasets, limited monitoring coverage and differences between satellite observations and ground-level pollution.

**Observation:**

Few-shot prompting produces a structured response that is easy to understand, compare and implement.

## **8. Comparison of AI-Generated Responses**

The following table compares the responses obtained using different prompting techniques.

| Prompting technique | Quality | Accuracy | Depth |
| ------------------- | ------- | -------- | ----- |
| Naïve Prompt        | 5       | 5        | 4     |
| Role-Based          | 7       | 7        | 6     |
| Context-Rich        | 9       | 8        | 9     |
| Step-by-Step        | 8       | 8        | 9     |
| Constraint-Based    | 8       | 9        | 7     |
| Few-Shot            | 8       | 7        | 8     |

*Note: These are illustrative evaluation scores. Replace them with scores based on your actual ChatGPT experiments before submission.*

## **9. Detailed Evaluation Table**

Each response is evaluated using five parameters.

Scoring scale: 1 = Poor, 10 = Excellent.

| Technique        | Relevance | Accuracy | Completeness | Clarity | Usefulness |
| ---------------- | --------- | -------- | ------------ | ------- | ---------- |
| Naïve            | 6         | 5        | 4            | 5       | 4          |
| Role-Based       | 7         | 7        | 6            | 7       | 6          |
| Context-Rich     | 9         | 8        | 9            | 8       | 9          |
| Step-by-Step     | 8         | 8        | 9            | 9       | 8          |
| Constraint-Based | 8         | 9        | 7            | 8       | 9          |
| Few-Shot         | 8         | 7        | 8            | 8       | 8          |

## **10. Graphical Representation**

The following graphs use the illustrative scores from the evaluation table.

### **Graph 1 – Average Performance of Prompting Techniques**

Average Prompting Technique Scores

Average of five evaluation criteria, out of 10. Illustrative scores.

0/102.5/105/107.5/1010/10NaiveRole-basedContext-richStep-by-stepConstraint-basedFew-shot

**Analysis:**

The graph indicates that context-rich prompting achieves the highest average score. This is because it provides the AI system with sufficient background information and clearly defines the engineering problem.

### **Graph 2 – Comparison Based on Evaluation Criteria**

Prompt Quality by Evaluation Metric

Illustrative scores for each prompting technique.

<img width="960" height="540" alt="Prompt Quality by Evaluation Metric" src="https://github.com/user-attachments/assets/da5fd43f-e764-4a75-9ee7-556d7317f47b" />

Relevance

Accuracy

Completeness

Clarity

Usefulness

02.557.510NaiveRole-basedContext-richStep-by-stepConstraint-basedFew-shot

**Analysis:**

- Context-rich prompting provides high relevance and completeness.
- Step-by-step prompting improves clarity and depth.
- Constraint-based prompting improves practical usefulness and technical accuracy.
- Naïve prompting provides less detailed answers.

### **Graph 3 – Sample Air Pollution Data**

The following is an illustrative dataset showing pollution levels across five geographical locations.

| Location | PM2.5 | PM10 | NO2 |
| -------- | ----- | ---- | --- |
| Area A   | 32    | 58   | 18  |
| Area B   | 48    | 83   | 27  |
| Area C   | 61    | 105  | 34  |
| Area D   | 42    | 76   | 23  |
| Area E   | 75    | 122  | 41  |

Values are dummy concentrations in µg/m³, not actual sensor measurements.

Air Pollution Levels Across Locations

Illustrative PM2.5, PM10 and NO2 concentrations in µg/m³.

<img width="960" height="540" alt="Air Pollution Levels Across Locations" src="https://github.com/user-attachments/assets/a284d73b-7d72-4a62-912b-1c30dcf5c580" />


PM2.5

PM10

NO2

03570105140Area AArea BArea CArea DArea E

**Analysis:**

The graph shows that Area E has the highest illustrative pollutant values, while Area A has the lowest values among the five locations.

This type of visualization can help identify geographical areas that may require further environmental investigation.

## **11. Analysis and Observations**

The experiment demonstrates that the quality of AI-generated responses depends on how clearly the problem is explained.

1. Naïve prompting generates general information but may not provide sufficient technical details.
2. Role-based prompting improves technical explanations by assigning a specific role to the AI.
3. Context-rich prompting provides more relevant and complete solutions.
4. Step-by-step prompting makes complex engineering problems easier to understand and implement.
5. Constraint-based prompting generates practical solutions by considering real-world limitations.
6. Few-shot prompting produces structured and consistent outputs.

**Does ChatGPT consistently provide better results with improved prompts?**

Yes, generally. Improved prompts provide better context, clear instructions and expected output formats. However, the improvement depends on the task.

**Are there scenarios where naïve prompts work equally well?**

Yes. Naïve prompts can work well for simple questions, definitions, basic explanations and general brainstorming. Advanced prompting techniques are more useful for complex engineering problems.

## **12. Final Selected Prompting Technique**

Selected technique

**Context-Rich + Constraint-Based Prompting**

This combination is selected because it provides detailed project information while considering practical implementation limitations.

It helps generate solutions that are technically relevant, realistic and suitable for a college engineering project.

## **13. Refined / Final Prompt**

The following is the final optimized prompt selected for the project.

Act as an environmental data scientist and geospatial AI engineer.

I am developing a college engineering project titled "AI-Driven Geospatial Analysis for Air Pollution Monitoring and Prediction."

The main problem is that air quality monitoring stations are limited in number, and available readings may contain missing, noisy or delayed information.

Design a feasible and low-cost system to monitor geographical air pollution patterns and predict PM2.5 levels for the next 24 hours.

Include the following:

1. Suitable air quality and environmental datasets.
2. Data preprocessing and missing value handling.
3. Geospatial and temporal feature extraction.
4. Suitable Machine Learning algorithms.
5. Model training and validation methods.
6. Performance evaluation using MAE, RMSE and R².
7. Geographical pollution visualization.
8. Limitations and possible improvements.

Use Python and open-source technologies wherever possible.

Clearly distinguish actual sensor measurements from model predictions. Explain how satellite-derived aerosol information can be used as an additional feature without treating it as a direct ground-level PM2.5 measurement.

Present the solution in numbered implementation steps and include a simple system architecture.

&#x20;Copy final prompt

## **14. Engineering Validation**

The AI-generated solution must be validated before implementing it in the actual engineering project.

The following validation steps are proposed:

1. **Dataset Validation:** Verify the source, availability, timestamps, units and reliability of air quality datasets.
2. **Preprocessing Validation:** Check whether missing values and duplicate records are handled correctly.
3. **Model Validation:** Train the Machine Learning model using historical data and test it using unseen data.
4. **Performance Validation:** Calculate MAE, RMSE and R² to measure prediction performance.
5. **Geospatial Validation:** Compare predicted pollution patterns with actual monitoring station measurements.
6. **Practical Validation:** Check whether the system works with limited data and computing resources.
7. **Result Validation:** Clearly distinguish predicted pollution values from actual sensor measurements.

## **15. Final Conclusion**

This experiment compares different prompting techniques and evaluates their effectiveness in solving an engineering problem related to AI-driven geospatial air pollution monitoring and prediction.

The results indicate that improved prompting techniques generally generate more relevant, accurate, structured and useful responses than simple naïve prompts.

Among the techniques tested, context-rich prompting provides the best overall illustrative evaluation score, while step-by-step prompting improves clarity and constraint-based prompting improves practical feasibility.

The experiment concludes that providing proper context, clear instructions, constraints and expected output formats helps obtain better AI-generated solutions for complex engineering problems.

However, AI-generated responses should always be verified through technical analysis, real datasets and engineering validation before implementation.

## **16. References**

1. World Health Organization (WHO) – Air Pollution: [https://www.who.int/health-topics/air-pollution](https://www.who.int/health-topics/air-pollution?utm_source=chatgpt.com)
2. OpenAQ – Open Air Quality Data: [https://openaq.org/](https://openaq.org/?utm_source=chatgpt.com)
3. Google Earth Engine: [https://earthengine.google.com/](https://earthengine.google.com/?utm_source=chatgpt.com)
4. Scikit-learn Documentation: [https://scikit-learn.org/](https://scikit-learn.org/?utm_source=chatgpt.com)
5. Python Documentation: [https://docs.python.org/3/](https://docs.python.org/3/?utm_source=chatgpt.com)
6. NASA Earthdata: [https://www.earthdata.nasa.gov/](https://www.earthdata.nasa.gov/?utm_source=chatgpt.com)

