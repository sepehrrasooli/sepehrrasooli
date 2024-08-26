```python
class Identity:
    def __init__(self,name:str,age:int,location:str):
        self.name = name
        self.age = age
        self.location = location

class Programmer:
    def __init__(self,specialty:str,familiar_with:list,interested_in:list):
        self.specialty = specialty
        self.familiar_with = familiar_with
        self.interested_in = interested_in


identity = Identity(
    "Sepehr", 
    18, 
    "Tehran",
)

programmer = Programmer(
    "Back-End, Python Developer",
    ["Git","Javascript","Docker","Django","Linux"],
    ["Open-Source Community","Linux","Security"],
)

```
