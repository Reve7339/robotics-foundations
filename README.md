# Fundamentos de Robótica (Robotics Foundations I - Robot Modelling) 🤖⚙️

¡Bienvenido! Este repositorio contiene una serie de **Jupyter Notebooks interactivos** creados para estudiar, comprender y simular visualmente los conceptos clave de la ingeniería robótica (cinemática, dinámica, control y modelado).

Los notebooks están fuertemente inspirados en el curso *Robotics Foundations I - Robot Modelling* y adaptan literatura estándar de la industria (como Siciliano y Craig) usando **Python**, **SciPy** y **Plotly** para visualizaciones en 3D interactivas.

## 📚 Índice de Contenidos

Este repositorio está en construcción. Actualmente contiene los siguientes módulos:

1. [**Representation of Orientation**](Representation_of_Orientation.ipynb)
   * Espacio Articular vs. Espacio Cartesiano.
   * Matrices de Rotación `SO(3)`.
   * Ángulos de Euler y el problema de *Gimbal Lock*.
   * Representación de Eje-Ángulo (Teorema de Euler).
   * Cuaterniones Unitarios y su uso industrial.
   * Casos Prácticos Reales: Modelado de cámaras en el robot (Eye-in-Hand), navegación de VANTs y animaciones de soldadura suaves con SLERP.

2. [**Direct Kinematics**](Direct_Kinematics.ipynb)
   * Transformaciones Homogéneas ($4\\times4$).
   * Convención de Denavit-Hartenberg (DH).
   * Ecuación de Cinemática Directa para cadenas abiertas.
   * Modelado completo de Robots Reales: Antropomórfico (RRR), Esférico (RRP), Cilíndrico (RPP) y SCARA (RRPR).

*(Próximamente más notebooks sobre cinemática inversa, jacobianos, dinámica y control...)*

## 🚀 Cómo ejecutar los Notebooks

### 1. En la nube (Recomendado)
No necesitas instalar nada. Solo da clic en el botón de **Open in Colab** que encontrarás en la parte superior de cada notebook para correrlo directamente en Google Colab con todos los recursos preinstalados.

### 2. De forma local (En tu computadora)
Si prefieres clonar este repositorio y correrlo localmente, asegúrate de tener instalado Python y Jupyter Lab/Notebook. Luego instala los requerimientos básicos corriendo:

```bash
pip install numpy scipy plotly
```

¡Abre tu editor favorito (Jupyter, VS Code) y explora el código interactivo!
