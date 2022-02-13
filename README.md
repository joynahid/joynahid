```python
from nahid import INahid
import subprocess

class JoyNahid(INahid):
    def __init__(self):
        self.name = "Nahid"
        self.aliases = [
            "joynahid",
            "joynahiid",
            "nahidhasan282"
        ]
        self.email = "nahidhasan282@gmail.com"
        self.location = "Bangladesh"
        self.operating_system = "Ubuntu Linux"
        
        self.programming_languages = [
            "C",
            "C++",
            "Go",
            "Typescript",
            "NodeJS"
        ]
        
    def get_interests(self) -> str:
        return "Everything about Coding"
```
