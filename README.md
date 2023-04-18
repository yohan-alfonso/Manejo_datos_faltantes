# Manejo_datos_faltantes

Repositorio de Tecnica de maenjo de datos faltantes

Para este fin usaré en dataset '[clean_df.csv](https://github.com/yohan-alfonso/Data_Cleansing_with_Python/blob/main/clean_df.csv "clean_df.csv")' que se limpio en el repositorio https://github.com/yohan-alfonso/Data_Cleansing_with_Python.

La idea es identificar  la naturaleza de la perdidad de los datos entre los cuales pueden estar:

1 - MCAR : Missing completely at random (no hay un patron de perdida de datos dependiente de una variable)

2 - MNAR: Missing not at random (la perdida de datos puede ser sistematica reconoce un patron o depende de una variable)

3- MAR: Missing at random (es un punto intermedio entre los dos anteriores, la perdida de datos puede depender de las variables)

Las tecnicas a usar pueden ser:

a) El descarte (eliminación de datos)

b) La imputación (estimar el dato faltante usando los datos vecinos o variables del dataset)

Las dos tecnicas anteriores son aplicable a MCAR o MAR (Perdidad de datos aleatorios no sistematicos)

Para el dataset que vamos a usar la eliminación de lista no es una opción por que los datos faltantes estan al rededor del 80% pero si contamos con varianbles que nos pueden ayudar a reconocer los datos aleatorios faltantes.
