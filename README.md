# Crop Yield-er
Made as a hackathon project for Hackoverflow 2.0 organised by AI club of IGDTUW and NSUT.
---
## Domain 1. BioTech
---
## Problem Statement 2 - Crop Guidance and Farmers Friend
---

* __Given statement:__ The needs of contemporary agriculture, which demands high-yield, high-quality, and efficient production, cannot be met by conventional agricultural practices. Furthermore, farmers face the main challenge of how to adapt to changing customer preferences. It is critical to modernize existing processes and use data acquired over time to determine the best potential farming practices that should be implemented. Develop a solution that uses the potential of AI to address this problem.

#### Elaborative problem statement: The modern world has come to an era of technological revolutions in every field. But regardless of this, farmers today face many challenges in meeting the growing demand for high-quality and high-yielding crops that are able to upkeep with the changing customer preferences. They must keep up with the new advances in technology, market trends, as well as shifting customer preferences related to their diets. In addition to this, they have to address issues like climate change, water scarcity, & soil degradation. Since all of these needs cannot be met by traditional agricultural practices, it is critical to modernize existing processes & use the data acquired over time to their benefit.

#### Once the perfect harmony is achieved and variables can be predicted better by the use of our AI model, it shall become easier for any farmer to implement better practices and methods that meet the requirements of contemporary farming and agricultural practices. This model can be succesfully used to derive and predict the yield by taking in available parameters such as rainfall, average temperature and amount of pesticides used during the crop period. We provide the functionality to calculate and predict yield with a desirable accuracy

#### Our project aims at being an aid to farmers so that they can conquer the often humongous targets of contemporary agriculture. It helps the farmers in identifying the best farming practices by taking complete advantage of the conditions.

* It also gives them an idea of how to modify the current methods to increase the yield without having to increase work or labour.
* Since it predicts the crop yield, we can depend on this model to control the Demand-chain management so that there is no supply-demand fluctuations in the market.
* This helps not only the farmers but also the common people who are greatly and directly impacted by the yield and its prices, which are bound to increase sharply in case of damage to crop or unexpected yield.

---
## Challenges we ran into
---
#### We faced an array of challenges during the completion of this project. These problems were tackled head-on by my team as we progressed the model to its completion for a noble cause.
***
1. Our initial dataset, formatted in JSON, proved to be cumbersome due to its heavy size and difficulties in downloading. We really put our efforts into working with the referenced dataset but since there is a time constraint to the competition we had to proceed with a dataset from Kaggle of our chosing.
* Not only we overcame it by using a more efficient CSV formatted Kaggle dataset but the comparision and training of the model became a lot easier once we shifted which streamlined the process.
2. When building and training our machine learning model, we encountered compatibility issues with the TensorFlow on MacOS, hindering its installation process.
* As a solution, we leveraged the Google Colab notebook to make things easier.
3. The polynomial regression model, with a degree of 3, initially encountered several type and value errors that required extensive time and effort to resolve.
* To solve these errors we had to extensively trace back to a point of correctness and alter the further progressions to change the outputs and produce desirable outcomes.

### Despite the numerous challenges, we were able to achieve the required results with team work and dedication.
---
## Proposed Solution and Working of the Model
---
#### We have designed this model to overcome the problems that arise from increased demands of contemporary farming techniques that produce high-yield, high-quality and efficient production to meet the growing demands of the ever-increasing population as well as keeping up with the fluctuating requests of customers.
1. To calculate and accurately predict the yield of crops we have taken the required parameters from the dataset such as amount of pesticides being used, rainfall experienced by the crop and average temperature during the crop period. (Period during which the crop is planted and harvested)
2. We have then cleaned the dataset and removed unnecessary values or parameters for better output.
3. After which we proceeded to calculate a theta which has been proved with a graph for better understanding.
4. Finally, we have used it to predict the yield with a particular amount of accuracy for the taken amount of pesticide.

### Another point to be carefully noted is that pesticides and other chemicals should always be used in the required amount or suggested limits to avoid harmful side effects on the plants, as well as on the cattle/humans that consume them. Since they can contain heavy metals or other harmful ingredients, it is crucial to decide teh correct amount for them which can be used on the crops without any fear.
### Also, the money invested in extra or wasteful products can be invested somewhere else by the farmers which helps them as well as provides a sustainable method to maintain the environment.

### We have extensively described the working of the project in the demo video which you can find [here](https://www.loom.com/share/7d582f2a945447b18b901c8d77de732b)

### The Kaggle dataset used can be found [here](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset?select=yield_df.csv)

### You can find the link to the Google Colab notebook [here](https://colab.research.google.com/drive/10CjnkWlm-XBOgraOhhvlQRWG__rlZLZV#scrollTo=BOIcb_I4amkZ)
