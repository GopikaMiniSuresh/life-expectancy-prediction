# life-expectancy-prediction

Life expectancy is a statistical measurement used to estimate an individual's lifespan. 
On an individual level, life expectancy is crucial in determining one's plans, support and care. On a larger group level, it holds paramount socio-economical implications.
On a country level, it is used to derive insights, analytics and further studies to better understand the needs & risk factors of populations. 

INPUT - The data has been provided by WHO, and it contains records between 2000 and 2015 across 183 countries. 

One of the main focuses of this project is data integrity. Several countries have previously expressed concerns with sharing some of their sensitive data, such as medical records, as they brought about unwanted financial implications when correlated with their quality of life measurements and hindered social developments. 
As such, the task is to construct two models: One that uses the least information necessary to make a prediction, as well as a more elaborate one that can be used if states decide to share more sensitive data.
Part of this task will be to use our own judgement as ethical data practitioners to determine which features may/should be used.

OUTPUT - a function that takes in relevant population statistics (features) and makes a prediction on the average life expectancy. 
The function should also prompt "Do you consent to using advanced population data, which may include protected information, for better accuracy? (Y/N)" to decide which model is to be used.
