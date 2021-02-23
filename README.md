# Examen
Primero lo que tuve que hacer es importar los reporsitorios

import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
import numpy as np
import numpy as np 
import seaborn as sns 
from matplotlib import pyplot as plt 
%matplotlib inline

Luego lo que haremos es definir nuestras variables,para abrir nuestro archivo directamente en un DataFrame utlizaremos el comando pd.read_csv, junto unos parentecis que llevara unas comillas dobles que donde sera para indicar nuestra ruta del archivo finalemeto con la extencion .csv

bd = pd.read_csv("data.csv")


Depues ingrese la parte de los 10 primeros artistas. ingresando los comandos 

df = df.head(10).sort_values(by='artists', ascending=True)

df['artists']

Ahora describi los posibles datos que se relaciones ingresando el comando 

df---------- para que muestre la tabla

Luego
relacion = df[['artists','danceability','duration_ms','energy']] donde se tomaran las relaciones

y aqui el comando -----relacion.head(10) mostrara 10 datos de cada columna donde veremos las relaciones.

Conforme con las variables lo que haremos es sacar la Media, Promedio, valor máximo, valor mínimo
para eso ingresamos el comando

*relacion.describe()
y luego el comando 
*relacion.describe()

luego procemos con la varianza para eso ingresamos el comando 
var = df.var()
print(var) Que imprimira los resultados


por ultimo veremos Cuáles valores pueden tener una relación lineal positiva 
para esto lo que haremos es ingresar el comando
*sns.pairplot(relacion, kind ='reg') y nos mostrara unas graficas

ahora cuales fueron esas relaciones?Se tiene relacion con la bailabilidad,diration y energy, pieso que es posible ya que se mueven por una misma direccion,teniendo como relacion la dependecia de una de otra y investigue  que la relacion literal positiva es la que va de aumento o disminuye simultaneamente a un ritmo constante.
