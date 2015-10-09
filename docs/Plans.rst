Rough Plan for Fall Quarter
===========================

We will have the software that you need already installed on the machines that you will be using. If you want, you can also install the software on your own machines. It should be fairly easy, but of course, we will help if necessary.

- Talk about the kind of datasets we are discussing. What is time, flux, bandflux, filters. How are these represented in the code. What model are we using. How are the results of the models used. Be able to get a few examples, understand and plot the datasets. Use the SNCosmo documentation, fitting tutorial and discuss with us.
- Make sure you know the examples for inferring the light curve parameters from  the Fitting Tutorial. Work out the standard case of doing this for the case where the only unknowns are $\{x_0, x_1, c, t_0\}.$  How do you compare the inferences to the known values of the parameters (because you are using simulated data)
- How do you do this for a large number of SNIa?
- Assume that you do not know the redshift  of the supernovae. This will add an extra parameter $z$ to the list of model parameters. Try the methods of inferring these unknown parameters simultaneously. How do we do for a large number of SNIa?
- If there are a number of outliers, try to use nestlc (using the multi-ellipsoid method) to see if it performs better?
- Improve the prior model by correlating $z-x0$ to see if we can improve this? 
