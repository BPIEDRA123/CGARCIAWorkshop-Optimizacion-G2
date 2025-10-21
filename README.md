#  Sistema de apoyo al diagnóstico basado en inteligencia artificial para la detección temprana de cáncer de tiroides mediante ecografía  

###  Proyecto Integrador — Universidad de Especialidades Espíritu Santo (UEES)

---

##  Descripción general  
Este proyecto presenta el desarrollo de un sistema de **inteligencia artificial aplicado al diagnóstico médico**, orientado a la **detección temprana del cáncer de tiroides** mediante imágenes ecográficas.  
El modelo utiliza técnicas de **Machine Learning** y **análisis estadístico avanzado** para mejorar la precisión diagnóstica, reducir el sesgo y proporcionar soporte clínico automatizado al especialista.

---

##  Metodología  
El sistema fue entrenado con **637 imágenes ecográficas** (377 malignas y 260 benignas), evidenciando un **desbalance moderado (1.45:1)**.  
Se implementó un modelo **Random Forest** optimizado mediante **RandomizedSearchCV**, explorando combinaciones de hiperparámetros con validación cruzada.  
El análisis de significancia estadística (*p-valores*) permitió identificar las variables más relevantes y su contribución al diagnóstico predictivo.  

---

##  Resultados principales  
-  **Score de validación optimizado:** 0.6148  
-  **Mejora relativa:** +1.6 % frente al modelo base (~0.6051)  
-  **Variables más relevantes:** contraste, intensidad promedio y densidad de bordes  
-  **Estrategia más equilibrada:** *Class Weights* (mejor relación entre rendimiento y equidad)  
-  **Tiempo total de optimización:** 0.97 minutos  

---

##  Conclusiones  
El modelo logró un **rendimiento estable y clínicamente prometedor**, confirmando la utilidad de las variables morfológicas en la clasificación de lesiones tiroideas.  
Los resultados demuestran la **viabilidad técnica y científica** del enfoque, estableciendo una base sólida para futuras fases de validación médica.  
Se recomienda continuar con:  
1. La **ampliación del dataset** para mejorar la generalización del modelo.  
2. La implementación de **redes neuronales convolucionales (CNN)** y *transfer learning*.  
3. La **validación clínica y regulatoria**, garantizando seguridad y confiabilidad en su aplicación práctica.  

---

##  Responsables del proyecto  

| Nombre | Rol | 
|:--------|:------|
| **Christian García** | Desarrollador | 
| **Byron Piedra** | Product Owner | 


