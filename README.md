### Hi there 👋
```
class MyBio:
    def __init__(self):
        self.name = "Gavin Qu"
        self.role = ["Data Creative", "Student", "Curiosity-driven"]
        self.location = ["Seattle"]
        self.languages = ["Python", "C", "JavaScript", "R", "Java"]
        self.interests = ["ML", "Math", "Open Source", "Blogging", "Linux", "Labor Econoimcs"]

    def current_project(self):
        return "Working on a deep learning project for mushroom ID using scraped Reddit data"

    def contact(self):
        return {
            "LinkedIn": "linkedin.com/in/gavinqu/"
        }

    def about_me(self):
        return """
            Outside of work, you'll often find me hiking, climbing, skiing and reading Sci-fi in some 3rd wave cafe. 
        """

bio = MyBio()
print(bio.about_me())
print("Current Project:", bio.current_project())
print("Contact Info:", bio.contact())
```
