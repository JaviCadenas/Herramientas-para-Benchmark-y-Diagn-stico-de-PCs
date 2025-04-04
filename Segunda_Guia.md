# Mini Guía de Prime95

## Introducción

**Prime95** es una herramienta de estrés y prueba de estabilidad para CPUs, ampliamente usada por:

- **Overclockers**: Verificar estabilidad bajo carga extrema.
- **Usuarios avanzados**: Detectar errores en la CPU o RAM.
- **Benchmarking**: Medir rendimiento en cálculos matemáticos (usando el algoritmo *GIMPS*).

---

## Descarga e Instalación

1. **Descarga**:
   
   - Ve al sitio oficial: [www.mersenne.org/download](https://www.mersenne.org/download/).
   - Selecciona la versión para tu sistema (Windows/Linux).
2. **Instalación**:
   
   - Descomprime el archivo ZIP descargado.
   - Ejecuta `prime95.exe` (no requiere instalación).

---

## Uso Básico

1. **Configuración inicial**:
   
   - Al iniciar, el programa pregunta el tipo de prueba:
     - **Just Stress Testing**: Para pruebas de estrés.
     - **Join GIMPS**: Para contribuir a proyectos de investigación.
   - Selecciona *Just Stress Testing*.
2. **Prueba de estrés**:
   
   - Ve al menú `Options > Torture Test`.
   - Elige un perfil según tu objetivo:
     - **Small FFTs**: Máxima carga en la CPU (calentamiento rápido).
     - **Blend**: Prueba CPU y RAM (recomendado para estabilidad general).
       ![Captura Torture Test](https://www.techpowerup.com/download/images/13_large.png)
3. **Interpretación de resultados**:
   
   - **Sin errores**: Si Prime95 no muestra warnings/errores, el sistema es estable.
   - **Errores detectados**: Indican inestabilidad (overclock fallido, temperatura alta, RAM defectuosa).
   - **Temperaturas**: Monitorea con herramientas como *Core Temp* o *HWMonitor* (evita >95°C en CPUs modernas).

---

