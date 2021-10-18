# Energy Potential Diffusion Simulation

In literature, the heterogeneous conformations of a biomolecule (e.g. protein or DNA) are often combined in an one-dimensional energy landscape. In this landscape conformational states are energy wells separated by barriers. Interconversion dynamics between these conformational states are then described by diffusion within the energy landscape. 

In this simulation package several types of one-dimensional energy landscapes are provided such as a harmonic, quartic, sinusoidal and custom built potential. State trajectories are simulated by Langevin dynamics using the gradient of the selected energy landscape. The script also evaluates the passage time between two reaction coordinates, enabling e.g. the detection of the transition path time, the time needed to overcome the energy barrier.

<p align="center">
![Equation](https://user-images.githubusercontent.com/58071484/137738308-d6881a79-d1a1-4096-99b3-b96e57e12e9e.JPG)
</p>

### Selection of the energy landscape

Choose between an harmonic, quartic, sinusoidal or custom built energy landscape by selecting the corrsponding model function in the main script. Feed the model function with the necessary features of the energy landscape.

![simNRJDiff_Figure1](https://user-images.githubusercontent.com/58071484/137720336-c499caca-533c-4e00-8c06-2379855c89da.png)

### Simulation output

![simNRJDiff_Figure2](https://user-images.githubusercontent.com/58071484/137707404-58e4e83a-afaf-4015-bbdd-ccb9bb040450.png)
