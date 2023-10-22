# Ataque de Tiburones

![Alt text](img/Tibu_ballena.jpg)

For this project, I will start with this messy data set Shark Attack. I will need to download it, import it, use my data wrangling skills to clean it up, prepare it to be analyzed, and then export it as a clean CSV data file. Add graphs to better understand the data!!

En este proyecto voy a limpiar y analizar los datos sobre ataques de tiburones a personas

##TO DO's

1. Explore the data and write down what you have found

    - you can use: df.describe(), df["column"], etc.

#####Realizar limpieza, carga de datos -> ver por encima, describe, quitar nulos, poner unidades, establecer criterio ordenado en las columnas...

** especie de tiburones

2. Use at least 5 data cleaning techniques inside a file named clean.ipynb
    
    - null values, columns drop, duplicated data, string manipulation, apply fn, categorize, regex, etc.

3. Show data that validates the conclusions based on your hypoteses in a file named analysis.ipynb

#####EL PROYECTO ES INFINITO!!! NO VA A ACABAR, PENSAR EN CADA PASO, SIGUIENTE CURVA..

#####resetear el nombre de todas las columnas para que no tengan falta de ortografia espacios...

##Suggested Ways to Get Started

- Examine the data and try to understand what the fields mean before diving into data cleaning and manipulation methods.

- Break the project down into different steps - use the topics covered in the lessons to form a check list, add anything else you can think of that may be wrong with your data set, and then work through the check list.

- Use the tools in your tool kit - your knowledge of Python, data structures, Pandas, and data wrangling. Work through the lessons in class & ask questions when you need to! Think about adding relevant code to your project each night, instead of, you know... procrastinating.

- Commit early, commit often, don’t be afraid of doing something incorrectly because you can always roll back to a previous version.

- Consult documentation and resources provided to better understand the tools you are using and how to accomplish what you want.

##How to deliver the project

1. Create a new repo with the name data-cleaning-pandas on your github account.

    - Create a README.md file on repo root with project documentation. Make sure to include as much useful information as possible. Someone that finds the README.md should be able to fully get a gist of the project without browsing your files.

    - Include a .gitignore

    - At least 1 jupyter notebook is required

    - Including your functions in a src.py is very, very highly reccommended (maybe even mandatory, check with your instructors)

2. Open an Issue on this repo and paste your own repo's link.

##Obligations & Restrictions

- OBLIGACIÓN MIN:
df.shape == (2500,23) ESTO ES LO MINIMO 

- RESTRICCIONES:
    1.  NO SE BORRAN COLUMNAS (hay una columna con nan todo...) si se pueden añadir columnas
    2. AL MENOS 2500 FILAS 
    3. Deadline: MARTES

- BONUS: PONER OBJETIVO Y HACER PEQUEÑO ANÁLISIS (ej: hay sesgo x genero, especie de tiburion, etc)

##Links & Resources:

https://www.kaggle.com/teajay/global-shark-attacks
https://numpy.org/doc/1.18/
https://pandas.pydata.org/
https://docs.python.org/3/library/functions.html
https://plotly.com/python/
https://matplotlib.org/
https://seaborn.pydata.org/
https://pandas.pydata.org/docs/
https://towardsdatascience.com/beware-of-storytelling-with-data-1710fea554b0?gi=537e0c10d89e