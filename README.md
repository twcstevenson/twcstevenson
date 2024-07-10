Howdy, I'm Thomas from Perth. Thanks for dropping by!
My scripts are useful for modelling meteoroids as they fall through Earth's atmosphere. They are mostly self-contained; check below for any external modules that need to be downloaded in advance.
Also, I do most of my work in Jupyter notebooks. If you need a certain script in a different format, and it isn't here already, just send me a message or email tom.william.stevenson@gmail.com  :)

Here's what I have uploaded so far:

'Imaginary Meteors' (last updated 10 July 2024)
Simulates a population of as many meteoroids as you like! Different compositional groups are modelled based on density and ablation coefficient, which you can change.
Other parameters, such as entry mass, height and velocity, are randomly generated within limits derived from real observations.
The script uses a simple ablation model to determine the flight path of each meteoroid, giving you a realistic view of how many in the population survive all the way to the ground.
It also returns maximum dynamic pressure values, which indicate the mechanical strengths of your meteoroids.
Give it a try and let me know what you think!

'Alpha Beta Stevenson' (last updated 10 July 2024)
A simplified version of Dr Sansom's trajectory modelling script used by Australia's Desert Fireball Network.
Given sufficient time, height and velocity data from a real events observed by fireball cameras, this script
uses an optimisation function to calculate the ballistic coefficient (alpha) and mass loss parameter (beta)
of the object being observed. Alpha and beta can then be used to calculate important properties of the object,
such as its entry mass, size, velocity and ablation coefficient.

'Mass Loss Simulator' (last updated 10 July 2024)
Beefier version of the ablation simulator included in Imaginary Meteors. It correctly predicts the trajectory and generates a simple light curve for a simulated meteoroid, given its entry state.
Provides close matches with the trajectories of real meteoroids, such as the Winchcombe and Tekapo falls, but over-estimates terminal mass because fragmentation is not accounted for.
Can be used to estimate the survival chance of a particular event, such as the 2023 Queensland fireball, which may have dropped meteorites.
