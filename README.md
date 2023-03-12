# test
class CartState:
    def __init__(self, position, velocity, direction):
        self.position = position
        self.velocity = velocity
        self.direction = direction

    def move(self):
        # some code to move the cart
        pass

    def change_direction(self, new_direction):
        self.direction = new_direction

    def get_position(self):
        return self.position
