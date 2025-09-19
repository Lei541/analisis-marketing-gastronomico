---

### `README.md` (Contenido)

# Proyecto Integrador 1: Análisis de Datos para Marketing Gastronómico 📊

Este proyecto de **Data Science** se centra en el análisis de datos de clientes y restaurantes de la ciudad de Miami, obtenidos a través de la **API de Yelp**. El objetivo principal es identificar patrones de consumo y generar `insights` accionables que puedan guiar decisiones de marketing en la industria gastronómica.

---

### Descripción y Metodología del Proyecto 🧑‍💻

El proyecto se desarrolló en tres etapas principales, cada una documentada en un `Jupyter Notebook`:

- **1. Limpieza y Preparación de Datos de Clientes:**
    - Análisis de la calidad de los datos para identificar y corregir valores nulos, erróneos y duplicados.
    - Imputación de variables clave como `edad`, `frecuencia_visita`, `promedio_gasto` y `preferencias_alimenticias`.

- **2. Obtención y Tratamiento de Datos de Yelp:**
    - Uso de la librería `requests` para consumir la **API de Yelp** y obtener información de 500 restaurantes en Miami.
    - Creación de un **rating ponderado** para los restaurantes, ajustado por la cantidad de reseñas para ofrecer un `ranking` más preciso y justo.

- **3. Análisis Integrado y Algoritmo de Recomendación:**
    - Unificación de los `datasets` de clientes y restaurantes.
    - Análisis descriptivo y visualizaciones para responder a preguntas de negocio sobre la relación entre el estrato socioeconómico, el gasto y las preferencias del cliente.
    - Desarrollo de una **función de recomendación** que sugiere restaurantes basándose en el perfil del cliente y el `rating` ponderado.

---

### Resultados Clave 📈

- **Segmentación de Clientes:** La edad y el estrato socioeconómico son `drivers` clave del consumo. Los clientes más jóvenes prefieren opciones **veganas/vegetarianas** 🌱 y métodos de pago digitales, mientras que los de estrato alto son los más rentables.

- **Análisis de Mercado:** Los restaurantes de precio medio (`$$`) concentran el mayor volumen de reseñas, mientras que los de alta gama (`$$$` y `$$$$`) tienen una valoración promedio superior.

- **Recomendaciones de Negocio:**
    - Crear campañas de marketing segmentadas (ej. promociones de `Brunch` para el público joven o eventos exclusivos para clientes de estrato alto).
    - Implementar programas de fidelización para clientes de alta frecuencia.
    - Utilizar el algoritmo de recomendación para personalizar las comunicaciones con los clientes.

---

### Mejoras a Futuro 🚀

- **Modularización del Código:** Refactorizar el código para organizar las funciones de limpieza y análisis en módulos separados y reutilizables.
- **Validación de Datos:** Implementar `tests` simples para asegurar la calidad de los datos a lo largo del `pipeline` de análisis.
- **Análisis Adicionales:** Explorar técnicas de `clustering` para una segmentación de clientes más detallada y enriquecer el modelo de recomendación.
