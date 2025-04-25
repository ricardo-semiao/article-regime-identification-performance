# Introduction

This document is a plan for the project.

I intend to do a methodological study comparing forecasting models with regime changes. The idea is to choose a financial/macroeconomic variable, present in a context of regimes, and use it as a backdrop to compare the results of the models considered.

I intend to interpret the different regimes that each model generates, and how this can relate to the observed performance.

To do this, I want to present the regime comparison metrics present in the research project that I sent you. I will not derive their statistical characteristics in depth, but I will define them formally and show their usefulness in identifying which models generated more or less different regimes. Then, I will show whether or not this information is useful for selecting and interpreting the models.

That is, the research question would be something like “What is the difference in performance between regime models in predicting variable x, and how can it be explained by the difference in regimes?”

I intend to consider regimes modeled by Markov switching, thresholds, structural breaks, and clustering.

The above is the basic idea, but I intend to bring some features, if possible:

- Carry out a ‘complete’ forecasting work, paying close attention to the selection and treatment of variables, selection and comparison of models, etc.
- High-dimensional data (and models), possibly including with ‘alternative’/original sources (text as data, web scrapping, etc.).
- Purchase regime models, in general, with time varying parameter models.


# Possible Variables

Central Bank Sentiment:

- [Understanding sentiment shifts in central bank digital currencies](https://doi.org/10.1016/j.jbef.2024.100988)
- [Unveiling the sentiment behind central bank narratives: A novel deep learning index](https://doi.org/10.1016/j.jbef.2023.100809)
- [Estimating Central Banks’ preferences from a time-varying empirical reaction function](https://doi.org/10.1016/j.euroecorev.2005.10.003)

Sentiment and stock volatility:


Other sentiment variables.

Regime breaks as identification variables. Maybe a metric of if a change was not smooth so that it can be used as a identifying schok. In the context of volatility: https://consensus.app/papers/uncertainty-across-volatility-regimes-angelini-bacchiocchi/f78850e8b9ae5295b15c65417777d979/.

Sentiment has an effect on short term interest rates: https://doi.org/10.1016/j.irfa.2024.103293

Model with both volatility and uncertainty to determine the regimes. They find that realized volatility is best characterized by a four-regime structure in which macroeconomic uncertainty predicts realized volatility across regimes and is a threshold that determines regime switches. https://doi.org/10.1016/j.econmod.2023.106483