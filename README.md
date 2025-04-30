This project builds a logistic regression model that predicts whether Amazon’s stock will go up or down after an earnings report, based solely on the RSI (Relative Strength Index) recorded the day before each earnings release.

parameters: 
	•	RSI (Relative Strength Index) values on the day before each of the last 9 Amazon earnings reports.

target:
	•	1: Stock went up after earnings
	•	0: Stock went down or stayed flat

model overview:
	•	A logistic regression model is trained using RSI data from the past 9 earnings events.
	•	The model then predicts the stock movement using the most recent RSI value (e.g., April 30 RSI to predict May 1 earnings).
