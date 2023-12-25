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


# Reeborg Rain 1
while not at_goal():
  if right_is_clear():
     move()
     if wall_in_right():
        turn_left()
        turn_left()
        move()
        turn_left()
        build_wall()
        turn_left()
     else:
        turn_left()
        turn_left()
        turn_left()
        move()
     elif front_is_clear():
        move()

     else:
        turn_left()

 if at_goal():
    done()
        
        
