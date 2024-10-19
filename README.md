Batsman Performance Analyzer
Overview
This program is designed to record and analyze a batsman's performance data based on how they perform against spin and pace bowlers. It also provides recommendations on how they can improve their game based on their strike rate and scoring patterns. The program inputs various statistics from the user, calculates key metrics, and displays the information with helpful suggestions.

Features
Input Batsman Data: The user can enter performance statistics for a batsman, including runs scored and balls faced against spin and pace bowlers, as well as their run-scoring pattern across different areas of the field.

Performance Metrics:

Strike Rate: The program calculates the batsman's strike rate against spin and pace bowlers by dividing runs scored by balls faced and multiplying by 100.
Suggestions:

If the strike rate against spin or pace is below 100, the program suggests ways to improve their batting technique against those bowlers.
Based on the batsman's scoring distribution (runs on the long side vs off side), additional suggestions are provided on how they can balance or enhance their gameplay.
Display of Results: The program displays the batsman's performance data in a structured format and provides personalized recommendations for improvement.

Program Flow
Input Phase:

The user is prompted to enter data for each batsman: runs against spin and pace, balls faced against spin and pace, batting average, and runs scored in different areas of the field (long side and off side).
Calculation Phase:

The program calculates the strike rate against spin and pace and compares run distribution between the long side and off side.
Output Phase:

The program prints the collected statistics and calculated metrics for each batsman.
It also provides suggestions based on the strike rate and scoring pattern.
Code Structure
struct StatAdv: Defines a structure that holds the batsman's performance data.
inputBatsmanData(): A function to input performance data for a batsman.
displayBatsmanData(): A function to display a batsman's performance metrics and provide suggestions for improvement.
main(): The main function where batsman data is input, processed, and displayed.
Expected Output
Sample Input:
yaml
Copy code
Entering details for Batsman 1:
Enter runs against spin: 50
Enter balls faced against spin: 40
Enter runs against pace: 30
Enter balls faced against pace: 50
Enter average against spin: 45.2
Enter average against pace: 35.8
Enter runs scored on the long side: 20
Enter runs scored on the off side: 60
Recorded successfully!
Sample Output:
yaml
Copy code
Details and Suggestions:
Details of Batsman 1:
Runs against spin: 50
Balls faced against spin: 40
Runs against pace: 30
Balls faced against pace: 50
Average against spin: 45.20
Average against pace: 35.80
Runs scored on the long side: 20
Runs scored on the off side: 60
Strike rate against spin: 125.00
Strike rate against pace: 60.00
Suggestion: Work on playing pace more aggressively. Consider shots like the pull or hook.
Suggestion: Try to score more runs on the long side. Shots like the cover drive or straight drive might be effective.
How to Compile and Run
Save the code to a file named batsman_analyzer.c.
Open a terminal and navigate to the directory containing the file.
Compile the program using the following command:
Copy code
gcc batsman_analyzer.c -o batsman_analyzer
Run the program:
bash
Copy code
./batsman_analyzer
Output Screenshots
Input Phase:

Output Phase with Suggestions:

Notes
You can adjust the number of batsmen by changing the length variable in the main function.
This program is designed for easy extensibility if more data fields or suggestions are required in the future.
