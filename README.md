# Challenge_Telecom_1
Se ha tomado la informacion de la evasion en la compañia telefonica TelecomX disponible en archivo json desde la api suministrada, 
archivo que exigio ser normalizado ya que contaba con estructuras de datos anidados. posteriormente se realiza la limpieza y tratamiento de datos 
y analisi exploratorio generando algunas conclusiones y recomendaciones.

## Requerimiento de instalacion y ejecucion
* Python
* import pandas as pd
* import matplotlib.pyplot as plt
* import seaborn as sns

## Analisis 
vemos el estado de la evasion y retencion de la compañia telefonica

<img width="549" height="393" alt="Sin título" src="https://github.com/user-attachments/assets/832479ba-adc2-4ed1-b3dc-3a7221f535df" />

Anlizajmos la relacion de las variables categoricas con nuestra columna objetivo Churn
<img width="1789" height="590" alt="Sin título" src="https://github.com/user-attachments/assets/da9b3217-7f7d-440d-b8e5-a820f681db51" />

Analizamos tambien la relacion de las variables numericas con la evasion 
<img width="1590" height="590" alt="Sin título" src="https://github.com/user-attachments/assets/2c37a537-7bbd-4053-826a-83795cd512b2" />


## Conclusiones
* Se identifica que se tiene una fidelidad del 75% de los clientes y un 25% porciento de evasion.

* La variable genero no tiene ninguna relacion con la evasion que presenta, pero si el estado civil o de pareja, las personas solteras tienden a terminar el contrato con mas facilidad.

* Uno de las puntos mas visibles en la evasion es que los contratos mes a mes tienen el mayor porcentaje de evasion en cuanto a tipo de contrato y en cuanto a los servicios de internet la mayor evasion se da en el servicio de fibra optica
