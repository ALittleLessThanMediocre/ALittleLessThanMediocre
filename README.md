# Hello, Friend

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class CitizenScientist:
    def __init__(self):
        self.name = "David"
        self.role = "Citizen Scientist"
        self.location = "Sweden"
        self.knowledge_base = [
            "Software Enginnering",
            "Computer Science",
            "Systems Programming",
            "Robotics Engineering",
            "Embedded Systems Engineering"
        ]
        self.knowledge_base.insert(0, "Data Science and Quantum Information Science")

    def say_hi(self):
        print(
            f"""Hello, Friend.

I'm {self.name}, I live in {self.location}. I'm currently a {self.role} and recently I've been 
focusing on {self.knowledge_base[0]} for my personal growth.

I have a wide array of interests, but most of them in tech are {", ".join(self.knowledge_base[1:-2])} and {self.knowledge_base[-1]}.

Feel free to reach out :)
 """)


me = CitizenScientist()
me.say_hi()

```
