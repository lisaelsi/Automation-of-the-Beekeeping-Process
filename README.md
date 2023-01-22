As pollinators, bees are important contributors to the global food production and to the preservation of biodiversity. The aim of this project is to create a web application for beekeepers with which they can monitor their beehives. Such an application would reduce the workload of beekeepers and benefit the health of the bee colony. The final application presents data
about the environment in the beehive (including weight, temperature and humidity) as well
as indications of the presence of a queen bee, how many varroa mites are detected and if a
swarm is occurring or is about to occur. The application uses sensors which were assembled
on the beehive prior to the project. The sensors allow for continuous collection of data, which
can be analyzed on a micro computer.

The project mainly focused on the development of three models. The machine learning model, ResNet50, used for mite detection was trained for different numbers of epochs, and its
highest precision was calculated to be approximately 80%. Calculations of the model’s F1-
precision and F1-recall resulted in a maximal F1-value. The queen detection model uses two
k-nearest neighbors models for analysis of sound. The models’ precisions were determined
to be 86,4% and 99,6% on test data, and when the whole program was tested on previously
recorded data from the sensors, as well as in real time, only correct answers were given.
For swarm detection an analytical model was developed based on set conditions for weight,
temperature and weather. The model gave the correct result when tested with previously
collected data from the beehive and with unit tests.

Further tests on real beehives will show how reliable the models are. The project has resulted in a functioning web application, where the models’ classifications give an indication
on the well-being of the beehive. The application can be used as a tool by beekeepers, and
the aim of the project is therefore considered to be reached.
