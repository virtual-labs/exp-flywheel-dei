## Procedure

### In real Laboratory

1. Rotate the flywheel to ensure that it can rotate smoothly. Oil the bearings if required. Estimate the minimum number of slotted masses required to move the flywheel from rest.
2. Measure the diameter of the axle using a scale or vernier callipers. Determine the radius $r$ of the axle by dividing the diameter by 2.
3. Wrap the string around the axle by rotating it until the weight is at point A, just below the axle, and hold it. Ensure the length of the string is such that it becomes detached from the axle when the mass strikes the floor at point B. Note the number of windings of string around the axle, denoted as $N_{1}$.
4. Measure the distance between point A (initial position of mass) and floor point B (final position of mass). This distance is $h = 2\pi r N_{1}$. Make a marking on the rim of the wheel to enable counting of the number of revolutions of the wheel during the experiment.
5. Allow the weights to fall down till it touches the ground. Start the stop-watch just when the weights touch the ground.
6. Count the number of rotations $N_{2}$ before the flywheel comes to rest. Record the time $t$ taken for the flywheel to stop completely. The timer should be stopped when the flywheel ceases to rotate.
7. Tabulate the results for each trial, including the values of mass $m$, number of windings $N_{1}$, height of fall $h$, number of post-detachment rotations $N_{2}$, time $t$, and the calculated moment of inertia $I$.
8. Repeat the experiment multiple times with the same or different masses and fall heights to ensure accuracy and obtain multiple data points.
9. Calculate the value of mass moment of inertia in each trial using the derived formula. Then, calculate the mean moment of inertia of the flywheel from all trials and compare with the theoretical value.

### In the simulator

In a real experiment, the theoretical mass moment of inertia is estimated by measuring the approximate mass of different simplified geometrical components and adding the mass moment of inertia about the central axis from the known equations of moment of inertia of rings, cylinders, rods, etc. In the simulator, the theoretical mass moment of inertia is directly calculated using the variables for determining volume and density.

1. Use sliders to control the Initial Setup to calculate the Theoretical Moment of inertia of the flywheel system. Moment of Inertia be calculated based on radius of flywheel $R$, thickness of the flywheel $t$, radius of axle $r$, length of axle $l$, density of material $\rho$ and acceleration due to gravity $g$. (Provision for locking the Moment of Inertia to be incorporated. (LOCK))
2. Use the sliders to control experimental setup (mass of the slotted weights $m$, number of windings $N_{1}$/height of fall $h$)
3. Allow the mass to fall down by clicking the PLAY button.
4. The simulator starts counting the rotations and time after the mass has touched the ground using a digital counter and stopwatch respectively.
5. As the simulation stops the result will display.

<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    displayMath: [['$$', '$$'], ['\\[', '\\]']]
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
