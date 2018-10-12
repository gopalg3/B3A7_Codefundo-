#Idea for codefundo++

#Drought Early Warning System (DEWS)

Over the centuries, droughts have caused tens of millions of deaths in India alone. A drought is a prolonged period of time during which there are shortages in the water supply. This water supply can be in the form of atmospheric water, groundwater or surface water. There are mainly 3 types of droughts: Agricultural, Hydrological, and Meteorological. Meteorological drought is related to the shortage of rainfall over a long period of time. Agricultural drought is related to the deficit in soil moisture, which eventually affects the crop yield. Hydrological drought is generally related to the surface run-off, stream flow or groundwater deficit.

A majority of the people in India are employed in the agriculture sector. The agriculture sector is water intensive and hence any changes in precipitation levels or groundwater levels can have drastic effects on the outputs from this sector. Crops can fail and result in great losses for the people invested in farming activities. We have chosen drought because we believe that this is a very serious issue and predicting droughts in advance can save the livelihoods of millions in our country.

We are building an early warning system that predicts in advance, the areas that are in danger of being affected by a drought. This information can then be broadcasted to the people determined to be living in the "danger zones" so that they can be well prepared for the eventuality. 

The prediction mechanism is a two-step process. The first step is to predict meteorological drought using key variables from the datasets and the second step is to use the first prediction along with other variables to predict agricultural drought. The final result is the prediction of agricultural drought along with which areas are going to be affected.

The end users of our product will be national/regional disaster management authorities who can broadcast the warnings to the people living in that particular jurisdiction and plan the future course of action.

The datasets that we plan to train our model on would most likely include the following variables: 
- Indian Ocean dipole index
- Southern Oscillation index
- Pacific decadal oscillation index
- Northern Oscillation index
- Sea surface temperatures
- Standardized precipitation index
- Local Temperature

We plan to use different machine learning algorithms like simple regression(with/without regularization), support vector regression, ensemble methods like random forest regression with gradient boosting techniques, neural networks such as RNN and MOBILENETs to train our data and then select the most accurate model considering the model accuracy and the runtime tradeoff.
