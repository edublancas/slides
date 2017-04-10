
# Configuración de ambiente en Python 3

---

# Paquetes

Para mostrar algunos ejemplos de ML usaremos las siguientes librerías de Python:

* scikit-learn: contiene una gran cantidad de implementación de algoritmos de ML (supervisado y no supervisado)
* sklearn-evaluation: paquete para evaluar modelos con gráficas

---

# Miniconda

La forma más sencilla de instalar estos paquetes es a través de miniconda, para instrucciones de instalación ver:

https://conda.io/docs/install/quick.html

---

# Instalando paquetes

Una vez que instalamos conda creamos  y activamos un nuevo ambiente de Python 3:

```
conda create python=3 --name ml && source activate ml
```

Instalamos scikit-learn:

```
conda install scikit-learn
```

Instalamos matplotlib (dependencia de sklearn-evaluation):

```
conda install matplotlib
```

Instalamos sklearn-evaluation:

```
pip install sklearn-evaluation
```

---

# Instalando Jupyter

Jupyter es un paquete que nos permite escribir Python desde un ambiente interactivo por medio de una aplicación web

```
pip install jupyter
```

---

# Instalando pandas

Pandas es una librería para manipulación de datos, no es estrictamente necesaria para usar scikit-learn pero facilita el manejo de los datos

```
pip install pandas
```

---

# Verificando instalación

Para verificar que todo se instaló de manera correcta, corremos lo siguiente en una sesión de Python:


```
import sklearn
import matplotlib
import pandas
```

---

# Iniciando Jupyter

Para iniciar una sesión de Jupyter ejecutamos lo siguiente:

```
jupyter notebook
```