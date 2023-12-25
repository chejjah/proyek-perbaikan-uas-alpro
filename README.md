# Reeborg Rain 0
def avoid_rain():
  while not at_goal():
    if object_here():
      turn_left()
    move()
    move()
    move()
    move()
    move()
    move()
    build_wall()
    turn_left()
    move()
    turn_left()
    move()
    move()
    move()
    move()
    move()
    turn_left()
    move()
    turn_left()
    turn_left()
    turn_left()
    build_wall()

avoid_rain()
