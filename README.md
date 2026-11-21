# SISTEMAS DE APOYO A LA DECISIÓN CLÍNICA
Práctica 3 Sistemas Inteligentes


## 1. Descripción del proyecto

Esta práctica consiste en la implementación de dos sistemas de apoyo a la decisión clínica:

- CDS basado en reglas: el programador decide y define las reglas, puntuaciones, umbrales y codificaciones.
- CDS basado en aprendizaje automático: el modelo aprende las realciones entre las variables a partir de ejemplos.

Se nos proporciona un dataset especifico (grupo 05) y a partir de esos datos llevamos a cabo la separación de los conjuntos (entrenamiento, validación y prueba) y la implementación de los modelos.

## 2. Versión de Python 

Este proyecto se ha realizado en la versión de Python 3.12.4 

## 3. Instalación del proyecto y las dependencias

Para instalar el proyecto hay que clonar el repositorio desde GitHub de la siguiente manera:

```bash
git clone <url-del-repositorio>
cd <SIST-APOYO-DECISION-CLINICA>
```

También hay que crear un entorno virtual:
```bash
python -m venv .envCDS
.envCDS\Scripts\activate    
```

Las dependencias del proyecto se encuentran en el archivo requirements.txt, que se instala mediante el siguiente comando: 
```bash
pip install -r requirements.txt 
```

## 4. Ejecución del cuaderno de resultados
El cuaderno de resultados se encuentra en `notebooks/Practica3-Resultados.ipynb`, se debe seleccionar el entorno `.envCDS`como kernel y ejecutar las celdas secuencialmente, mediante la opción de Run All o utilizando Ctrl + Enter para ejecutarlas individualmente.

Los datos se leen de la carpeta `datos/`.


## 5. Estructura del repositorio

La organización del proyecto en archivos y carpetas/directorios sigue la siguiente estrutura:

``` text
SIST-APOYO-DECISION-CLINICA/
|
├── datos/       
|       ├──grupo_05_config.json
|       ├──grupo_05_datos.csv     
|
├──docs/
|     └── uso_ia.md   
│       
├── notebooks/
|      └── Practica3-Resultados.ipynb 
│     
├── .gitignore                  
├── README.md                  
└── requirements.txt            
```

