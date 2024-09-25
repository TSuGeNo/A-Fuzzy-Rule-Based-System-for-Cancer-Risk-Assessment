**OVERVIEW OF THE PROJECT**
Lung cancer is a significant global health challenge, impacting millions annually and leading to severe complications and high mortality rates if not detected early. 
This disease is classified by the uncontrolled growth of cells in the lungs, with smoking alcohol being a major risk factor for lung cancer. 
This project develops a Fuzzy Rule-Based System FRBS for assessing levels of cancer risk.
This system uses fuzzy logic-a computation paradigm that deals with imprecise information-to provide the highly interpretable, human-like approach to risk prediction based on input parameters, such as genetic factors, lifestyle choices, and medical history.

**FEATURE OF DATASET**
In this project we have consider various risk factors which are highly related to causes of lung cancer such as Age,Air Pollution,Alcohol uses, Chronic_Lung_Disease and Smoking.

**Fuzzy logic Rule-Based Approach for prediction of Lung Cancer**
The computational approach follows the human reasoning that works in terms of uncertainty and imprecision by using the Fuzzy Logic Rule-Based Approach, instead of the rigid, binary logic of true or false, with ideas on degrees of truth or partial membership useful in complex decision-making systems whose input data don't come in a crisp or clear-cut form.

**MALTAB SIMULATION TOOLBOX**
The MATLAB Fuzzy Logic Toolbox provides a comprehensive set of tools for designing and simulating fuzzy logic systems.
If you want to use Fuzzy Logic Toolbox in MATLAB from the command line interface (CLI), you can use the following command:fuzzyLogicDesigner]

**Methodology**

System Input:Raw data is input into the system. For a cancer risk assessment system, inputs might include patient characteristics such as age, medical history, smoking habits, etc.

Fuzzifier:Converts the crisp (numerical) input values into fuzzy sets. This step allows the system to handle imprecise or uncertain data. 
For instance, a patient's age (a precise value like 45 years) might be translated into fuzzy categories like "middle-aged" or "old."

Knowledge Base: Comprises two parts:
Fuzzy Rule Base: A collection of if-then rules that define how input variables should be interpreted and how they relate to the outputs. For example, "If Age is old and Smoking is high, then Cancer Risk is high."
Database: Contains the membership functions that define the fuzzy sets for input and output variables (e.g., defining what qualifies as "old" or "high risk").

Inference Engine: The core of the fuzzy logic system that processes the input data using the rules from the fuzzy rule base. The inference engine applies the fuzzy rules to map the input data to corresponding output fuzzy sets. It aggregates the results of all the relevant rules to generate a fuzzy conclusion.

Defuzzifier: Converts the fuzzy output from the inference engine into a crisp value. In this case, the fuzzy conclusion about the cancer risk (e.g., "high risk") is translated into a specific value or category (e.g., a risk score or a risk level like low, normal, or high).

System Output: The final result of the fuzzy system, which could be a decision or classification, such as determining the level of cancer risk (e.g., Low, Normal, or High) based on the processed inputs.

The above FIS (Fuzzy Inference System) file contains 9 rules, 5 features, and 1 output, which is Risk of Cancer.
As mentioned earlier, the defuzzifier converts the fuzzy output into a crisp value.
For example, if the system determines that a patient has a cancer risk of 4.5, this value falls under the category of Normal Risk for cancer.






