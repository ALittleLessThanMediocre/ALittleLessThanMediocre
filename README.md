# Hello, Friend

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class CitizenScientist:
    def __init__(self):
        self.name = "David"
        self.role = "Citizen Scientist"
        self.location = "Johannesburg, South Africa"
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
            """Hello, Friend.

I'm {name}, I live in {location}. I'm currently a {role} and recently I've been 
focusing on {focus} for my personal growth.

I have a wide array of interests, but most of them in tech are {knowledge_base} and {last}.

Feel free to reach out :)
 """.format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:-2]),
                last=self.knowledge_base[-1]
            )
        )


me = CitizenScientist()
me.say_hi()

```