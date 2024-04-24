# <h1 style="font-family:verdana; text-align: center;"> AI or Real? Image Classification Challenge </h1>

![robot.png](https://img.freepik.com/premium-photo/arafed-robot-painting-canvas-messy-room-with-window-generative-ai_927978-24454.jpg?w=1060)

## <h2>  <center> Where is the data coming from?</center> </h2>

<div class="alert alert-block alert-info" style="font-size:14px; font-family:verdana; line-height: 1.7em;">
    📌 &nbsp;In response to the rise of AI-generated images, our challenge is to develop a Convolutional Neural Network (CNN) model that distinguishes between authentic and AI-generated images, ensuring reliability in digital content.
</div>

<div style="color:white;
           display:fill;
           border-radius:5px;
           background-color:#5642C5;
           font-size:110%;
           font-family:Verdana;
           letter-spacing:0.5px">

<p style="padding: 10px;
              color:white;">
    <br>
📍Information about the data
    
Original data can be found at the following link. It contains more than 15,000 artwork images with each and every label verified:
https://www.kaggle.com/datasets/kausthubkannan/ai-and-human-art-classification/data    
</p>
</div>

## Data Visualization

<div class="alert alert-block alert-info" style="font-size:14px; font-family:verdana; line-height: 1.7em; background-color: #add8e6; color: #000000;">
    &nbsp; The two categories of the data are:<br>
    🔴AI_GENERATED<br>
    🔴NON_AI_GENERATED<br>
</div>
    <br>

![descarga](https://github.com/AndresMembrillo/AI_image_recognition/assets/145653361/d22477ee-9cfe-4c46-9786-1bc73e068d96)



## Model

Project based on the implementation of Deep Learning models (Tensorflow and Keras) in images.

- Convolutional part: Pre-trained model: "vgg16"

- Simple neural network part

![kmeans](https://github.com/AndresMembrillo/proyecto-usisa/assets/145653361/39023b00-5e1a-4691-af45-62390ea09e00)

Se agrupan los clientes por sus respectivos clusters y se obtiene el centro de cada cluster usando la media para ver las características que mejor explican cada grupo. El clúster 0  lo etiquetamos como clientes fieles.

- `Clúster 0`: su última compra fue hace mucho, promedian tan solo un pedido y es el grupo que menos dinero gasta. Corresponde al 54% de los clientes. El clúster 0  lo etiquetamos como clientes perdidos.

- `Clúster 1`: se observa que la última compra de este grupo ha sido muy reciente, promedian tan solo un pedido y gasta moderadamente. Comprende el 22% aproximadamente del total de clientes. El clúster 1  lo etiquetamos como clientes nuevos.

- `Clúster 2`: su última compra ha sido hace relativamente poco, es el grupo que más pedidos promedia y que más gasta prácticamente cuadruplicando los demás. Se trata del 24% de los clientes. El clúster 2 lo etiquetamos como clientes fieles.

También graficamos un mapa de España por cada cluster, con la geolocalización donde se aprecian dónde están los mayores volúmenes de pedidos de cada cluster según su código postal. 

A continuación se visualiza el mapa del cluster 0, etiquetado como el grupo de los clientes perdidos.
![00mapas](https://github.com/AndresMembrillo/proyecto-usisa/assets/145653361/fd60302d-47bb-436e-a1e3-b071b233d565)

Mapa del cluster 1, etiquetado como el grupo de los clientes nuevos:
![01mapas](https://github.com/AndresMembrillo/proyecto-usisa/assets/145653361/9894d5c4-40f7-4ead-ae93-c417bfe48310)

Mapa del cluster 2, etiquetado como el grupo de los clientes fieles:
![02mapas](https://github.com/AndresMembrillo/proyecto-usisa/assets/145653361/13faae0a-e58b-4482-bba6-f43718d8e7e2)

  nota: los mapas son gráficos de la libreria folium, son dinámicos y no se pueden visualizar en GitHub.

## Conclusión
Hemos segmentado los clientes y sabemos donde se localiza cada grupo, esta información junto a los datos del cliente (correo electrónico) es de gran valor para una campaña de marketing.
