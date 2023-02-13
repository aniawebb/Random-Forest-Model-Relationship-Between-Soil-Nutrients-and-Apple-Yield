# Random Forest Model Relationship Between Soil Nutrients and Apple Yield

# Abstract
In an ever-changing climate plagued by the proliferation of global warming and with economic inflation rampant across the United States, farmers need to make agricultural decisions to save money and sustain crop yield. Using soil nutrient data along with fruit count information from Washington Fruit’s Grandview Smart Orchard courtesy of Innov8.ag, this project investigates if certain soil variables are correlated with apple yield via Random Forest implementation in JupyterNotebook. Moreover, this project runs the Random Forest model workflow twice for fruit count data from 2021 and 2022. It was determined that elevation was the top predictor over both years and sodium was also deemed important (ranked 2nd in 2021, and 3rd in 2022).

# Methodology 

<img width="213" alt="image" src="https://user-images.githubusercontent.com/99928235/218530070-d69ce544-b037-49ec-9233-d1332b6897ea.png">

# Discussion / Conclusion

This study showed some interesting findings in terms of soil nutrient variables relationship to apple yield, both in the 2021 and 2022 data. In the model for 2021 and 2022, the Random Forest Regressor found elevation to be an important predictor of apple yield. This is further interesting because of the nature of the yield data from 2021 and 2022. This apple orchard shows clear patterns of biannualism. This means that the apple trees which produced one year do not produce the following year, and vice versa. This is shown through the switching of polygon colors from yellow to purple or purple to yellow (seen in the script). This makes the results from the Random Forest models even more interesting because despite the yield production shifting from certain trees to others in the field, elevation still remained an important predictor for these newly producing trees.

No study is without faults or room for improvement, however. Given more time and more data, I would home in on the 2021 model and explore methods to improve overall model accuracy and importance. For instance, I would perhaps remove the least significant variables from the model, such as manganese or clay. I would also try to alter the train/test split methodology from the default conditions to see if any improvements to the model are made. 

