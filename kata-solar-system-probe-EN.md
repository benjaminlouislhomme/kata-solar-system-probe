# Solar system probe

### Instructions
A probe are to be landed by NASA for solar system exploring.

Your task is to develop a program that moves the probe througs the solar system, and fly over each planet.

In this program, the probe's journey is represented as a line crossing the planets's orbites, and a probe has state containing his distance in astronomic unity (AU) from the Sun.


### Input
The input to the program is an signed float :

- the sign is positive for moving the probe away to the sun, and it is negative from moving closer

- the absolute value is the distance to travel


### Output

The program's output is a string message saying :

- *Hello from [planet's name]* if the probe is at the same distance from Sun that some planet

- *I am lost in the universe ...* if the probe is nowhere


### Interface
The class Probe must contain the orbital distance in AU of each planet.

- Mercury => 0.387
- Venus => 0.782
- Earth => 1
- Mars => 1.52
- Jupiter => 5.20
- Saturn => 9.58
- Uranus => 19.20
- Pluto => 30.05

We assume that take off from Earth, with initial position 1.

### Examples to be tested :

- input +0.52 gives output *Hello from Mars*

- input -0.218 gives output *Hello from Venus*

- input +2 gives output *I am lost in the universe ...*