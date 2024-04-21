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

<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/rzashakeri/beautify-github-profile?style=flat-square"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/rzashakeri/beautify-github-profile?style=flat-square"> <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/rzashakeri/beautify-github-profile?style=flat-square"> <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/rzashakeri/beautify-github-profile?color=blue&style=flat-square"> <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rzashakeri/beautify-github-profile?color=blue&style=flat-square"> <img alt="GitHub" src="https://img.shields.io/github/license/rzashakeri/beautify-github-profile?color=blue&style=flat-square"> <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/rzashakeri/beautify-github-profile?color=blue&style=flat-square"> <img alt="GitHub closed pull requests" src="https://img.shields.io/github/issues-pr-closed/rzashakeri/beautify-github-profile?color=blue&style=flat-square">
<img src="https://raw.githubusercontent.com/omidnikrah/profile-activity-generator/master/demo.png" style="max-width: 100%;">
<br/>
<br/>
