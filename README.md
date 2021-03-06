
# Mars Rover Kata

You’re part of the team that explores Mars by sending remotely controlled vehicles to the surface of the planet. Develop an API that translates the commands sent from earth to instructions that are understood by the rover.

## Requirements

* You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.
* The rover receives a character array of commands.
* Implement commands that move the rover forward/backward (f,b).
* Implement commands that turn the rover left/right (l,r).
* Implement wrapping from one edge of the grid to another. (planets are spheres after all)
* Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point, aborts the sequence and reports the obstacle.

## Rules
* Git workflow is important. Fork or create a new branch to work off of. *Commit Often, Perfect Later, Publish Once*
* Excercise a TDD discipline to work through the Kata. Don't leave any red refactors. 
* Show that you know OOP principles. Architecture is important.
* Be careful about edge cases and exceptions. We can not afford to lose a mars rover, just because the developers overlooked a null pointer.


## References

* [Victor Farcic](https://technologyconversations.com/2014/10/17/java-tutorial-through-katas-mars-rover/)
* [Kata Log Rocks: Mars Rover](http://kata-log.rocks/mars-rover-kata)
* [Made Tech](https://github.com/madetech/learn/tree/master/katas)

### Complements to 

[Made Tech](https://www.madetech.com/) who first introduced me to this kata
