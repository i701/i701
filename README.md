```python
import random

class Me:
    def __init__(self):
        self.greeting = "Yeet! 👋, I'm Aidhaan"
        self.bio = "Full stack Web Developer from Maldives 🇲🇻"
        self.languages = ['javascript', 'typescript', 'python']
        self.frameworks = ['NextJS', 'Django', 'React', 'FastAPI']
        self.website = 'dev.idhaan.me'
        self.projects = ['https://donors.ungoodhoo.live']
        self.facts = [
            "I love Telegram.",
            "Not only do I love Telegram, I obsess over it.",
            "I loathe Viber.",
            "I like chocolate cake.",
            "I love football.",
            "I don't like my native language, Dhivehi."
        ]

    def get_random_fact(self) -> str:
        """Get a random fact about me."""
        return random.choice(self.facts)

    def __str__(self) -> str:
        """String representation of Me."""
        return f"{self.greeting}\n{self.bio}\nWebsite: {self.website}\nLanguages: {', '.join(self.languages)}\nFrameworks: {', '.join(self.frameworks)}\nProjects: {', '.join(self.projects)}"


if __name__ == "__main__":
    me = Me()
    print(me.get_random_fact())

```

[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=i701&border=8&line=fb8c00&bg_color=fafcff&point=cf222e)](https://github.com/ashutosh00710/github-readme-activity-graph)
<p align='center'><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=i701&" alt="i701" /></p>
