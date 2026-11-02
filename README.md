# `>>> import mohan_kumar as dev` 🐍

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
mohan_kumar.py — Full-Stack Developer & Python Engineer
"""

from dataclasses import dataclass, field


@dataclass
class DeveloperProfile:
    name: str = "Mohan Kumar N"
    handle: str = "@MohanReddy05"
    role: str = "Full-Stack Developer & Software Engineer"
    location: str = "Bengaluru, India"
    focus: list[str] = field(
        default_factory=lambda: [
            "Full-Stack Web Apps & Scalable Python Backends (FastAPI)",
            "AI Agent Workflows & Automated Data Pipelines",
            "End-to-End QA Automation (Playwright, Postman)",
        ]
    )

    def greet(self) -> str:
        return f"Hey there! I'm {self.name} — turning complex problems into clean Python & TypeScript."


if __name__ == "__main__":
    me = DeveloperProfile()
    print(me.greet())
```

## `def tech_stack() -> dict[str, list[str]]:`

```python
TECH_STACK = {
    "languages":      ["Python", "SQL", "TypeScript", "JavaScript", "Java", "HTML5", "CSS3"],
    "backend_&_apis": ["FastAPI", "Node.js", "Express.js", "REST APIs", "OAuth", "JWT"],
    "frontend_&_app": ["React.js", "Next.js", "React Native", "Expo", "Tailwind CSS"],
    "data_&_bi":      ["Pandas", "NumPy", "Matplotlib", "Seaborn", "Tableau", "Power BI"],
    "databases":      ["PostgreSQL", "MySQL", "MongoDB", "SQLite"],
    "testing_&_ops":  ["Playwright", "Postman", "Git", "GitHub", "Jupyter", "Linux", "VS Code"],
}
```

## `>>> dev.fetch_github_telemetry("MohanReddy05")`

&lt;div align=&quot;center&quot;&gt;
  &lt;img height=&quot;165em&quot; src=&quot;https://github-readme-stats.vercel.app/api?username=MohanReddy05&amp;show_icons=true&amp;theme=tokyonight&amp;include_all_commits=true&amp;count_private=true&amp;hide_border=true&quot; alt=&quot;Mohan&#39;s GitHub Stats&quot; /&gt;
  &lt;img height=&quot;165em&quot; src=&quot;https://github-readme-stats.vercel.app/api/top-langs/?username=MohanReddy05&amp;layout=compact&amp;langs_count=8&amp;theme=tokyonight&amp;hide_border=true&quot; alt=&quot;Top Languages&quot; /&gt;
&lt;/div&gt;

&lt;div align=&quot;center&quot;&gt;
  &lt;img src=&quot;https://github-readme-streak-stats.herokuapp.com/?user=MohanReddy05&amp;theme=tokyonight&amp;hide_border=true&quot; alt=&quot;GitHub Streak&quot; /&gt;
&lt;/div&gt;

## `>>> dev.connect()`

```python
CONTACT_ENDPOINTS = {
    "portfolio": "https://mohankumarn.com/",
    "linkedin":  "https://www.linkedin.com/in/mohan-pulikanti",
}
```
