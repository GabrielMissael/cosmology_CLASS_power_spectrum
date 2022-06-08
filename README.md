<p align="center">
    <img src="https://i.imgur.com/NNrhhjz.png" alt="Image" width="70%"/>
</p>

# Cosmology: Project 2.

## Power Spectrum variations in $\Lambda CDM$ cosmology.

**Prof. Alma Xochitl Gonzalez Morales**

**By: Gabriel Missael Barco**

The notebook in this repository performs a power spectrum analysis in the $\Lambda CDM$ cosmology. It solves the cosmology for different parameters configurations and plots the result of the power spectrum. The default parameters values are:

- $h = 0.67810$ - Dimensionless reduced Hubble parameter ($H_0 / (100km/s/Mpc)$)
- $T_{cmb} = 2.7255$ - CMB temperature ($K$)
- $\Omega_{b} = 0.02238280$ - Reduced baryon density ($\Omega h^2$)
- $\Omega_{cdm} = 0.1201075$ - Reduced cold dark matter density ($\Omega h^2$)
- $\Omega_{k} = 0.0$ - Curvature density
- $\Omega_{\Lambda} = 1 - \sum \Omega_i$ - Cosmological constant density

In each plot, we vary one of the parameters to see the corresponding variation of the power spectrum. In the case of matter-energy densities, we vary $\Omega_{\Lambda}$ at the same time as any other given $\Omega_i$ (so that they add up to 1).

To run the notebook, you need to install the [`CLASS`](https://github.com/lesgourg/class_public/wiki/Installation) package, and run the notebook from inside the `class` directory. Also, ther must be a `image` directory outside the `class` directory, where the plots will be saved.

----

## Gallery.

1. Varying the Hubble parameter:

<p align="center">
  <img alt="Image" src="https://i.imgur.com/rd7T7cA.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="image" src="https://i.imgur.com/nQ4l3nF.gif" width="45%">
</p>

2. Varying the CMB temperature:

<p align="center">
  <img alt="Image" src="https://i.imgur.com/zAz2v03.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="image" src="https://i.imgur.com/XRLOyJS.gif" width="45%">
</p>

3. Varying the baryon density and the cosmological constant density:

<p align="center">
  <img alt="Image" src="https://i.imgur.com/WowdxuZ.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="image" src="https://i.imgur.com/JVtZUOX.gif" width="45%">
</p>

4. Varying the cold dark matter density and the cosmological constant density:

<p align="center">
  <img alt="Image" src="https://i.imgur.com/O8zdyaJ.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="image" src="https://i.imgur.com/0TlbBYl.gif" width="45%">
</p>

5. Varying the curvature density and the cosmological constant density:

<p align="center">
  <img alt="Image" src="https://i.imgur.com/VpnAMYb.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="image" src="https://i.imgur.com/M1QQg4h.gif" width="45%">
</p>

