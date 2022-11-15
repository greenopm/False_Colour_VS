# False_Colour_VS
For the production and processing of low feature, false-colour shaded vibrational spectroscopy maps

# Background: 
In vibrational spectroscopy (infrared and Raman spectroscopies), wavelengths of light are linked with specific molecular bonds. By emitting light onto a sample and detecting the photons that come back (under the correct conditions), the samples molecular composition can be determined non-destructively and without molecular labelling.

By sampling over an area using vibrational spectroscopy, the distribution of a molecules detected over that area can be plotted, producing a vibrational spectroscopy map. 

False-colour shading associates a colour with a spectral feature (wavenumber, ratio of wavenumbers, or spectral range), and shows the intensity of feature over the mapped area, relating the colour intensity to the feature prominence.

False-colour shaded vibrational spectroscopy maps can therefore be relatively simple to interpret when compared to hyperspectral images, especially when a single feature is being visualised.

To visualise two or more features false-colour shaded features in the same map, typically the lower intensity regions of one or more features is made transparent, allowing distributions for other features to be seen. By removing sections of one false-coloured feature, boundaries can be formed to highlight target regions within the vibrational spectroscopy map.

The formation of maps consisting of two or three features (low feature) vibrational spectroscopy maps using false-colour shading therefore raises the question, within high accuracy contexts such as academic or industrial research; how to determine the most accurate, objective, and repeatable shading parameters to produce boundaries within vibrational spectroscopy maps, as highlighted by Ashton et al [1].


# Aims:
- To produce python modules that once combined provide a python package capable of objectively and repeatably determine boundaries within vibrational spectroscopy maps (with an initial focus on Raman maps of single HaCaT cells)
- To include modules for the processing of vibrational spectroscopy maps, including pre-processing, background removal, feature selection, and feature layering.


Reference:
[1] L. Ashton, K. Hollywood, & R. Goodacre, "Making colourful sense of Raman images of single cells",  Analyst, V. 140, 2015, pp. 1852-1858, DOI: 10.1039/C4AN02298J
