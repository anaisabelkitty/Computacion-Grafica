# 🎨 Computación Gráfica e Interacción Humano Computadora

Repositorio de prácticas de la materia **Computación Gráfica e Interacción Humano Computadora** de Ingeniería en Computación, UNAM. Este repositorio está organizado por ramas para facilitar la navegación y revisión de cada ejercicio de forma independiente.

## 📋 Descripción

Este repositorio contiene 11 prácticas (0-10) desarrolladas a lo largo del curso, donde se exploran conceptos fundamentales de gráficos por computadora, desde la configuración del entorno hasta técnicas avanzadas de animación. Cada práctica se encuentra en su propia rama para mantener el código organizado y permitir una revisión individual de cada tema.

## 🌿 Estructura del Repositorio

El repositorio está organizado en **ramas**, donde cada una representa una práctica específica:

| Rama | Descripción | Enlace |
|------|-------------|--------|
| `master` | Práctica 0: Configuración del Entorno de Desarrollo | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/master) |
| `practica1_Introduccion_a_OpenGL-_(actualizada)` | Práctica 1: Introducción a OpenGL | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica1_Introduccion_a_OpenGL-_(actualizada)) |
| `practica2_Proyecciones_y_Puertos_de_vista_Transformaciones_Geometricas_(actualizada)` | Práctica 2: Proyecciones y Transformaciones Geométricas | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica2_Proyecciones_y_Puertos_de_vista_Transformaciones_Geometricas_(actualizada)) |
| `practica3_Modelado_Geometrico` | Práctica 3: Modelado Geométrico 3D | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica3_Modelado_Geometrico) |
| `practica4_Modelado_Jerarquico` | Práctica 4: Jerarquías de Objetos - Brazo Robótico | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica4_Modelado_Jerarquico) |
| `practica5_Carga_de_modelos_y_Camara_Sintetica` | Práctica 5: Carga de Modelos 3D y Cámara Sintética | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica5_Carga_de_modelos_y_Camara_Sintetica) |
| `practica6_Texturizado` | Práctica 6: Texturizado en OpenGL | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica6_Texturizado) |
| `practica7_Iluminación_1` | Práctica 7: Iluminación - Modelo Phong | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica7_Iluminaci%C3%B3n_1) |
| `practica8_Iluminacion_2` | Práctica 8: Técnicas Avanzadas de Iluminación | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica8_Iluminacion_2) |
| `practica9_Animacion_Basica` | Práctica 9: Animación 3D en Tiempo Real | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica9_Animacion_Basica) |
| `practica10_Animacion_por_Keyframes` | Práctica 10: Sistema de Animación por Keyframes | [Ver rama](https://github.com/anaisabelkitty/Computacion-Grafica/tree/practica10_Animacion_por_Keyframes) |

## 🚀 Cómo navegar el repositorio

### Opción 1: Desde GitHub (Recomendado)
1. Ve a la [página principal del repositorio](https://github.com/anaisabelkitty/Computacion-Grafica)
2. Haz clic en el selector de ramas (donde dice `master`)
3. Selecciona la práctica que deseas revisar:
   - `master` → Práctica 0
   - `practica1_Introduccion_a_OpenGL-_(actualizada)` → Práctica 1
   - `practica2_Proyecciones_y_Puertos_de_vista_Transformaciones_Geometricas_(actualizada)` → Práctica 2
   - Y así sucesivamente...
4. Explora los archivos de esa práctica específica

### Opción 2: Clonando el repositorio
```bash
# Clonar el repositorio completo
git clone https://github.com/anaisabelkitty/Computacion-Grafica.git
cd Computacion-Grafica

# Ver todas las ramas disponibles
git branch -a

# Ver la Práctica 0 (ya estás en master por defecto)

# Para ver la Práctica 1:
git checkout practica1_Introduccion_a_OpenGL-_\(actualizada\)

# Para ver la Práctica 2:
git checkout practica2_Proyecciones_y_Puertos_de_vista_Transformaciones_Geometricas_\(actualizada\)

# Para ver la Práctica 3:
git checkout practica3_Modelado_Geometrico

# Y así sucesivamente...
```

### Opción 3: Clonar una práctica específica
```bash
# Para clonar solo la Práctica 0:
git clone https://github.com/anaisabelkitty/Computacion-Grafica.git

# Para clonar solo la Práctica 1:
git clone -b practica1_Introduccion_a_OpenGL-_\(actualizada\) --single-branch https://github.com/anaisabelkitty/Computacion-Grafica.git practica1

# Para clonar solo la Práctica 2:
git clone -b practica2_Proyecciones_y_Puertos_de_vista_Transformaciones_Geometricas_\(actualizada\) --single-branch https://github.com/anaisabelkitty/Computacion-Grafica.git practica2

# Para clonar la Práctica 3:
git clone -b practica3_Modelado_Geometrico --single-branch https://github.com/anaisabelkitty/Computacion-Grafica.git practica3

# Y así sucesivamente...
```

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** C++
- **IDE:** Visual Studio Community 2022
- **API Gráfica:** OpenGL 4.x
- **Librerías:**
  - **GLFW** - Gestión de ventanas e interacción con usuario
  - **GLEW** - Extensiones de OpenGL
  - **GLM** - Matemáticas para gráficos (vectores y matrices)
  - **Assimp** - Carga de modelos 3D
  - **stb_image** - Carga de texturas
- **Lenguaje de Shaders:** GLSL (OpenGL Shading Language)
- **Control de versiones:** Git & GitHub

## 📚 Contenido de las prácticas

> **Nota:** Para ver el contenido detallado de cada práctica, navega a su rama correspondiente.

### Práctica 0: Configuración del Entorno de Desarrollo
📍 **Rama:** `master`

**Objetivo:** Configurar el entorno de trabajo en Visual Studio Community 2022 e integrar las librerías necesarias de OpenGL.

**Contenido:**
- Instalación y configuración de Visual Studio Community 2022
- Integración de librerías OpenGL, GLFW y GLEW
- Configuración de propiedades del proyecto (directorios de inclusión y enlace)
- Creación de la ventana de renderizado básica (800x600 px)
- Renderizado de un triángulo simple como prueba
- Configuración de Git y GitHub para control de versiones

**Conceptos clave:** Configuración de IDE, librerías gráficas, pipeline básico de OpenGL

---

### Práctica 1: Introducción a OpenGL
📍 **Rama:** `practica1_Introduccion_a_OpenGL-_(actualizada)`

**Objetivo:** Configurar un proyecto en OpenGL y aplicar shaders básicos para dibujar primitivas en 2D.

**Contenido:**
- Implementación de shaders (Vertex Shader y Fragment Shader)
- Compilación y enlace de programas de shader en GLSL
- Manejo de Vertex Buffer Objects (VBO) y Vertex Array Objects (VAO)
- Renderizado de primitivas gráficas 2D
- Control de colores mediante shaders
- Configuración del bucle de renderizado

**Conceptos clave:** Shaders, GLSL, pipeline programable, primitivas gráficas, buffers

---

### Práctica 2: Proyecciones y Transformaciones Geométricas
📍 **Rama:** `practica2_Proyecciones_y_Puertos_de_vista_Transformaciones_Geometricas_(actualizada)`

**Objetivo:** Comprender y aplicar los conceptos de proyecciones y transformaciones geométricas en gráficos por computadora.

**Contenido:**
- Construcción de un cubo 3D con colores en cada cara
- Implementación de matrices de transformación (traslación, rotación, escalado)
- Proyección ortográfica (mantiene dimensiones sin importar distancia)
- Proyección en perspectiva (objetos lejanos se ven más pequeños)
- Matrices Model, View y Projection (MVP)
- Uso de GLM para operaciones matemáticas con matrices

**Conceptos clave:** Transformaciones geométricas, matrices MVP, proyecciones, coordenadas homogéneas

---

### Práctica 3: Modelado Geométrico 3D
📍 **Rama:** `practica3_Modelado_Geometrico`

**Objetivo:** Aplicar el modelado geométrico en la representación de objetos 3D con OpenGL, partiendo de un cubo inicial.

**Contenido:**
- Modelado de objetos 3D mediante vértices y caras
- Creación de geometrías complejas a partir de primitivas básicas
- Aplicación de transformaciones a objetos individuales
- Manejo de normales para correcta visualización
- Composición de múltiples objetos en una escena
- Renderizado de objetos con colores uniformes

**Conceptos clave:** Modelado geométrico, vértices, caras, normales, mallas poligonales

---

### Práctica 4: Jerarquías de Objetos - Brazo Robótico
📍 **Rama:** `practica4_Modelado_Jerarquico`

**Objetivo:** Construir un brazo robótico en 3D aplicando el modelo jerárquico para comprender la relación padre-hijo en transformaciones.

**Contenido:**
- Implementación de sistemas jerárquicos de transformación
- Construcción de un brazo robótico articulado (bíceps, antebrazo, palma, dedos)
- Relaciones padre-hijo entre componentes
- Transformaciones acumulativas en jerarquías
- Matrices de transformación local y global
- Animación coordinada de partes móviles

**Conceptos clave:** Jerarquías de objetos, transformaciones padre-hijo, sistemas articulados, cinemática

---

### Práctica 5: Carga de Modelos 3D y Cámara Sintética
📍 **Rama:** `practica5_Carga_de_modelos_y_Camara_Sintetica`

**Objetivo:** Cargar y manipular modelos 3D externos en una escena gráfica, integrando una cámara sintética para navegación.

**Contenido:**
- Carga de modelos 3D desde archivos .obj
- Uso de la librería Assimp para importación de modelos
- Implementación de una cámara sintética configurable
- Navegación en el espacio 3D (movimiento y rotación de cámara)
- Matriz de vista y posicionamiento de cámara
- Renderizado de modelos complejos (RedDog.obj, miGato.obj)

**Conceptos clave:** Carga de modelos, formato OBJ, cámara sintética, matriz de vista, navegación 3D

---

### Práctica 6: Texturizado en OpenGL
📍 **Rama:** `practica6_Texturizado`

**Objetivo:** Aplicar texturas a superficies 3D para mejorar su representación visual.

**Contenido:**
- Carga de imágenes como texturas
- Mapeo de coordenadas UV
- Aplicación de texturas a objetos 3D
- Configuración de parámetros de textura (wrapping, filtering)
- Combinación de texturas con colores
- Uso de múltiples texturas en una misma escena
- Integración de texturas en el fragment shader

**Conceptos clave:** Texturas, coordenadas UV, mapeo de texturas, samplers, filtering, wrapping

---

### Práctica 7: Iluminación - Modelo Phong
📍 **Rama:** `practica7_Iluminación_1`

**Objetivo:** Implementar el modelo de iluminación Phong para comprender los principios fundamentales de la iluminación en gráficos.

**Contenido:**
- Implementación del modelo de iluminación de Phong
- Componente de luz ambiental
- Componente de luz difusa (Lambertiana)
- Componente de luz especular (reflexión)
- Cálculo de vectores normales
- Propiedades de materiales (coeficientes de reflexión)
- Posicionamiento de fuentes de luz

**Conceptos clave:** Modelo Phong, iluminación ambiental/difusa/especular, normales, materiales

---

### Práctica 8: Técnicas Avanzadas de Iluminación
📍 **Rama:** `practica8_Iluminacion_2`

**Objetivo:** Implementar diferentes técnicas de iluminación en una escena tridimensional utilizando OpenGL y GLSL.

**Contenido:**
- Múltiples fuentes de luz en una escena
- Luces direccionales, puntuales y focos (spotlights)
- Atenuación de luz con la distancia
- Transformación de normales al espacio de vista
- Combinación de múltiples luces en fragment shader
- Optimización de cálculos de iluminación
- Efectos de iluminación avanzados

**Conceptos clave:** Múltiples luces, tipos de luces, atenuación, transformación de normales, espacios de coordenadas

---

### Práctica 9: Animación 3D en Tiempo Real
📍 **Rama:** `practica9_Animacion_Basica`

**Objetivo:** Implementar un sistema de animación 3D en tiempo real para comprender los fundamentos de las transformaciones geométricas aplicadas progresivamente.

**Contenido:**
- Sistema de animación mediante transformaciones progresivas
- Control de tiempo y frames por segundo (FPS)
- Interpolación lineal de movimientos
- Animación de objetos mediante matrices de transformación
- Bucle de animación continuo
- Sincronización temporal de animaciones
- Transformaciones basadas en tiempo delta

**Conceptos clave:** Animación en tiempo real, interpolación, delta time, bucle de animación, FPS

---

### Práctica 10: Sistema de Animación por Keyframes
📍 **Rama:** `practica10_Animacion_por_Keyframes`

**Objetivo:** Desarrollar un sistema completo de animación por keyframes para controlar un modelo 3D articulado.

**Contenido:**
- Implementación de sistema de keyframes
- Animación de modelo 3D de perro articulado
- Control independiente de extremidades (cabeza, cola, patas)
- Interpolación entre keyframes
- Estructuras de datos para almacenar animaciones
- Reproducción cíclica de animaciones
- Sincronización de múltiples animaciones simultáneas
- Sistema de control de animación mediante teclado

**Conceptos clave:** Keyframes, animación por cuadros clave, interpolación, sistemas articulados, control de animación

---

## 💻 Compilación y ejecución

### Requisitos del sistema
- **Sistema Operativo:** Windows 10/11
- **IDE:** Visual Studio Community 2022 (o superior)
- **OpenGL:** 4.0 o superior
- **Tarjeta Gráfica:** Compatible con OpenGL 4.0+

### Dependencias
Todas las dependencias están incluidas en cada rama del proyecto:
- GLFW 3.x
- GLEW 2.x
- GLM 0.9.9+
- Assimp (para prácticas con carga de modelos)
- stb_image.h (para carga de texturas)

### Pasos para compilar y ejecutar

1. **Clonar la rama deseada:**
```bash
# Para la Práctica 0 (rama master):
git clone https://github.com/anaisabelkitty/Computacion-Grafica.git
cd Computacion-Grafica

# Para otras prácticas, usa el nombre específico de la rama
# Ejemplo para Práctica 3:
git clone -b practica3_Modelado_Geometrico https://github.com/anaisabelkitty/Computacion-Grafica.git
cd Computacion-Grafica
```

2. **Abrir el proyecto en Visual Studio:**
   - Buscar el archivo `.sln` en la carpeta del proyecto
   - Doble clic para abrir con Visual Studio

3. **Verificar configuración:**
   - Asegurarse de que el proyecto esté configurado para x64
   - Verificar que las rutas de inclusión y bibliotecas sean correctas
   - Las configuraciones ya están establecidas en cada proyecto

4. **Compilar:**
   - Seleccionar configuración: `Debug` o `Release`
   - Menú: `Build` → `Build Solution` (o presionar `Ctrl+Shift+B`)

5. **Ejecutar:**
   - Presionar `F5` para ejecutar con depuración
   - O `Ctrl+F5` para ejecutar sin depuración

### Estructura típica de carpetas
```
practica/
├── configInicial/          # Proyecto principal
│   ├── Source.cpp          # Código fuente principal
│   ├── *.vs / *.sln        # Archivos de Visual Studio
│   └── x64/                # Binarios compilados
├── shaders/                # Shaders GLSL
│   ├── shader.vs           # Vertex Shader
│   └── shader.fs           # Fragment Shader
├── models/                 # Modelos 3D (.obj)
├── textures/              # Texturas (.png, .jpg)
└── include/               # Archivos de encabezado
    ├── Camera.h
    ├── Shader.h
    └── Model.h
```

### Controles comunes
Los controles varían según la práctica, pero generalmente incluyen:
- **W/A/S/D:** Movimiento de cámara
- **Mouse:** Orientación de cámara
- **Flechas:** Transformaciones de objetos
- **ESC:** Salir de la aplicación
- **Teclas numéricas:** Cambio de modos/animaciones

Consulta el código fuente de cada práctica para controles específicos.

## 📝 Notas importantes

- La rama **`master`** contiene la **Práctica 0** (Configuración del Entorno)
- Las demás prácticas tienen nombres descriptivos que identifican su contenido
- Cada rama es **independiente** y contiene únicamente los archivos de su práctica correspondiente
- No mezcles código entre ramas para mantener la organización del repositorio
- Todos los proyectos parten de una base común llamada `configInicial`
- Las prácticas están diseñadas para construirse progresivamente sobre conceptos previos
- Algunas ramas tienen el sufijo `_(actualizada)` indicando que son versiones mejoradas

## 🏫 Información Académica

- **Universidad:** Universidad Nacional Autónoma de México (UNAM)
- **Facultad:** Facultad de Ingeniería
- **División:** Ingeniería Eléctrica
- **Carrera:** Ingeniería en Computación
- **Materia:** Computación Gráfica e Interacción Humano Computadora
- **Periodo:** 2024-2025

## 👤 Autor

**Ana Isabel Flores Cerqueda**
- Código: 319051988
- GitHub: [@anaisabelkitty](https://github.com/anaisabelkitty)
- Universidad: UNAM - Facultad de Ingeniería

## 📄 Licencia

Este proyecto es material académico desarrollado para fines educativos en el curso de Computación Gráfica. El código y los recursos están disponibles para propósitos de aprendizaje y referencia.

## 🤝 Agradecimientos

- Profesores del curso de Computación Gráfica e Interacción Humano Computadora
- Facultad de Ingeniería, UNAM
- Comunidad de OpenGL y recursos educativos en línea

## 📚 Referencias

- [LearnOpenGL](https://learnopengl.com/) - Tutorial completo de OpenGL
- [OpenGL Documentation](https://www.opengl.org/documentation/)
- [GLFW Documentation](https://www.glfw.org/documentation.html)
- [GLM Documentation](https://glm.g-truc.net/)

---

⭐ Si este repositorio te fue útil para aprender Computación Gráfica, considera darle una estrella ⭐

**Última actualización:** Noviembre 2025
