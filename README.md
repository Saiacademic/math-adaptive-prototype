# math-adaptive-prototype

A minimal adaptive math learning system for children.
It generates math puzzles, tracks performance, and automatically adjusts difficulty (Easy / Medium / Hard).

Features:
Generates arithmetic problems (addition, subtraction, multiplication, division).
Tracks correctness and response time.
Rule-based adaptive engine adjusts difficulty based on performance.
Simple console interaction.
End-of-session performance summary.

How It Works:
User enters name and starting difficulty.
System generates puzzles at that level.
Correctness + time taken are recorded.
Difficulty increases if the user performs well; decreases if struggling.
Session summary shows accuracy, average time, and recommended next difficulty.

Run the Project:
pip install -r requirements.txt
python src/main.py

Adaptive Logic (Brief):
Increase difficulty after consistent correct & fast answers.
Decrease difficulty after repeated mistakes or slow answers.
Optional ML model can be plugged in for prediction-based level changes.
