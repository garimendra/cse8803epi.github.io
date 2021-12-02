## Predicting DogeCoin Price Bubbles using Epidemic Modeling

For CSE-8803 : Data Science for Epidemiology by Dr. B. Aditya Prakash, Fall 2021

## Meet the Authors

![Authors](images/Gary-and-Surya.jpeg)


## Motivation 

Previously, researchers used only social media data as an indicator to predict cryptocurrency prices<sup>1</sup>, but the results proved insufficient to make the profits. The reason behind this is the volatility and price bubbles of the crypto market. There has also been some research on how cryptocurrency price bubbles have previously been linked with the epidemic-like spread of an investment idea.<sup>2</sup> The idea is similar to how epidemic diseases spread when infected by a virus; a cryptocurrency market may boom or burst when infected with an investment idea. In predicting such epidemic diseases, especially influenza monitoring, researchers utilized Hidden Markov Model to detect the pandemic in an early stage<sup>3</sup>. 


The intuition behind this project is to study the application of previous works from epidemiology on different domains other than Epidemiology. This project aims to extend the idea of the hidden Markov model's usage in the early detection of Influenza disease to the cryptocurrency market. We chose the cryptocurrency market because there is a direct correlation as to how the price of a crypto market booms/bursts similar to an epidemic disease. The novelty of our idea is we want to show how previous research work of unique mathematical models in Epidemiology can easily extend to different domains. We also wish this project gives enough motivation to utilize the previous work done in epidemiology in various fields other than Epidemiology. A detailed approach and further practical details about the project are discussed in the next section. 

## Approach 

The crypto market is prone to sudden changes due to new investment ideas in the market. In order to best study this behaviour we attempted to predict doge coin price bubbles. As explained in the previous sections, crypto price bubble comprises of five phases in the following order: 
1. Displacement 
2. Boom 
3. Euphoria 
4. Profit 
5. Panic. 

To efficiently predict the doge coin bubbles, we need a model that detects boom, euphoria and panic phases in the market as early as possible. To achieve this we are extending the work of M. A. Martínez-Beneit<sup>3</sup> for early detection of influenza pandemic to doge coin. We are using an HMM model that is previously been used on influenza data to successfully detect early stages of doge coin market.

![Flowchart](images/twint.png)
Fig 1: Experiment Flowchart
<br/>


As seen from the above image when an influenza time series data is trained on Hidden Markov model, the algorithm can successfully detect hidden states in between low-epidemic and high-epidemic states. Researchers used those hidden states to detect the disease even before happening. This similar approach of early detection of influenza is used in this project to detect early rise in the price of doge coin. First, we tried to predict doge coin price bubbles using epidemic modelling, later we are tried to find the effect of influenza and covid data on the price of doge coin. 

![Flowchart](images/Unknown-4.png)
Fig 2: Influenza data when trained on HMM
<br/>


## Relevant Links 

- [Final Report](https://drive.google.com/file/d/1MhoiAz3_2MDQOiOYE7UcwHhRJxTtzRvH/view?usp=sharing)
- [Final Presentation - PDF](https://drive.google.com/file/d/1pPAi0ffFLkBYbETMkNLE2i8Op0lq_yU9/view?usp=sharing)
- [Final Presentation](https://docs.google.com/presentation/d/1aIgEpqu9d1Orh7cUOoqaYWTyHVXob2ES/edit?usp=sharing&ouid=108530677477326081924&rtpof=true&sd=true)
- [Software Files](https://drive.google.com/file/d/1oEyzDL44sp8EAOPQ17Of0syf-rd2zqGf/view?usp=sharing)



## Results

![Flowchart](images/HMM.png)
Fig 3: Study of HMM on influenza and covid data
<br/>

![Flowchart](images/Unknown-7.png)
Fig 4: Study of HMM on Social Media Sentiment
<br/>

![Flowchart](images/DogeVsTwitter.png)
Fig 5: Twitter Sentiment vs Doge Coin
<br/>

## References 

1. Georgoula, Ifigeneia; Pournarakis, Demitrios; Bilanakos, Christos; Sotiropoulos, Dionisios N.; and Giaglis, George M., "Using Time-Series and Sentiment Analysis to Detect the Determinants of Bitcoin Prices" (2015). MCIS 2015 Proceedings. 20.
[Link](https://aisel.aisnet.org/mcis2015/20)
2. Shtatland, Ernest & Shtatland, Ma. (2008). Another Look at Low-Order Autoregressive Models in Early Detection of Epidemic Outbreaks and Explosive Behaviors in Economic and Financial Time Series. 363-2008. 
[Link](https://www.researchgate.net/publication/228984995_Another_Look_at_Low-Order_Autoregressive_Models_in_Early_Detection_of_Epidemic_Outbreaks_and_Explosive_Behaviors_in_Economic_and_Financial_Time_Series)
3. Martínez-Beneito MA, Conesa D, López-Quílez A, López-Maside A. Bayesian Markov switching models for the early detection of influenza epidemics. Stat Med. 2008 Sep 30;27(22):4455-68. doi: 10.1002/sim.3320. PMID: 18618414.
[Link](https://www.uv.es/mamtnez/Influenza.pdf)


