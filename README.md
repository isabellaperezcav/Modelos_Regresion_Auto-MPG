# Implementación de Regresión Lineal

Este proyecto contiene una implementación completa de **regresión lineal** utilizando distintas técnicas de ajuste:

* **Ecuación normal**
* **Scikit-learn**
* **Gradiente descendente**

Además, se incluye un **análisis exploratorio de datos (EDA)** para la selección de *features*, comparación de modelos con métricas y estudio de problemas comunes como **overfitting**, **outliers** y **normalización**.

---

## Dataset

Los datos corresponden al consumo de combustible en ciclo urbano (**millas por galón**, *mpg*), que se predice en función de **3 atributos discretos multivaluados** y **5 atributos continuos**.

Fuente: *Quinlan, 1993*

### Atributos del dataset

1. **mpg** → continuo
2. **cilindros** → discreto multivalorado
3. **cilindrada (displacement)** → continuo
4. **potencia (horsepower)** → continuo
5. **peso (weight)** → continuo
6. **aceleración** → continuo
7. **año del modelo** → discreto multivalorado
8. **origen** → discreto multivalorado  (USA=1/Europe=2/Japan=3)
9. **nombre del coche** → cadena (*única por instancia*)

### Valores faltantes

* La variable **potencia (horsepower)** contiene **6 valores faltantes**.
