## Hi🌼

```python
class oridotexe:
    def __init__(self):
        self.pronouns = ("she", "her")
        self.language_spoken = ["Spanish", "English"]
        self.code = ["Python", "C++", "HTML", "CSS", "JavaScript", "C#"]
        self.interests = ["Data Science", "Machine Learning", "Data Visualization"]
        self.hobbies = ["Music", "Gardening", "Baking Cookies", "Mathematics", "Learning New Things"]
        self.challenge = "I am currently exploring Data Science techniques and trying to keep up with LeetCode."

    def introduce(self):
        return (f"Hi! I'm Ori. I'm currently studying Software Engineering, and my focus of interest is "
                f"{', '.join(self.interests)} 🌱\n")

me = oridotexe()
print(me.introduce())
```
