# Road-Accident-UK
En este proyecto se desarrollará un modelo de predicción de la severidad de los accidentes de tránsito.

## Integrantes

Jean Carlos Julio Rodriguez C.C: 1.045.750.641 Ingeniería Eléctrica 

Anamaria Romero Carvajal C.C 1.061.823.688 Ingeniería Eléctrica

## Datos

Los datos a utilizar provienen del siguiente dataset: [Road Accident (United Kingdom (UK)) Dataset](https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk-dataset), y se hacen disponibles ejecutando desde cualquier notebook en Colab lo siguiente:

### 1. Instalar y configurar Kaggle

Inicialmente se debe instalar kaggle con el siguiente comando:

    pip install kaggle

Seguidamente se genera un token, el cual se encuentra en la configuración de la cuenta Kaggle, se descarga el archivo "kaggle.json" y se mueve a la carpeta ".kaggle", esto realiza ejecutando los siguientes comandos:

    mkdir ~/.kaggle
    mv ~/Descargas/kaggle.json ~/.kaggle/
    
### 2. Descargar el Dataset
El Dataset se puede obtener mediante la ejecucion del siguiente comando:

    kaggle datasets download -d devansodariya/road-accident-united-kingdom-uk-dataset
    
Se descargará un archivo comprimido en formato zip que contiene el archivo ".csv", el cual se descomprime posteriormente.
    
    unzip road-accident-united-kingdom-uk-dataset.zip 
### 3. Video presentacion
[Entrega 2](https://youtu.be/_azjuCuH0oI)
