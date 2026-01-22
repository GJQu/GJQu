### Hi there 👋
```
class MyBio:
    def __init__(self):
        self.name = "Gavin Qu"
        self.role = ["Data Science", "Economics", "Curiosity-driven"]
        self.location = ["Seattle"]
        self.languages = ["Python", "SQL", "R", "Java"]
        self.interests = ["ML for Economics", "Causal Inference", "Open Source", "Blogging", "Linux"]

    def current_project(self):
        return "TBD"

    def contact(self):
        return {
            "LinkedIn": "linkedin.com/in/gavinqu/"
        }

    def about_me(self):
        return """
            Outside of work, you'll often find me hiking, climbing, skiing, and reading Sci-fi. 
        """

bio = MyBio()
print(bio.about_me())
print("Current Project:", bio.current_project())
print("Contact Info:", bio.contact())
```
