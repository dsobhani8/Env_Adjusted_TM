# Env_Adjusted_TM

08/18:

No datasets are included in this repo; however, within the models there is a description of how to upload personal datasets. Furthermore the number of K topics, epochs, and scale values for the horseshoe prior could all be improved and depend on specific use case. The number of samples in the Monte Carlo KL-divergence calculation can increase, and will likely lead to better capturing environment specific information; however, it is also more computationally expensive.

The stopwords are specific to the Zurich channels dataset.

The results in the model iii colab reflect the performance of the model when trained on a dataset of NBC, FOX, and CBS data, and tested iid.
