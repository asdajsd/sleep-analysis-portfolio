🧠 Project Overview
This project delves into the relationship between sleep patterns and various lifestyle factors, such as physical activity, caffeine consumption, and stress levels. By analyzing cleaned sleep data, the goal is to uncover insights that can inform healthier sleep habits and improve overall well-being.

📊 Dataset
The primary dataset, sleep_cleaned.csv, includes:


Column Name	Description
Date	Date of the sleep record
Sleep Duration	Total hours of sleep
Sleep Quality	Subjective rating of sleep quality
Sleep Onset Latency	Time taken to fall asleep
Wake After Sleep Onset (WASO)	Time spent awake after initially falling asleep
Sleep Efficiency	Percentage of time spent asleep while in bed
Bedtime	Time when the individual went to bed
Wake Time	Time when the individual woke up
Physical Activity	Amount of physical activity during the day
Caffeine Intake	Amount of caffeine consumed
Stress Levels	Subjective stress rating
🔍 Analysis Techniques
The analysis employs:

Descriptive Statistics: To summarize the data.

Correlation Analysis: To identify relationships between variables.

Time Series Analysis: To observe trends over time.

Data Visualization: To present findings clearly.

📁 Project Structure
kotlin
Copy
sleep-analysis-portfolio/
├── sleep_project/
│   ├── data/
│   │   └── sleep_cleaned.csv
│   ├── notebooks/
│   │   └── analysis.ipynb
│   └── README.md
└── README.md
🚀 Getting Started
To run the analysis locally:

Clone the repository:

bash
Copy
git clone https://github.com/asdajsd/sleep-analysis-portfolio.git
Navigate to the project directory:

bash
Copy
cd sleep-analysis-portfolio/sleep_project
Open the Jupyter notebook:

bash
Copy
jupyter notebook notebooks/analysis.ipynb
🎯 Key Findings
Correlation between physical activity and sleep quality: Increased activity is associated with better sleep quality.

Impact of caffeine intake: Higher caffeine consumption correlates with shorter sleep duration.

Stress levels and sleep efficiency: Elevated stress levels are linked to decreased sleep efficiency.

📈 Visualizations
The analysis includes visual representations to:

Illustrate distributions of sleep duration and quality.

Show trends in sleep patterns over time.

Highlight correlations between lifestyle factors and sleep metrics.

🛠 Technologies Used
Python

Pandas

Matplotlib

Jupyter Notebook

🤝 Contributing
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your proposed changes.

📄 License
This project is licensed under the MIT License.
