# exploring problems of the pendulum
summarize our exploration of interesting problems and simpler variants that we can use to orient our understanding

## questions to answer
- how do we calculate the center of mass for a complicated object?
  - how do we approach this if the object isn't rigid?
- can we predict the dynamics of the driven rigid pendulum?
  - is there a closed-form solution?
- how do things change when the pendulum motion affects the driver's motion?

### driven rigid pendulum
**what we know about pendulum motion:**
- make strong statements abt forces, *torques*, potential/kinetic energy
  - need to remind ourselves about polar coordinates and angular motion
  - $\vec{F}_g = -mg\hat{y}$
  - $\omega = 2\pi f = \frac{2\pi}{T}$
- simple harmonic motion
  - *guess:* will occur between $\pm90^{\circ}$, will be expressed by sinusoidal graph
- we expect that simple harmonic motion will break down for a large starting displacement
