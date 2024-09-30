# temperatura

## actividad

- ## 1 Crear un arreglo llamado dias, que contenga los días de la semana (lunes, martes, etc)
- ## 2 Crear un arreglo llamado temperatura con los siguientes valores 22, 21, 23, 24, 20, 19, 25
- ## 3 Graficar con matplotlib
![Figure_1](https://github.com/user-attachments/assets/c8e85c3b-763c-447a-8a7f-6fa52a5d95b5)

import matplotlib.pyplot as plt

~~~
# 1. Crear un arreglo llamado dias
dias = ["lunes", "martes", "miércoles", "jueves", "viernes", "sábado", "domingo"]

# 2. Crear un arreglo llamado temperatura
temperatura = [22, 21, 23, 24, 20, 19, 25]

# 3. Graficar con matplotlib
plt.figure(figsize=(10, 5))
plt.plot(dias, temperatura, marker='o')
plt.title('Temperaturas de la Semana')
plt.xlabel('Días de la Semana')
plt.ylabel('Temperatura (°C)')
plt.grid()
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
~~~
