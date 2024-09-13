## Hi there 👋

```python
# Import libraries
from le_wagon_data_bootcamp import DataAnalysis, DataVisualization, MachineLearning
from journalism import Research, Storytelling, Communication

# Gabriella Pacheco's profile
class GabriellaPacheco:
    def __init__(self):
        self.title = "Junior Data Analyst"
        self.motto = "Turning data into actionable insights"
        self.languages = ["Portuguese", "Spanish", "English", "Dutch (Intermediate)"]
        self.list_of_interests = [
            "Star Trek", "Star Wars", "football", "photography", "rock music", 
            "pop culture", "cinema", "tv shows", "baking"
        ]

    def journey(self):
        return ("From Communications Specialist to Data Analyst, "
                "my journey is fueled by a passion for analysis — whether "
                "it's speech, information, or complex datasets.")

    def approach(self):
        return [
            "Combine curiosity, empathy, and creativity to uncover challenges",
            "Craft strategic, data-driven solutions using Python, SQL, and Power BI",
            "Adapt and thrive across diverse industries, applying a multidisciplinary approach"
        ]

    def connect(self, expanding_team=False, partner_for_project=False):
        if expanding_team:
            return "Check my portfolio to see how I can contribute to your team!"
        elif partner_for_project:
            return f"Let's work together! Some of my interests include: {', '.join(self.list_of_interests)}."
        else:
            return "Come back any time! Let's connect when you're ready to collaborate."

# Initialize and display profile summary
profile = GabriellaPacheco()
print(profile.journey())
print(profile.approach())
print(profile.connect(expanding_team=True))   # Check the portfolio
print(profile.connect(partner_for_project=True))  # Partnering for a project
print(profile.connect())   # Default case

```
