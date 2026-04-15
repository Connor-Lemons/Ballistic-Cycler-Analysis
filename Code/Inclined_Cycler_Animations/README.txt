File Naming Scheme:

tgt - Minimize the cross product of the initial velocity vector w.r.t. a unit vector inclined below the xy-plane at the specified angle. Start with the planar cycler guess and rotate it by a degree for the first iteration, then take successive solutions and recycle them as guesses after rotating by a degree

tgts - Minimize the cross product of the initial velocity vector w.r.t. a unit vector inclined below the xy-plane at the specified angle. Start with the planar cycler guess and rotate it by the specified degree. Never recycle generated solutions in future iterations.

z - Minimize the integral of the square of the z-position across the orbit. Start with the planar cylcer guess and rotate it by the specified degree. Never recycle solutions as guesses.

The number indicates the targeted angle for the optimizer (if applicable) and the initial guess (if applicable), inert indicates the orbit in an inertial frame centered at the system barycenter, rot indicates the orbit in the CR3BP frame for the Earth and the Moon.

Folder Naming Scheme:

Accidental Near Rectilinear Halo Orbit with Cycler Periodicity: Accidentally found a NRHO with repeatable Earth-Moon geometry about the L1 point

Somewhat Interesting Orbits: Orbits with cycler nature that deviate from the standard cycler shape

Standard-ish Cyclers: Orbits which are more or less standard cyclers. Any orbits with tgt or tgts cross the Lunar Orbital Plane on the backside of the Earth at the specified angle (moving down through the plane).

Strange Elliptical Cycler (kinda) Orbits: Elliptical orbits around Earth which take advantage of Lunar gravitational perturbations to achieve orbits which are impossible to fly in the standard 2-body problem, but end up being more or less ellipses. All have repeatable Earth-Moon geometry like cyclers (evident in the rotating frame).

Very Interesting Orbits: Actual non-planar cyclers.
