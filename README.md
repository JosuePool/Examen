# Examen
Primero lo que tuve que hacer es importar el panda

*Impor pandas as pd

Luego lo que haremos es definir nuestras variables,para abrir nuestro archivo directamente en un DataFrame utlizaremos el comando pd.read_csv, junto unos parentecis que llevara unas comillas dobles que donde sera para indicar nuestra ruta del archivo finalemeto con la extencion .csv

*df=pd.read_csv("Music/data_by_artist.csv')

Luego lo que hice fue ver la informacion que se tiene para eso ingrese el comando

*df.info

Depues ingrese la parte de los 10 primeros artistas. ingresando el comando 

*df.head()

Ahora describi los datos usando el comando 

*df.describe()
df.artist.count()

ahora para poder identificar la media primero ingresamos el nombre de la variable.  y junto el comando

*Media = df["duration_ms"].mean




