class Room:
    def __init__(self, room_type: str):
        self.room_type = room_type

class House:
    def __init__(self):
        # Composition: Rooms are created inside the house instance.
        # If the house is destroyed, the rooms are destroyed too.
        self.kitchen = Room("Kitchen")
        self.bedroom = Room("Bedroom")
