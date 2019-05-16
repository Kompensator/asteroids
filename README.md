# asteroids
## Simulates the deflection of an asteroid on collision course with Earth using a powerful laser
This project demonstrates the deflection of an asteroid using laser to provide thrust.
As the laser heats up the asteroid's surface, the stellar material will evaporate and produce a vapour flux. If heated significantly, the asteroid will deorbit as a result of the thrust.
The physics engine supports N-Body simulation with Euler's numerical integration method. The relationship between laser power and thrust produced is derived while consulting the referenced webpages. The acceleration attributed to the action of the laser is directly added into the acceleration of the asteroid body.


## Dependencies
- Python 3 with Matplotlib
- Anaconda Python 3 distro recommanded


## To run
1. Navigate to the project folder
2. `python orbit_sim.py`
3. You will be prompted to enter laser power (W) and burn time (s)
Usually 1e17 watts or above and 1e7 seconds is good
4. Enjoy!


## Authors
- David A.
- Manuel M.
- Ding Yi Z.
- Ben C.


## References
- https://en.wikipedia.org/wiki/Effusion
- https://www.grc.nasa.gov/www/k-12/rocket/mflchk.html


### Special thanks to McGill Physics Department for organising the hackathon where this project came to be!