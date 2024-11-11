
# Name and contact
Name: Fengran Wang 

Email： fengran.wang@emory.edu
# The question number you select to answer
Question number: hw1

# Key insights
SIR and SEIR models help us to understand the impact of different interventions (social distancing, etc.)
on the spread of a pandemic.
We can know how different combinations of transmission and recovery rates affect the pandemic.
They provide a scientific basis for public health interventions.

# Comparative model performance
SIR Model is suitable for disease spread without a latent period; simple but less accurate.

SEIR Model introduces an exposed (E) compartment, making it better suited for diseases with a latent period,
and the simulation results are closer to real-world scenarios. 

Therefore, in SEIR Model, the infection peak is slightly delayed and exhibits gradually weakening waves, which is more accurate than SIR model.

# Relevance to model-based machine learning
When we build a machine learning model for epidemiology, we can integrate compartmental models(SIR, SEIR) with it,
which can enhance prediction accuracy, simulate scenarios, and evaluate interventions.

# Suggestions for future modeling improvements
- Use real-world data to optimize model parameters for greater accuracy.
- Introduce more variations (temperature, season, vaccine, etc.) to account for real-world.
- Combine with some machine learning models (CNN+LSTM) for time-series forecasting.