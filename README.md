<<<<<<< HEAD
# whoop_vs_nrc
This notebook explores and analyzes data from both Nike Running Club and WHOOP. 
=======
# Background
In an effort to build a consistent running habit, I set a personal goal: run 100 kilometers in 100 days. To track my progress, I used the Nike Running Club app to log each run, recording details like distance, pace, duration, and more.
Additionally, I wore a WHOOP fitness tracker 24/7 throughout the challenge. WHOOP collects continuous biometric data, including heart rate (HR), heart rate variability (HRV), strain, and sleep metrics.

Purpose of the Analysis
This notebook explores and analyzes data from both Nike Running Club and WHOOP with the following objectives:
- Evaluate WHOOP's Run Detection Accuracy
- Analyze how accurately WHOOP identified running activities on days I actually went for a run, as tracked by the Nike app.
- Track Running Progress
- Visualize and summarize my running activity over the 100-day challenge.
- Integrate WHOOP and Running Data
- Combine running session data with WHOOP metrics (e.g. HRV, sleep, recovery) to explore how physical strain from runs might be reflected in physiological indicators.

# Data Sources
1. Nike Running Club Export
Includes:
- Date & time of run
- Distance
- Pace
- Duration

2. WHOOP Export
Includes:
- Daily strain
- HRV
- Resting heart rate
- Sleep stages & sleep duration
- Automatically detected activities (type, duration, HR, etc.)

# Notes
Data cleaning and preprocessing were necessary due to format differences between platforms.
WHOOP does not always explicitly label runs as “running” — part of the analysis includes verifying activity classification.

# Key Questions
1. Can we trust WHOOP to automatically detect running sessions accurately?
2. TBD: How do WHOOP metrics (e.g., recovery, HRV, sleep) correlate with running effort and frequency?
>>>>>>> 8a349c5 (whoop and nrc data analysis init)
