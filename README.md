Code repository for the University of Edinburgh Statistics with Data Science MSc Dissertations:

# Property Type Classifications (Simply Business)
In 2022, nearly 18 million UK home insurance policies were purchased online (Gibbs, 2023). Insurers rely on physical property 
characteristics when they estimate insurance premiums. It is infeasible for insurers to physically collect property data for every 
prospective client when providing insurance premium estimates - the volume of online policy purchases is too great. How e↵ective can 
publicly available data be leveraged to estimate essential property characteristics such as property type?

We propose a convolutional neural network (CNN) model for image classification of Google Street View images, and find that the CNN model
has an accuracy rate of 37% when used for classifying new property images. Based on this poor accuracy rate, we recommend only making
classifications with Google Street View images when no other data collection method is available (real estate listings, surveying the 
client directly, etc.). We propose two methods for improving the quality of Google Street View image data - discretising the ”Unknown”
class into subgroups, and collecting multiple images at different angles for each property.


# Forecasting Earthquakes
Earthquakes continue to cause catastrophic losses to both human life as well as critical infrastructure, despite the efforts of 
government agencies and scientific communities around the world. Predicting individual earthquakes using today’s seismological models and technology remains a challenging task. However, aftershocks can be probabilistically forecasted — though they continue to present 
significant risks. A powerful framework for understanding the temporal and spatial evolution of aftershocks is the Epidemic-Type 
Aftershock Sequence (ETAS) model, which comes in different forms and can be approximated with various means.

We aim to inform scientists or government offi cials on when and how best to leverage the type of ETAS model implemented in the R package
INLABRU. Analysis is carried out with historical earthquake data from the Italian Seismological Instrumental and Parametric Database.
In particular, we find that:

1. The number of events, the time of the first large event (magnitude 4 or greater), and the amount of clustering within an earthquake
   sequence are all highly indicative of the reliability of the resulting parameter estimates.
2. For overall model reliability, the most important ETAS model parameters to estimate correctly are alpha and p
3. Synthetic data can behave similarly to real data with the right parameter specifications.
4. The ramifications for incorrectly estimating parameters can be simulated using synthetic datasets.
