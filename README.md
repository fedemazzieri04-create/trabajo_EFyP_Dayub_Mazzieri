# Calibración de Magnetómetros: MLE Batch vs EKF

**Trabajo Final de Estimación, Filtrado y Predicción**  
*Facultad de Ingeniería y Ciencias Hídricas (FICH) - Universidad Nacional del Litoral (UNL)*

**Autores:** Dayub Mateo Jose y Mazzieri Federico Nicolás

---

## Descripción del Proyecto

Este repositorio contiene el código fuente en Python utilizado para la estimación de parámetros y calibración de magnetómetros frente a perturbaciones magnéticas locales (**Hard-Iron** y **Soft-Iron**). 

Bibliografía:
1. **MLE Batch Iterativo (Mínimos Cuadrados):** Basado en el método propuesto por E. Dorveaux et al. (2009).
2. **Filtro de Kalman Extendido (EKF):** Basado en el algoritmo recursivo y secuencial propuesto por J. L. Crassidis et al. (2005).

Sensores:
* XSens MTi 630
* Phidgets Spatial Precision 3/3/3
* STMicroelectronics LSM9DS1

## Dependencias y Requisitos

Para ejecutar los scripts de este repositorio, se requiere Python 3.x y las siguientes librerías:
```bash
pip install numpy pandas matplotlib bagpy

## Clonar el repositorio:

1. git clone [https://github.com/fedemazzieri04-create/trabajo_EFyP_Dayub_Mazzieri.git](https://github.com/fedemazzieri04-create/trabajo_EFyP_Dayub_Mazzieri.git)

2. Asegurarse de tener los archivos .csv o el .bag de los datos reales en el directorio raíz.
