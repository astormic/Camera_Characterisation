<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Camera characterisation

_The practical measurements for characterising the camera for noise correction. I'm transferring details from my notebook to this but it takes time. Meanwhile, you can reach out if you want to comment on something or suggest an experiment._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Converting the grey values to the number of electrons
To convert the electron value given by each pixel to the number of photons received in each pixel.

Number of electrons = (Grey value - Bias)*Gain

## Converting the number of electrons to photon flux
Number of photons = Number of electrons/QE in decimal

QE for 647nm wavelength for Prime BSI Express camera is 90%.

## BIAS Measurements
Number of photons = Signal in Electrons/QE in decimal

## GAIN Measurements

## Read noise calculations

## Signal to noise ratio calculations

   
## FAQs: 
**What specifications from the camera manufacturer are required?**
 
<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Feedback: [Create a pull request]()

This work is licensed under a
[Creative Commons Attribution 4.0 International][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: https://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

</footer>
