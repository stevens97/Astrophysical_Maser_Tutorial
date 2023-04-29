# HartRAO Astrophysical Maser Tutorial


<img src="http://www.hartrao.ac.za/gallery/ltg021023c.jpg" width="50%" height="50%">
Photo credit: http://www.hartrao.ac.za/gallery/ltg021023c.jpg
---------------------------------------------------------------------------------------------------------------

<img src="https://mcdonaldobservatory.org/sites/default/files/images/news/gallery/salt.startrails.jpg" width="50%" height="50%">

This Jupyter Notebook provides a tutorial of how Astrophysical Maser Data (observed with the HartRAO telescope) can be reduced, processed and visualised.

## What are Astrophyiscal Masers?

Astrophysical masers are natural sources of microwave and radio-frequency radiation that emit intense, coherent beams of light. They are produced by a process called stimulated emission, in which molecules in a gas are excited by collisions or radiation and then emit photons of the same energy and frequency as the incident radiation.

In astrophysical environments, masers are commonly found in regions of intense radiation, such as around young stars, evolved stars, and active galactic nuclei. They can provide important information about the physical conditions and dynamics of these regions, including the temperature, density, and velocity of the gas and the magnetic fields that may be present.

Some of the most commonly observed astrophysical masers include water vapor masers, which are found in regions of star formation and in the envelopes of evolved stars, and methanol masers, which are associated with massive star-forming regions. Other types of masers include those produced by molecules such as OH, SiO, and HCN.

## What is the HartRAO radio telescope? Why is it a good instrument for observing Masers?

The HartRAO (Hartebeesthoek Radio Astronomy Observatory) telescope is a radio telescope located in South Africa that is used for a variety of astronomical observations, including the study of astrophysical masers.

To gather data about masers, the telescope is typically pointed at a specific region of the sky where the masers are expected to be found. The telescope collects the radio-frequency radiation emitted by the masers and focuses it onto a receiver, which converts the radiation into an electrical signal that can be analyzed by astronomers.

The receiver is typically tuned to a specific frequency corresponding to the frequency of the maser emission. The signal is then amplified and processed to remove any unwanted noise or interference, and the resulting data is recorded and analyzed to extract information about the properties of the masers and the astrophysical environments in which they are found.

HartRAO is particularly well-suited for studying masers because it has a large dish with a diameter of 26 meters, which provides a high sensitivity to weak radio signals, and it is located in a relatively radio-quiet area, which reduces interference from terrestrial sources.

## How does this program work?

This program takes 4 observations of the same Astrophysical Maser,
(1) Left-circularly polarized observation #1
(2) Left-circularly polarized observation #2
(3) Right-circularly polarized observation #1
(4) Right-circularly polarized observation #2

And applies the following single-dish observational techniques to process the data:

Technique #1: Bandpass correction
Technique #2: Frequency switching
Technique #3: Baseline subtraction

The script than finally averages out the observations to obtain a single spectra for the observed Astrophysical maser.

## Prerequisites for using this program:

- astropy v 3.2.1
- matplotlib v 3.0.3
- seaborn v 0.9.0

**NOTE**: Original data is not provided due to copyright/privacy.
This code is for educational purposes only.

## References:

- Burke, B.F., Graham-Smith, F. and Wilkinson, P.N., 2019. An introduction to radio astronomy. Cambridge University Press.
- O'Neil, K., 2002. Single dish calibration techniques at radio wavelengths. arXiv preprint astro-ph/0203001.

For more on the HartRAO telescope and Astrophysical Masers, see: http://www.hartrao.ac.za/spectra/SP_Publs.html
