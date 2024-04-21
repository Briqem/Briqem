```py
class Briq:
    def __init__(self, name, title, location, interests, skills):
        self.name = name
        self.title = title
        self.interests = interests
        self.skills = skills

    def __str__(self):
        bio = (
            f"My username is {self.name}, I'm a {self.title} based in {self.location}. "
            f"My interests include {', '.join(self.interests)}. "
            f"I'm skilled in {', '.join(self.skills)}."
        )
        return bio

name = "Briq"
title = "Software Engineer"
interests = ["Network Development", "Backend Development", "Security"]
skills = ["Python", "GO", "C"]

my_bio = Briq(name, title, location, interests, skills)
print(my_bio)
```
