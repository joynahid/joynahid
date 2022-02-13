```python
from nahid import INahid

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
        
    def get_interests(self) -> str:
        return "Everything about Coding"
```
