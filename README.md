
<p>
	<img src="https://img.shields.io/badge/maintenance%20status-deprecated-red"
			alt="Maintenance">
</p>

_(**Currently under construction** 🏗)_

# MatLab-Simulink MSEIRD epidemiological model for CoViD-19 hidden variables inference

## Project abstract
The project consists of a Simulink system that aims at creating a realistic [_MSEIRD model_](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology), in which the hidden variables that influence the _Transition rates_ such as γ and _β_, are shown and can be manipulated to infer their actual values comparing the model output variables with the real ones gathered from real world data, such as those from [_COVID-19 (WHO data)_](https://covid19.who.int/).


## MSEIRD Compartmental model
[_Compartmental models in epidemiology_](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)
_**MSEIRD**_ is an acronym that represents the different stages of exposure to an epidemic for a certain population. The model in not uniquely defined and the differential equations defining it can be rearranged to better suit the use case depending on the variables we wish to display.
- _**S(t)**_ is used to represent the individuals **susceptible** to the disease at time _t_.
- _**E(t)**_ For many important infections there is a significant latency period during which individuals have been infected but are not yet infectious themselves. During this period the individual is in compartment _E_ for **exposed**.
- _**I(t)**_ denotes the individuals of the population who have been **infected** with the disease and are capable of spreading the disease to those in the susceptible category.
- _**R(t)**_ is the compartment used for the individuals of the population who have been infected and then **recovered** from the disease, due to **immunization**. Those in this category are not able to be infected again or to transmit the infection to others. Can be extended to **vaccinations**.
- _**D(t)**_ is the compartment used for the individuals of the population who have been infected and then removed from the disease, due to **death**. Those in this category are not able to be infected again or to transmit the infection to others.
- _**M(t)**_ is a class for **maternally derived immunity**, can be extended to **vaccinations**.

### Vaccinations
Vaccinations can be added in a few different classes, or be separated in a new one; in both cases, as for what _CoViD-19_ data showed, vaccinated people will not stay immune for the rest of their life, but the period of vaccine-derived immunity tends to last from weeks to months, bringing once again part of the vaccined population to the _Susceptible_ class every day.

## Data
### Italy: PCM-DPC
Fonte dati: [pcm-dpc/COVID-19: COVID-19 Italia - Monitoraggio situazione (github.com)](https://github.com/pcm-dpc/COVID-19)
### World: WHO
[WHO Coronavirus (COVID-19) Dashboard | WHO Coronavirus (COVID-19) Dashboard With Vaccination Data](https://covid19.who.int/)

## Scelta variabili

_**TBA**_



## Licensing
The models are given **without** the pandemic data used to compare the results.
The model is provided under    license. 


## Notes

#### Project development period
22-24 Aprile 2021





