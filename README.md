# Carpool Website

One of the major forms of transport in an industrial complex consists of the private passenger car. These cars are generally used with only a single rider. Because of this, it leads to increased pollution, traffic congestion (Jam), parking space constraints, wastage of time and many such anomalies. Carpooling reduces each person’s travels costs such as fuel costs, tolls, and the stress of driving. Carpooling is one method that can be easily instituted and can help resolve a variety of problems that continue to plague urban areas, ranging from energy demands and traffic congestion to environmental pollution. Authorities often encourage carpooling, especially during high pollution periods and high fuel prices. The intent here is of making a web based application that will enable to let people know if vehicles are available for carpool in their desired path they can sign in for it. It will show the accurate time required to reach at particular location and would give a better way for pooling a car with a very efficient mapping system embedded into it for optimal routes for the employees. This Web-based application involves real time tracking of cars through GPS and works on logic of efficient and optimal allocation of vehicles to users taking into account the fuel and pollution constraints by allocation vehicles in a optimal fashion. All the cabs involved in this carpooling system are tracked through GPS in head office by the admin cell for safety and security of users, thus promoting safe carpooling culture for women as well.
Furthermore, carpooling has documented social and environmental benefits that include: Reducing traffic congestion as number of vehicles on the road can be reduced significantly, miles of travel of a particular vehicle and emission of gases by the vehicles can also be reduced. Thus it also helps in saving cost of building and maintaining infrastructure. 


## Run

To run the project follow these steps:

1. Create a file called **.env** in the root folder of your project.
2. Import and inject your secret keys in the **.env** file containing your CometChat and Firebase in this manner.

```js

REACT_APP_FIREBASE_API_KEY = AIzaSyAWkiYmoU5rgR_21Uj6l28059I0Txv58eE
REACT_APP_FIREBASE_AUTH_DOMAIN = carpooling-dd480.firebaseapp.com
REACT_APP_FIREBASE_DATABASE_URL = https://carpooling-dd480-default-rtdb.firebaseio.com/
REACT_APP_FIREBASE_STORAGE_BUCKET = carpooling-dd480.firebasestorage.app

REACT_APP_COMETCHAT_APP_ID = 2669669657f8e010
REACT_APP_COMETCHAT_REGION = in
REACT_APP_COMETCHAT_AUTH_KEY = 8e7578140da0481c112f42f7021376fc7f8f2448
REACT_APP_COMETCHAT_API_KEY = d3646e978dc4685ebcf9580d107e20abba69e9fa

REACT_APP_MAP_BOX_API_KEY = pk.eyJ1Ijoic3VubnktZ3VwdGEtbml0aiIsImEiOiJjbTNmZndmN3Ywb2N3MmpyM3Z5N3Nhajk2In0.Tv_uY7iDr-xYlpdQHo8YAg

```
3. Run the following command to install the app.

```sh
    npm install
    npm run start
```
