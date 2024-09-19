# Football Decision Analysis - Interactive Dashboard


#Project Overview


This project aims to analyze and visualize key decision-making scenarios during a football game using an interactive Power BI dashboard. It explores various play choices such as passing, running, kicking a field goal, or punting, alongside the impact of down scenarios and yard line positions. The dashboard provides detailed insights into how these decisions affect the game's dynamics and outcome, helping users understand strategic choices made during pivotal moments.

#Data Description


The dataset used for this project captures different play types and key attributes affecting football games, including:

-unit_id: Unique identifier for the unit.

-_golden, _unit_state, _trusted_judgments, _last_judgment_at: Metadata about the record, indicating if it’s a finalized decision, judgment count, and the last judgment timestamp.

-antecedent: Describes the situation in the game (e.g., “kick a field goal”).

-antecedent:confidence: Confidence level for the decision, likely based on some scoring system.

-orig_antecedent: Detailed scenario of the game (e.g., “It is first down and 10. The ball is on your opponent’s 20 yardline...").

-option1 to option5: Possible strategic options that could be chosen in that situation (punt, kick a field goal, run, pass, kneel down).

-Play Antecedents: Types of play such as pass, run, kick a field goal, punt, kneel down, or unknown.

-YardLine: The position on the field where the play occurred.

-Down Scenarios: First down, second down, third down, or fourth down.

-TimeLeft: The time left in the game when the play was made.

-Point: The effect of each play on increasing or decreasing points.


Database:https://drive.google.com/file/d/1980UNGlCyZLC3WwGceUI0RkrLX54NgMF/view


#Key Visualizations


-Points Count by Antecedent: A stacked bar chart that visualizes how different play antecedents contribute to the overall points scored or lost.

-Count of Antecedent by Antecedent Gold: A pie chart that shows the distribution of play types based on the percentage each contributes to the total play count.

-Sum of Confidence, Yard Line, and Time Left by Antecedent: A combined area chart that visualizes the sum of confidence, yard line positions, and the time left for each play type.

-Trusted Judgments by Antecedent: A line graph showing the number of trusted decisions made for each antecedent, providing insights into which play choices are more reliable.

-Points by Yard Line and Antecedent: A layered area chart that details how different play types influence point outcomes based on the yard line.

-Downs and YardLine Distribution by Antecedent: A bar chart visualizing the frequency of different play types based on down and yard line, offering insights into situational play choices.



#Workflow


-Data Import and Cleaning: The dataset was imported into Power BI. Basic data cleaning, including column renaming and handling missing or incomplete data, was performed to ensure consistency.

-Building Visualizations: Various charts, including bar charts, pie charts, line graphs, and area charts, were created to provide multiple angles of analysis on the play antecedents and their outcomes.

-Adding Interactivity: Filters and slicers were incorporated, allowing users to interact with the visualizations dynamically. Users can filter the data by down scenarios, yard lines, and specific play types.

-Confidence Analysis: A confidence metric was integrated, showing how much trust can be placed in decisions made for each antecedent, helping to determine the reliability of certain play choices.



#Key Insights
-Strategic Play Insights:

Passing and running plays contribute significantly to both points gained and lost, while kicking and punting are generally conservative choices.

-Down Scenario Analysis:

Certain plays (such as passing) are more frequent in early downs (first and second), while punting is a common choice on fourth down.

-Yard Line Impact:

Play decisions vary drastically based on the yard line. For example, the likelihood of kicking a field goal increases in the red zone, while passing is dominant at longer distances.

-Confidence Levels:

Pass and run plays typically have higher confidence levels, indicating they are often safer and more trusted decisions in game situations.



#Contributing

Contributions are welcome to improve the dashboard or to suggest new visualizations and data insights. If you would like to contribute:

Fork the repository
Submit a pull request
Open an issue to discuss potential enhancements.
