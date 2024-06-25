# AI AGENT DATA VISUALIZER

## Project Overview

This project demonstrates the use of Watsonx AI and LangChain libraries to analyze and visualize data from a CSV file. It showcases the capabilities of creating an AI agent that interacts with data and generates visualizations based on natural language commands.

## Steps

### 1. Data Import

The project begins by importing the `student-mat.csv` file into a Pandas DataFrame. This dataset contains information about students' academic performance and various personal attributes.

### 2. Model Initialization

Next, the code sets up credentials, model parameters, and project and space IDs necessary for using the Watsonx AI model. It then initializes a Llama 3 70B model and integrates it with LangChain, preparing the system for advanced data processing and analysis.

### 3. Agent Creation

A LangChain agent is created to interact with the DataFrame and the Large Language Model (LLM). This agent serves as the intermediary between the data and the model, enabling natural language interaction for data analysis and visualization tasks.

### 4. Data Analysis and Visualization

The agent is employed to perform various tasks on the DataFrame:
- **Count the Number of Rows**: The agent counts the total number of rows in the DataFrame.
- **Filter Data**: It filters the data to include only students who are over 18 years old.
- **Generate Bar Plots**: Bar plots are generated to show the count of students by gender.
- **Generate Scatter Plots**: Scatter plots are created to illustrate relationships between different variables.
- **Compare Average Final Grades**: The agent compares the average final grades of students based on their internet access status.

### 5. Output

The results of each task are outputted, including the generated plots. These visualizations provide insights into the dataset and demonstrate the analytical capabilities of the AI agent.

## Key Features

- **Natural Language Interaction**: The AI agent is designed to process natural language commands to perform data analysis and visualization tasks.
- **Integration with Watsonx AI and LangChain**: Utilizes powerful AI and language models to enhance data interaction and visualization.
- **Customizable and Extensible**: The agent can be extended to perform more complex tasks and generate more sophisticated visualizations.


## Conclusion

This project showcases the potential of using Watsonx AI and LangChain to analyze and visualize data from a CSV file. By enabling natural language interaction, it simplifies the process of data analysis and visualization, making it accessible to a broader audience.

