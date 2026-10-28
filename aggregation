class Professor:
    def __init__(self, name: str):
        self.name = name

class Department:
    def __init__(self, name: str):
        self.name = name
        # Aggregation: The department has professors, 
        # but professors exist even if the department closes down.
        self.professors = [] 

    def add_professor(self, professor: Professor):
        self.professors.append(professor)
