### Hi there 👋

<!--
**lewislovelock/lewislovelock** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
``` python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from typing import List

class SoftwareEngineer:

    def __init__(self, name: str, role: str, languages: List[str], hobbies: List[str], skills: List[str], learning: List[str]):
        self.name = name
        self.role = role
        self.languages = languages
        self.hobbies = hobbies
        self.skills = skills
        self.learning = self.skills + learning

    def say_hi(self):
        print(f"👋 Hi there, my name is {self.name} and I am a {self.role}.")
        print(f"💬 I speak {', '.join(self.languages)} and my hobbies include {', '.join(self.hobbies)}.")
        print(f"🧑🏻‍💻 Code： {', '.join(self.skills)}.")
        print(f"📚 Learning: {', '.join(self.learning)} 🤩.")
        print("😄 Thanks for dropping by, hope we will build something that makes the world better 🚀.")

me = SoftwareEngineer(
    name="Lewis Liu",
    role="Software Engineer",
    languages=["Chinese", "English"],
    hobbies=["Coding🧑‍💻", "Hip-hop🎵", "Basketball🏀"],
    skills=["Python", "React", "Machine Learning", "Linux"],
    learning= ["Rust", "Golang", "Penetration Testing"]
)

me.say_hi()

```
