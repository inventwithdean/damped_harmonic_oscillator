# 🌊 Damped Harmonic Oscillator Integration 
*A beautiful dance of physics and mathematics* ✨

Based on Steve Brunton's amazing lecture: [Second-Order ODE: Spring-Mass-Damper](https://youtu.be/r1eWerqrcqo) 🎓

## 🧮 The Beautiful Theory
The damped harmonic oscillator is like a poetry in physics, described by this elegant equation:

$$m\frac{d^2x}{dt^2} + c\frac{dx}{dt} + kx = 0$$

What's dancing in this equation? 🩰
- m = mass (our main character)
- c = damping coefficient (the resistance)
- k = spring constant (the restoring force)
- x = position (where we are)
- dx/dt = velocity (how fast we're moving)
- d²x/dt² = acceleration (how our speed changes)

### 🔄 State Space Magic
Here's where it gets interesting! We can transform our 2nd order ODE into two 1st order ODEs using the state space sorcery ✨

Let's say $x$ be the position and $v = \dot{x}$ be the velocity.

And voilà! Our system becomes this beautiful matrix:
$$\begin{bmatrix} \dot{x} \\ \dot{v} \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ -\omega^2 & -\zeta \end{bmatrix} \begin{bmatrix} x \\ v \end{bmatrix}$$

The magical ingredients 🪄:
- $\omega = \sqrt{\frac{k}{m}}$ (natural frequency - the system's heartbeat 💓)

- $\zeta = {\frac{c}{m}}$ (damping ratio - how quickly the dance fades 🌙)
