This project is designed to study supernova Type Ia (SNIA) light curves and estimate characteristics leading to understanding their peak intrinsic brightnesses. The methods of doing these have been devised and practised for a couple of decades now.  But we want to do this for the most modern datasets which are (a) large and (b) different in that they have better photometry (light curves), but don't have spectra.

Traditionally, light curves have been used to estimate the intrinsic brightness of supernovae Type Ia, whereas spectra have been used 
a. to obtain 'redshift' of the supernovae, which tells you how much expansion of the universe has happened since the supernova exploded
b. Classify the type of SN and confirm that they are Type Ia. 
You can get a better sense of how spectra have been used to obtain redshifts and how only some of this information is available in light curves. Thus doing this from light curves is harder, but not impossible.

In the absence of spectra, we will be using light curves to also do these two functions. In particular, during this project, we will work on obtaining redshift
from these light curves. The goals of this project would be to use our existing tools (many of them based on .. SNCosmo: http://sncosmo.github.io, check out
the documentation in .. SNCosmo_docs: http://sncosmo.readthedocs.org/en/v1.1.x/ ). More generally, the problem of inferring redshifts from only the photometry of astrophysical objects is well known beyond supernovae, and is studied in great detail for galaxies. This process of recovering photometric redshifts (as it is often called) in galaxies is often plagued by the problem of "catastrophic failures", where a number of outliers are found to be very different from inferred values compared to inferred uncertainties. Once SNIa have been identified, one might expect the problem to be easier, but the status is not very clear.

- Build statistics of how well these tools and some new modifications do in inferring both the redshift and light curve characteristics from the light curves.
- Try to understand the cause of 'failures' if significant. For the cases we will study, these may be related to a. the kind of prior used b. Multiple solutions c. Finiteness of model spectrum. Characterizing the cause could open up the ways to improve this.

Feel free to discuss this more either by emailing us at lisaleemcb@gmail.com, rbiswas4@gmail.com or by using the issues feature of this repository.
