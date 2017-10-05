# Le jardin Connecté

## Prérequis

## Ajoutez les bibliothèques suivantes dans l'IDE d'arduino
- Ajoutez les bibliothèques
	- I2CSoilMoistureSensor https://github.com/julienrat/jardin_connect-/raw/master/Biblioth%C3%A8ques/I2CSoilMoistureSensor-master.zip
	- MOD 1023 https://github.com/julienrat/jardin_connect-/raw/master/Biblioth%C3%A8ques/MOD-1023-master.zip
	- ADAFRUIT SI 1145 https://github.com/julienrat/jardin_connect-/raw/master/Biblioth%C3%A8ques/Adafruit_SI1145_Library-master.zip
	- BME280 https://github.com/julienrat/jardin_connect-/raw/master/Biblioth%C3%A8ques/BlueDot_BME280-master.zip
	- ADAFRUIT Unified Sensor https://github.com/julienrat/jardin_connect-/raw/master/Biblioth%C3%A8ques/Adafruit_Unified_Sensor.zip

## Configurer les sondes SOIL moisture
Il est necessaire d'effectuer l'adressage des sondes une à une, pour ceci munissez vous d'étiquettes autocollantes pour repérer vos sondes.

- Connecter la première sonde au Wemos comme suit
- Chargez le programme " ChangeSensorI2Cadress" et changez les adresses de vos sondes à la ligne 19

