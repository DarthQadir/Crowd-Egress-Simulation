# Crowd-Egress-Simulation
Project that simulates how a crowd exits from a room in the case of an emergency evacuation.

***Note: The simulation takes place in a 2D grid in a Python list where each cell is either a 0 which represents an empty space or a 1 that represents a person***



# Parameters

You can change 4 parameters in the *crowd_egress* class to test the simulation.

people: Integer, specifies the number of people in the room.

room_dim: Tuple of two integers, specifies the dimensions of the room e.g. (20,10) = 20 meters width, 10 meters length.

exits: Integer, specifies the number of exits in the room.

exit_size: Integer, specifies the size of each exit in the room where an 1 = 1 cell in the simulation grid.
