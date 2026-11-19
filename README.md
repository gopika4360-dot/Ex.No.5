

# EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios


### Project Title

**AI-Based Predictive Maintenance of Industrial Motors**

---

## AIM

To compare different prompting techniques for solving an engineering problem using an AI system and evaluate their effectiveness in analysing industrial motor condition, identifying possible faults, and recommending suitable maintenance actions.

---

## AI TOOLS REQUIRED

 ChatGPT 



## EXPERIMENT OVERVIEW

Predictive maintenance uses machine and sensor data to identify abnormal operating conditions before a major failure occurs. Industrial motor monitoring commonly uses parameters such as vibration and temperature, along with electrical measurements.

In this experiment, different prompting techniques are given to an AI model for analysing the same industrial motor condition.

The following prompting techniques are compared:

1. Straightforward Prompting
2. Role-Based Prompting
3. Constraint-Based Prompting
4. Step-by-Step Prompting

The responses are compared based on accuracy, relevance, clarity, completeness, and usefulness for engineering decision-making.

---

# ENGINEERING PROBLEM SCENARIO

### AI-Based Predictive Maintenance of an Industrial Induction Motor

An industrial three-phase induction motor is operating in a manufacturing plant.

The maintenance team collected the following sensor readings:

| Parameter         | Measured Value |
| ----------------- | -------------: |
| Motor Temperature |           82°C |
| Vibration         |       7.8 mm/s |
| Motor Current     |          9.4 A |
| Motor Speed       |       1440 RPM |
| Load              |            85% |
| Bearing Noise     |           High |

The maintenance engineer wants to determine whether the motor is operating normally and whether maintenance is required.

### Problem Statement

**Analyse the sensor readings and determine:**

* Motor operating condition
* Possible fault
* Severity of the condition
* Recommended maintenance action

> Note: The values above are sample experimental values created for this prompting experiment and are not claimed to be measurements from a real motor.

---

# PROMPTING TECHNIQUE 1: STRAIGHTFORWARD PROMPT

### Prompt

```text
Analyse the following industrial motor sensor data:

Temperature: 82°C
Vibration: 7.8 mm/s
Current: 9.4 A
Speed: 1440 RPM
Load: 85%
Bearing noise: High

Determine the motor condition, possible fault and recommended maintenance action.
```

### AI-Generated Output

The motor appears to be operating under an abnormal condition.

The high vibration and elevated temperature indicate that the motor should be inspected. The high bearing noise may indicate bearing wear or another mechanical problem.

Possible causes include:

* Bearing wear
* Misalignment
* Mechanical imbalance
* Excessive loading

### Recommended Action

Inspect the bearings, shaft alignment and mechanical mounting. Continue monitoring temperature and vibration. If the values continue increasing, schedule maintenance before a major failure occurs.

### Observation

The straightforward prompt provides a basic and useful answer, but it does not give a detailed engineering analysis.

---

# PROMPTING TECHNIQUE 2: ROLE-BASED PROMPT

### Prompt

```text
Act as an experienced industrial maintenance engineer.

Analyse the following three-phase induction motor data:

Temperature: 82°C
Vibration: 7.8 mm/s
Current: 9.4 A
Speed: 1440 RPM
Load: 85%
Bearing noise: High

Evaluate the motor health, identify the most likely causes of abnormal behaviour and recommend appropriate maintenance actions.
Do not claim an exact fault without sufficient evidence.
```

### AI-Generated Output

As an industrial maintenance engineer, the motor should be considered to have a potential developing mechanical problem.

The most important warning indicators are:

1. **High vibration** – may indicate imbalance, misalignment or bearing degradation.
2. **Elevated temperature** – may indicate excessive mechanical or electrical loading, poor cooling or bearing friction.
3. **High bearing noise** – increases the possibility of bearing-related deterioration.
4. **High load** – may contribute to increased temperature and current.

### Possible Faults

The likely causes should be investigated in the following order:

* Bearing wear or lubrication problem
* Shaft or coupling misalignment
* Rotor imbalance
* Cooling problem
* Excessive loading

### Recommended Maintenance

* Inspect the motor bearings.
* Check lubrication condition.
* Verify shaft and coupling alignment.
* Inspect cooling airflow.
* Check motor current against the rated current.
* Continue vibration and temperature monitoring.

### Observation

The role-based prompt produces a more professional response because the AI is instructed to behave like a maintenance engineer.

---

# PROMPTING TECHNIQUE 3: CONSTRAINT-BASED PROMPT

### Prompt

```text
Analyse the industrial motor using the following constraints:

1. Use only the given sensor values.
2. Do not invent additional measurements.
3. Identify at least three possible causes.
4. Classify the condition as Normal, Warning or Critical.
5. Give three recommended maintenance actions.
6. Clearly separate observations from assumptions.
7. Do not claim a definite fault without further testing.

Sensor data:

Temperature = 82°C
Vibration = 7.8 mm/s
Current = 9.4 A
Speed = 1440 RPM
Load = 85%
Bearing noise = High
```

### AI-Generated Output

### Condition: WARNING

### Observations

* Temperature is elevated.
* Vibration is relatively high.
* Bearing noise is reported as high.
* Motor is operating at an 85% load.
* The motor speed is 1440 RPM.

### Possible Causes

1. Bearing degradation
2. Shaft misalignment
3. Rotor imbalance
4. Cooling problem
5. Excessive mechanical loading

### Recommended Actions

1. Inspect the bearings and lubrication.
2. Check shaft and coupling alignment.
3. Monitor vibration and temperature trends.

### Limitation

The available data is insufficient to confirm the exact fault. Additional tests such as vibration spectrum analysis, current analysis and physical inspection may be required.

### Observation

The constraint-based prompt gives a more controlled and structured answer. It reduces unsupported assumptions and clearly separates observations from possible causes.

---

# PROMPTING TECHNIQUE 4: STEP-BY-STEP PROMPT

### Prompt

```text
Analyse the industrial motor step by step.

Step 1: Examine each sensor reading.
Step 2: Identify abnormal parameters.
Step 3: Explain what each abnormal parameter may indicate.
Step 4: Combine the evidence to determine the overall motor condition.
Step 5: List possible faults in order of likelihood.
Step 6: Recommend suitable maintenance actions.
Step 7: State what additional information would be required to confirm the diagnosis.

Data:

Temperature: 82°C
Vibration: 7.8 mm/s
Current: 9.4 A
Speed: 1440 RPM
Load: 85%
Bearing noise: High
```

### AI-Generated Output

### Step 1 – Sensor Analysis

The temperature is elevated and should be monitored.

The vibration level indicates abnormal mechanical behaviour.

The motor is operating at a relatively high load.

High bearing noise provides an additional indication of possible mechanical deterioration.

### Step 2 – Abnormal Parameters

The main abnormal indicators are:

* Vibration
* Temperature
* Bearing noise

### Step 3 – Possible Meaning

**Vibration:** May indicate imbalance, misalignment or bearing problems.

**Temperature:** May be associated with excessive loading, friction or insufficient cooling.

**Bearing Noise:** May indicate bearing wear or lubrication problems.

### Step 4 – Overall Condition

The motor should be treated as being in a **warning condition** and should be inspected.

### Step 5 – Possible Faults

1. Bearing deterioration
2. Misalignment
3. Mechanical imbalance
4. Cooling problem

### Step 6 – Maintenance Action

* Inspect bearings.
* Check lubrication.
* Verify alignment.
* Check cooling system.
* Monitor vibration and temperature.

### Step 7 – Additional Information Required

To improve the diagnosis, the following information would be useful:

* Historical vibration readings
* Vibration frequency spectrum
* Rated motor current
* Rated temperature
* Previous maintenance history
* Motor load history

### Observation

The step-by-step prompt produces the most detailed reasoning structure and makes the engineering decision easier to follow.

---

# COMPARISON OF PROMPTING TECHNIQUES

| Prompting Technique | Accuracy  | Detail    | Clarity   | Engineering Usefulness |
| ------------------- | --------- | --------- | --------- | ---------------------- |
| Straightforward     | Medium    | Low       | Medium    | Medium                 |
| Role-Based          | High      | High      | High      | High                   |
| Constraint-Based    | High      | High      | Very High | Very High              |
| Step-by-Step        | Very High | Very High | Very High | Very High              |

---

# COMPARATIVE OBSERVATIONS

### 1. Straightforward Prompt

* Easy to create
* Produces a quick response
* Requires little prompt engineering
* May provide limited reasoning

### 2. Role-Based Prompt

* Gives the AI a specific professional perspective
* Produces more domain-oriented recommendations
* Useful for engineering decision-making

### 3. Constraint-Based Prompt

* Controls the AI's response
* Reduces unsupported assumptions
* Produces a structured answer
* Useful when accuracy and limitations are important

### 4. Step-by-Step Prompt

* Provides detailed analysis
* Breaks the engineering problem into smaller stages
* Makes the reasoning easier to understand
* Useful for complex engineering problems

---

# ENGINEERING ANALYSIS

The sample motor shows several warning indicators. Vibration monitoring is particularly useful for identifying mechanical conditions such as imbalance, misalignment and bearing wear. Temperature monitoring can also help identify overheating and abnormal operating conditions. Research on industrial motor predictive maintenance commonly combines sensor data with machine-learning methods to detect anomalies and support proactive maintenance.

However, sensor values alone should not be used to declare an exact motor fault. Historical trends, motor ratings, vibration-frequency analysis and physical inspection can provide additional evidence.

---

#  RESULT

Among the four prompting techniques:

**Step-by-Step Prompting** provides the most comprehensive engineering analysis.

**Constraint-Based Prompting** provides the most controlled and reliable response because it specifies what the AI should and should not assume.

**Role-Based Prompting** improves the professional quality of the response.

**Straightforward Prompting** is suitable for quick preliminary analysis.

Therefore, for an industrial predictive-maintenance application, **Constraint-Based and Step-by-Step Prompting are the most useful techniques**.

---

# CONCLUSION

This experiment demonstrated how different prompting techniques influence AI-generated solutions for an engineering problem.

The same industrial motor sensor data produced different levels of analysis depending on the prompt structure. Simple prompting generated a basic response, while role-based prompting produced a more professional engineering perspective. Constraint-based prompting improved response control and reduced unsupported assumptions. Step-by-step prompting produced the most detailed and systematic analysis.

Hence, effective prompt engineering can improve the usefulness, clarity and reliability of AI-assisted engineering problem solving.

---

# FINAL COMPARISON

| Feature                  | Straightforward | Role-Based      | Constraint-Based    | Step-by-Step     |
| ------------------------ | --------------- | --------------- | ------------------- | ---------------- |
| Easy to use              | ✓               | ✓               | ✓                   | ✓                |
| Professional response    |                 | ✓               | ✓                   | ✓                |
| Controls assumptions     |                 |                 | ✓                   | ✓                |
| Detailed reasoning       |                 | ✓               | ✓                   | ✓                |
| Suitable for engineering | ✓               | ✓✓              | ✓✓✓                 | ✓✓✓              |
| Best use                 | Quick analysis  | Expert analysis | Controlled analysis | Complex analysis |

**Best Prompting Technique for this scenario: Constraint-Based + Step-by-Step Prompting**

