# Spaceship-Titanic
En este proyecto se entrenaron varios mmodelos de clasificación basados en la competencia de Kagle llamada Spaceship Titanic. La competencia consta de entrenar un modelo de clasificación para predecir una variable de salida dentro del contexto que se plantea. El contexto y detalles específicos se encuentran en la página del concurso. Específicamente en este proyecto, se utilizaron métodos de feature engineering para preparar y ajustar los datos previo a la generación del modelo. Se crearon 4 modelos (Logistic Regression, LDA, Decision Tree, Random Forest) para finalizar con un ensamble de los 4 el cual es el modelo final utilizado para las predicciones.

Las variables son las siguientes según la página oficial:
- PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
- HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.
- CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
- Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
- Destination - The planet the passenger will be debarking to.
- Age - The age of the passenger.
- VIP - Whether the passenger has paid for special VIP service during the voyage.
- RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
- Name - The first and last names of the passenger.
- Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

En este proyecto se encuentran los siguientes documentos:
- [Reporte ipynb](PP2_611858.ipynb)
- [Reporte html](PP2_611858.html)
- [Base de datos de entrenamiento](train.csv)
- [Base de datos de prueba](test.csv)
