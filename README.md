# ¿El juego tiene exito o no?

## Descripción del proyecto

Trabajas para la tienda online Ice que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. Tienes que identificar patrones que determinen si un juego tiene éxito o no. Esto te permitirá detectar proyectos prometedores y planificar campañas publicitarias.

Delante de ti hay datos que se remontan a 2016. Imaginemos que es diciembre de 2016 y estás planeando una campaña para 2017.
Lo importante es adquirir experiencia de trabajo con datos. Realmente no importa si estás pronosticando las ventas de 2017 en función de los datos de 2016 o las ventas de 2027 en función de los datos de 2026.

El dataset contiene una columna "rating" que almacena la clasificación ESRB de cada juego. El Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.

## Diccionario de datos

Dataset: `./games.csv`

- Name: Nombre
- Platform: Plataforma.
- Year_of_Release: Año de lanzamiento.
- Genre: Género.
- NA_sales: ventas en Norteamérica en millones de dólares estadounidenses. 
- EU_sales: ventas en Europa en millones de dólares estadounidenses.
- JP_sales: ventas en Japón en millones de dólares estadounidenses.
- Other_sales: ventas en otros países en millones de dólares estadounidenses.
- Critic_Score: calificación de crítica (máximo de 100). 
- User_Score: calificación de usuario (máximo de 10).
- Clasificación: clasificación del software de entretenimiento ESRB.  
Nota: Es posible que los datos de 2016 estén incompletos.

## Creación de un perfil para cada región
Para cada región (NA, UE, JP) se determina:
- Las cinco plataformas principales. Describe las variaciones en sus cuotas de mercado de una región a otra.
- Los cinco géneros principales. Explica la diferencia.
- Si las clasificaciones de ESRB afectan a las ventas en regiones individuales.

## Pruebas de hipótesis

— Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
— Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.