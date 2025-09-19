-----

### `README.md` (Contenido)

# Proyecto Integrador 1: Análisis de Datos para Marketing Gastronómico 📊

Este proyecto de **Data Science** se centra en el análisis de datos de clientes y restaurantes de la ciudad de Miami, obtenidos a través de la **API de Yelp**. El objetivo principal es identificar patrones de consumo y generar `insights` accionables que puedan guiar decisiones de marketing en la industria gastronómica.

-----

### Descripción y Metodología del Proyecto 🧑‍💻

El proyecto se desarrolló en tres etapas principales, cada una documentada en un `Jupyter Notebook`:

  - **1. Limpieza y Preparación de Datos de Clientes:**

      - Análisis de la calidad de los datos para identificar y corregir valores nulos, erróneos y duplicados.
      - Imputación de variables clave como `edad`, `frecuencia_visita`, `promedio_gasto` y `preferencias_alimenticias`.

  - **2. Obtención y Tratamiento de Datos de Yelp:**

      - Uso de la librería `requests` para consumir la **API de Yelp** y obtener información de 500 restaurantes en Miami.
      - Creación de un **rating ponderado** para los restaurantes, ajustado por la cantidad de reseñas para ofrecer un `ranking` más preciso y justo.

  - **3. Integración de Datos y Algoritmo de Recomendación:**

      - **Integración de los datos** de clientes y restaurantes para conectar el perfil del usuario con las características de los establecimientos.
      - Análisis descriptivo y visualizaciones para responder a preguntas de negocio sobre la relación entre el estrato socioeconómico, el gasto y las preferencias del cliente.
      - Desarrollo de una **función de recomendación** que sugiere restaurantes basándose en el perfil del cliente y el `rating` ponderado.

-----

### Resultados Clave 📈

  - **Segmentación de Clientes:** La edad y el estrato socioeconómico son `drivers` clave del consumo. Los clientes más jóvenes prefieren opciones **veganas/vegetarianas** 🌱 y métodos de pago digitales, mientras que los de estrato alto son los más rentables.

  - **Análisis de Mercado:** Los restaurantes de precio medio (`$$`) concentran el mayor volumen de reseñas, mientras que los de alta gama (`$$$` y `$$$$`) tienen una valoración promedio superior.

  - **Recomendaciones de Negocio:**

      - Crear campañas de marketing segmentadas (ej. promociones de `Brunch` para el público joven o eventos exclusivos para clientes de estrato alto).
      - Implementar programas de fidelización para clientes de alta frecuencia.
      - Utilizar el algoritmo de recomendación para personalizar las comunicaciones con los clientes.

-----

### Mejoras a Futuro 🚀

  - **Modularización del Código:** Refactorizar el código para organizar las funciones de limpieza y análisis en módulos separados y reutilizables.
  - **Validación de Datos:** Implementar `tests` simples para asegurar la calidad de los datos a lo largo del `pipeline` de análisis.
  - **Análisis Adicionales:** Explorar técnicas de `clustering` para una segmentación de clientes más detallada y enriquecer el modelo de recomendación.

-----

### Requisitos e Instalación ⚙️

Este proyecto utiliza las siguientes librerías principales de Python. Puedes instalarlas con `pip`:

```bash
pip install pandas numpy matplotlib seaborn requests ast
```

**Nota sobre la API de Yelp:**
Por motivos de seguridad, la clave de la API de Yelp **no se incluye** en este repositorio. Para ejecutar el cuaderno `Avance_API_Yelp.ipynb`, deberás obtener tu propia clave de la [Yelp Fusion API](https://www.google.com/search?q=https://www.yelp.com/developers/documentation/fusion/get_started) y reemplazar el `token` en el código.

**Archivos de Datos:**
Por cuestiones de tamaño y confidencialidad, la base de datos de usuarios original y los archivos generados durante el proceso **no están incluidos** en este repositorio. Si deseas reproducir el análisis o necesitas acceso a la base de datos, no dudes en contactarme.

-----

### **Soporte y Contacto** 📞

**Desarrolladora:** Leila Abduca
**Email:** leiabduca@gmail.com
**LinkedIn:** [Leila Abduca](https://linkedin.com/in/leila-abduca )

-----
