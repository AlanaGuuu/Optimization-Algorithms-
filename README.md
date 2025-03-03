# Optimization-Algorithms-
Final project for the Algorithm Design and Analysis course, solving the Knapsack problem and TSP using optimization algorithms like Genetic Algorithm, Backtracking, and Branch and Bound. Includes algorithm visualization, data generation, and result display for better understanding.

1. Start the Program
	•	Navigate to the main.py file in the project directory.
	•	Open the command line or terminal, and go to the directory where the file is located.
	•	Enter the command python app.py and press Enter to start the program. Ensure that Python is correctly installed and the environment variable is set up.

2. Run the Program and Import Data
	•	Problem Selection and Data Size Setup
	•	After the program starts, the “Problem Selection” area will appear on the interface.
	•	Select a problem type from the dropdown menu between “Knapsack” and “TSP” (Traveling Salesman Problem).
	•	In the “Data Size” input field, enter an integer for the data size (e.g., input “15”).
	•	Generate Data
	•	After completing the settings above, click the “Generate Data” button.
	•	If the input is valid, a message like “Generated data for Knapsack with size 15” (for Knapsack problem) or “Generated data for TSP with size 15” (for Traveling Salesman Problem) will appear in the text box below.
	•	For the Knapsack problem, a bar chart and other relevant data visualizations will be displayed; for the TSP, the city coordinates will be drawn.
	•	Algorithm Selection
	•	In the “Algorithm Selection” area, there are multiple algorithm options, such as “Backtracking,” “Branch and Bound,” “Genetic Algorithm,” etc.
	•	Select the algorithms you wish to run by checking the boxes. You can select one or multiple algorithms.
	•	Run the Algorithm and View Results
	•	Click the “Run Algorithms” button to start running the selected algorithms.
	•	After the execution is completed, the results of each algorithm will be displayed in the text box below. For example, the output of the Genetic Algorithm might show: “Genetic Algorithm: Size: 15, Best Value: 120.00, Time: 0.4500 s, Solution: Items selected: 1, 4, 6, 9, total items: 4.”

3. System Requirements
	•	Programming Language and Version: Written in Python, recommended to use Python 3.x version.
	•	Third-Party Libraries
	•	numpy: Used for numerical calculations, such as array manipulation and mathematical operations.
	•	matplotlib: Used to create visualization charts, displaying data and algorithm results.
	•	tkinter: Used for building the graphical user interface (GUI) and interactive operations.
	•	logging: Used to log program operation details, which helps in debugging and error tracking.

Notes:
	1.	Before running, make sure all required third-party libraries are installed. You can install them using commands like pip install numpy matplotlib in the command line (depending on your system).
	2.	If the input data is invalid, the program will display an error message in the interface, such as “Invalid size. Please enter an integer.”
	3.	During execution, the console will output log information, including program status, data generation, algorithm execution details, and error messages, which are useful for debugging and issue resolution.
