# HERA

- Part of: Google Bangkit 2021 Capstone Project
- Task: Sexual Harassment Classification System

# HERA Data Preprocessing, Modeling, and Sexual harassment Classification

HERA (Helps and Emergency Reporting App) is an Android-based application which provides online complaint service and prevention against women's violence and harassment. HERA mainly solves problems during pandemic conditions, namely the unreadiness of a complaint service model for pandemic conditions (not yet adapted to turning complaints online) and large-scale social restrictions (PSBB) which largely impacted the decrease of report amount in various service agency.

Two Convolutional Neural Networks were trained to classify user posts in the "Speak Up!" feature and report types in "Online Report" based on descriptions. Tweets from the #MeToo movement on X (formerly Twitter) served as training data, with labels assigned via RegEx keyword matching. The models achieved 80.26% accuracy for posts (6 categories) and 78.24% accuracy for reports (7 violence-related categories).

