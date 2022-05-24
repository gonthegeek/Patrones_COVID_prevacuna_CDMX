# Patrones_COVID_prevacuna_CDMX

Se realizó un análisis del set de datos de actas de defunciones de México, específicamente de la Ciudad de México entre el inicio de la pandemia por COVID-19 en territorio nacional y el inicio del esquema de vacunación en la ciudad. Se usaron herramientas de ciencia de datos en Python, tales como pandas y scikit learn para ello. Este análisis conllevó una manipulación y visualización de datos así como el diseño de un modelo de Machine Learning no supervisado, con el cual no logramos llegar a una conclusión precisa sobre nuestra pregunta de investigación. Gracias a la visualización de datos logramos darnos cuenta que los grupos más vulnerables son los hombres con una edad avanzada, más precisamente aquellos que tienen una edad entre los 60 y 80 años de las alcaldías de Venustiano Carranza, Iztacalco y Azcapotzalco. 

## Requiere
 - Python 3.7.13
 - Pandas 1.3.5
 - Numpy 1.21.6
 - Plotnine 0.6.0
 - Scikit learn 1.0.2
 - Matplotlib 3.2.2

## Datos
  https://datos.cdmx.gob.mx/dataset/19e094a0-f1c0-4544-bac6-dd1d5cb8a4de/resource/d683ec6e-171a-4825-a523-2cdbf30f9894/download/defunciones_corte_110322.csv
  
## Esquema de datos
1. Edad - float64 - Edad de la persona fallecida.
2. Sexo - String -	Sexo de la persona fallecida.
3. Fecha Defunción - String - Fecha en la que falleció en formato YYYY-MM-DD
4. Estado - String - Estado en el cual falleció la persona.
5. Causa - String - Determinación de si falleció por COVID-19 o por otras causas.
6. Causa Registro - String - Causas de muerte en formato separado por comas.
7. Alcaldía - String - Alcaldía en la cual falleció. En caso de estar fuera de la CDMX está en NaN.
8. Lugar Muerte - String - Determinación de si murió en casa o en el hospital.
9. Número Consecutivo - int64 - Número consecutivo de fallecimiento.
