# RustyBargain, Métodos numéricos

📖 Resúmen:  
  Crear y entrenar modelo de predicción para la empresa Rusty Bargain que quiere desarrollar una aplicación que te arroje el valor de tu auto seminuevo para atraer nuevos clientes.
.  
.  
.  
🎯 Objetivo:  
  Encontrar el mejor modelo predictivo con los mejores hiperparámetros para elegir el valor más aproximado posible.

❌ Problema:  
  Datos sucios e incompletos, algunos clientes no llenaban todos los campos de información de su vehículo o lo hacían  con información incoherente.

✅ Solución:  
  Tratamiento de valores ausentes e incongruentes con reemplazos, eliminación e imputación.

🔢 Metodologia:  
  1. Análisis y limpieza de datos.
  2. Tratamiento de valores ausentes e incongruentes.
  3. Creación de 5 modelos diferentes (LightGBM, Catboost, XGBoost, Bosque aleatorio, árbol de decisión y regresión lineal):  
     2.1. Prueba de dos hiperparámetros distintos,  
     2.2. Elección de hiperparámetros con mejores métricas.   
  4. Elección final y conclusión.

📊 Conclusiones:  
  Se creó modelo predictivo que cumple con los requerimientos (calidad de predicción, tiempo bajo de entrenamiento y velocidad de predicción), los modelos con potenciación de gradiente fueron superiores al resto y de esos el mejor resulto ser LightGBM.
