## API Platform

Es un framework para crear APIs RESTful y GraphQL en Symfony, facilitando la creación de servicios eficientes y escalables con soporte para documentación automática y validación de datos.

## GraphQL

Es un lenguaje de consulta para APIs que permite a los clientes pedir solo los datos que necesitan, evitando sobrecarga de información. Soporta:

- **Consultas (Queries)**: Solicitudes para obtener datos específicos de la API, pidiendo solo los campos necesarios.
- **Mutaciones (Mutations)**: Operaciones para modificar datos en la API, como crear, actualizar o eliminar entradas.
- **Suscripciones (Subscriptions)**: Permite a los clientes recibir actualizaciones en tiempo real. A través de las suscripciones, el servidor puede enviar datos automáticamente cuando ocurre un cambio en la información, lo que es útil para aplicaciones que necesitan recibir datos en tiempo real (por ejemplo, en aplicaciones de mensajería o de seguimiento en vivo).

## RESTful

Se refiere a las APIs que siguen los principios del estilo arquitectónico **REST** (Representational State Transfer). Las características clave son:

-  **Recursos identificados por URLs**: Los recursos (usuarios, productos, etc.) son identificados por URLs únicas, como `/users/123`.

- **Operaciones CRUD**: Usando el protocolo HTTP para crear, leer, actualizar y eliminar recursos:

    - **GET**: Obtener datos.
    - **POST**: Crear nuevos recursos.
    - **PUT/PATCH**: Actualizar recursos existentes.
    - **DELETE**: Eliminar recursos.

---

# Diferencias entre REST y GraphQL

- **Enfoque:**

    - **REST:** Basado en recursos (URLs), donde cada recurso tiene su propia URL.
    - **GraphQL:** Basado en consultas, donde el cliente define los datos exactos que necesita.

- **Operaciones:**

    - **REST:** Utiliza los métodos HTTP estándar: GET, POST, PUT, DELETE.
    - **GraphQL:** Utiliza consultas y mutaciones definidas por el cliente.

- **Respuesta:**

    - **REST:** Responde con una estructura fija de datos, que a menudo es excesiva o insuficiente.
    - **GraphQL:** Responde con exactamente los datos solicitados, sin más ni menos.

- **Estructura de Datos:**

    - **REST:** Respuesta predefinida por el servidor, a menudo contiene datos innecesarios.
    - **GraphQL:** El cliente controla qué campos o propiedades se devolverán.

- **Versionado:**

    - **REST:** Las versiones de la API se manejan a través de rutas (por ejemplo, `/api/v1/`).
    - **GraphQL:** No es necesario versionar la API, ya que las consultas son flexibles.

- **Flexibilidad:**

    - **REST:** Menos flexible: el cliente solo puede acceder a lo que el servidor expone.
    - **GraphQL:** Muy flexible: el cliente puede hacer consultas personalizadas.

- **Manejo de múltiples recursos:**

    - **REST:** Requiere múltiples solicitudes para obtener información de varios recursos relacionados.
    - **GraphQL:** Permite obtener datos de múltiples recursos en una sola consulta.

- **Desempeño:**

    - **REST:** Puede ser menos eficiente debido a la sobrecarga de datos innecesarios.
    - **GraphQL:** Más eficiente al obtener solo los datos necesarios.


---

# Herramientas para interactuar con APIs

## Swagger UI

- **Qué es**: Interfaz visual para interactuar con APIs RESTful, basada en la especificación OpenAPI.

- **Cómo funciona**: Genera una interfaz interactiva que muestra las rutas, métodos y detalles de la API a partir del archivo de especificación.

- **Beneficios**:

  - Prueba endpoints directamente desde la interfaz.
  - Documentación clara y accesible.
  - Facilita la interacción con la API para pruebas y desarrollo.
- **Ejemplo de uso**: Se integra en una API RESTful, permitiendo a los usuarios ver y probar los endpoints.

## GraphQL Playground

- **Qué es**: Herramienta de desarrollo y depuración para interactuar con APIs GraphQL.
- **Cómo funciona**: Ofrece una interfaz para escribir consultas y mutaciones, explorar el esquema de la API y obtener respuestas detalladas.

- **Beneficios**:

  - Permite explorar y probar consultas GraphQL.
  - Autocompletado y validación del esquema.
  - Facilita la depuración y desarrollo mediante consultas en vivo.
- **Ejemplo de uso**: Permite realizar consultas específicas y obtener solo los datos necesarios, a diferencia de las múltiples solicitudes en REST.

---

## Resumen:

- **REST**: Protocolo más tradicional y simple, donde el servidor define las respuestas y las rutas para los recursos. Es adecuado para APIs que no necesitan gran flexibilidad en las consultas.
- **GraphQL**: Protocolo más moderno, flexible y eficiente, donde el cliente tiene control sobre las consultas y puede obtener solo los datos que necesita en una sola solicitud.
