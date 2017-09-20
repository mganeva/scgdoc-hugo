+++
title = "Cylinders in Born Approximation"
weight = 11
+++

### Cylinders in Born Approximation

Scattering from a monodisperse distribution of cylinders using the Born approximation.

* The cylinders are all identical with radii and heights equal to 5 nanometers.
* The wavelength is equal to 1 Å.
* The incident angles are equal to αi = 0.2° and Φi=0°.
* There is no substrate (particles are embedded in the air layer), hence no refraction, hence no distorted waves, hence DWBA boils down to regular Born approximation.
* Scattering is not affected by inter-particle correlations (dilute-particles approximation).

{{< load-photoswipe >}}

{{< gallery >}}
{{< figure link="../CylindersInBA.png" caption="Intensity image">}}
{{< figure link="../CylindersInBA_setup.jpg" caption="Real-space model">}}
{{< /gallery >}}

{{< highlight python "linenos=table">}}
{{< readfile file="/content/documentation/bornagain/python-examples/embedded-particles/CylindersInBA.py">}}
{{< /highlight >}}