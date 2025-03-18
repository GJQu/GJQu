### Hi there 👋
```
class MyBio:
    def __init__(self):
        self.name = "Gavin Qu"
        self.role = ["Data Creative", "Investment Management", "Pilot"]
        self.location = ["Seattle"]
        self.languages = ["Python", "C", "SQL", "R", "Javascript"]
        self.interests = ["Machine Learning", "A/B Testing", "Open Source"]

    def current_project(self):
        return "Working on a book recommendation system for a community-based book exchange"

    def contact(self):
        return {
            "LinkedIn": "linkedin.com/in/gavinqu/",
            "Email": "gavin.qu@hotmail.com",
        }

    def about_me(self):
        return """
        Passionate and creative data science student with a diverse background in economics and statistics. 
        """

bio = MyBio()
print(bio.about_me())
print("Current Project:", bio.current_project())
print("Contact Info:", bio.contact())
```
