# Astro_Demos

<img src="Images/qarg_bw_dark.png" alt="QUT Logo" width="500" />

Interactive browser-based demonstrations for teaching astrophysics at QUT, developed by the QUT Astrophysics Research Group [(QARG)](https://research.qut.edu.au/qutastrophysics/). Each demo is a self-contained HTML page that runs in any modern browser with no installation, and is designed to be embedded directly into Canvas.

Companion repository: [Astro_Code](https://github.com/mjcowley/Astro_Code), a collection of Python code for astronomical analysis.

## Demos

| Demo | Description |
| --- | --- |
| [Redshift Explorer](https://mjcowley.github.io/astro_demos/redshift-explorer/) | Drag a slider to redshift a template galaxy spectrum through a set of optical and near-infrared filters. |
| [Blackbody Curve and Colour Index](https://mjcowley.github.io/astro_demos/blackbody/) | Planck curves with Wien's law, the Stefan-Boltzmann flux and a synthetic B&minus;V colour index. |
| [HR Diagram and Stellar Evolution](https://mjcowley.github.io/astro_demos/hr-diagram/) | Pick a 0.3, 1, 5 or 20 solar-mass star and evolve it off the main sequence, with a timeline of how long each phase lasts. |
| [Magnitudes and Distance Modulus](https://mjcowley.github.io/astro_demos/magnitudes/) | Move a star nearer or further to explore the inverse square law, the magnitude scale, m&minus;M and dust extinction. |
| [Exoplanet Transit Light Curve](https://mjcowley.github.io/astro_demos/transit/) | Change the planet size, orbital period and impact parameter and watch the transit dip respond, with optional limb darkening and noise. |
| [Hubble Diagram Fitter](https://mjcowley.github.io/astro_demos/hubble/) | Fit Hubble's 1929 data or a simulated modern survey to measure H&#8320; and the Hubble time. |
| [Celestial Sphere Explorer](https://mjcowley.github.io/astro_demos/celestial-sphere/) | Set your latitude, date and time to see the celestial sphere, your sky overhead, circumpolar stars and the Southern Cross. |
| [Kepler's Laws and Orbits](https://mjcowley.github.io/astro_demos/kepler/) | Change an orbit's size and shape to explore all three of Kepler's laws, or launch a planet at different speeds up to escape. |
| [Stellar Parallax](https://mjcowley.github.io/astro_demos/parallax/) | Photograph a nearby star six months apart, measure its shift and work out its distance in parsecs. |
| [Telescope Resolution and Light Collection](https://mjcowley.github.io/astro_demos/telescope/) | Split close double stars by changing aperture, wavelength and seeing, and compare light-gathering power. |
| [Solar System to Scale](https://mjcowley.github.io/astro_demos/solar-system/) | Travel outward from the Sun with sizes and distances on one scale, and build a scale model you could walk. |
| [Planet Temperatures](https://mjcowley.github.io/astro_demos/planet-temperature/) | See how distance, albedo, the greenhouse effect and the star set a planet's temperature, with the habitable zone. |
| [Jeans Mass and Cloud Collapse](https://mjcowley.github.io/astro_demos/jeans-mass/) | Change a gas cloud's temperature, density and mass to see whether gravity or pressure wins. |
| [Stellar Remnants Compared](https://mjcowley.github.io/astro_demos/stellar-remnants/) | Zoom from the Sun down to a city to compare white dwarfs, neutron stars and black holes, with a mass-radius diagram. |
| [The Expanding Universe](https://mjcowley.github.io/astro_demos/expanding-universe/) | Watch space stretch and click any galaxy to see that every observer measures the same Hubble law, so there's no centre. |
| [Cosmic Expansion History](https://mjcowley.github.io/astro_demos/expansion-history/) | Set the amounts of matter and dark energy to see a universe's expansion, age and fate, from Big Crunch to runaway acceleration. |
| [The Cosmic Microwave Background](https://mjcowley.github.io/astro_demos/cmb/) | Run back to recombination as the CMB heats up, then explore a simulated sky map from uniform glow to dipole to ripples. |
| [Galaxy Rotation Curves and Dark Matter](https://mjcowley.github.io/astro_demos/rotation-curve/) | Build a galaxy from bulge, disc and halo and fit simulated rotation-curve data to see how much dark matter it needs. |

## Embedding in Canvas

Canvas strips JavaScript from pasted HTML, so the demos are hosted here via GitHub Pages and pulled in with an iframe. In the Canvas Rich Content Editor, switch to the HTML view and add:

```html
<iframe src="https://mjcowley.github.io/astro_demos/redshift-explorer/"
        width="100%" height="900" style="border:1px solid #ccc;"
        title="Redshift Explorer"></iframe>
```

Set the height generously, since a cross-origin iframe cannot resize itself to fit its content.

## Structure

Each demo lives in its own folder with `index.html` as the entry point, which keeps the published URLs clean.

## Contributing

Contributions are welcome! If you have any ideas for improvements or new demos, feel free to open an issue or submit a pull request.

## Acknowledgements

Special thanks to all contributors and to the open-source communities that make scientific computing and data visualisation possible.