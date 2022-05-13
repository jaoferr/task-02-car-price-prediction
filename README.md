# task-02-car-price-prediction
Kaggle Community competition - Task 02 - Car Price Prediction

## <a href="https://www.kaggle.com/competitions/task-02-car-price-prediction" target="_blank"> Kaggle Community competition - Task 02 - Car Price Prediction </a>

Solução desenvolvida na disciplina Aprendizado de Máquina - I, durante o 5º termo da graduação em Ciência de Dados da FATEC Ourinhos.

---

<i> Descrição no Kaggle </i>

# Project 02 - Car Price Prediction
For this challenge, you guys are now OLX employees, congratulations!

OLX is expanding its services to India and has made your team responsible for all the data science matters. Your new supervisor, Radirk Tumasali, has commented that most Indians, when selling their old cars, don't know the estimated price they can use when advertising on OLX. This seems to happen because the Indian version of the website still doesn't have many cars available for sale. In this case, the sellers often go to the competitor platform CarDekho to get an estimated value of the price and ended up staying there.

To solve this issue, Radirk proposed:

```Let's create an "estimated selling price" feature on the website!```

Then, Radirk web scrapped the Car Dekho platform for getting samples of cars that were on sale and got the following available features for each vehicle:

| Name | Year | Selling Price | Km Driver | Fuel | Seller Type | Transmission | Owner | Mileage | Engine | Max Power | Torque | Seats |

Now, your team needs to develop a model that can propose a suggested selling price for when a new user registers a car on the OLX platform.

All the models are going to be evaluated on the R2 Score between the prediction/estimated value of the model and the test set ground truth. You are free to choose any regression algorithm as well as pre-processing and data splitting strategies.

References
https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho
