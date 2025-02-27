![Image](https://github.com/user-attachments/assets/9bf3b4cc-9a1c-4b8b-81e3-797905cd74e7)

# Modelo-Vista-Controlador (MVC)

El **Modelo-Vista-Controlador (MVC)** es un patrón de arquitectura de software que separa la lógica de una aplicación en tres componentes interconectados:

1. **Modelo**: Gestiona los datos y la lógica de negocio.
2. **Vista**: Muestra la información al usuario (interfaz).
3. **Controlador**: Recibe las entradas del usuario, las procesa y actualiza el modelo o la vista.

---

## Componentes del MVC

### 1. Modelo
- Representa los datos y reglas de negocio.
- Se comunica con la base de datos.
- Notifica a la vista cuando hay cambios.

### 2. Vista
- Muestra la información al usuario.
- No contiene lógica de negocio.
- Recibe datos del modelo.

### 3. Controlador
- Actúa como intermediario entre el modelo y la vista.
- Procesa las entradas del usuario.
- Actualiza el modelo y refresca la vista.

---

## Flujo de trabajo

1. El usuario interactúa con la vista.
2. El controlador recibe la entrada.
3. El controlador actualiza el modelo.
4. El modelo notifica a la vista.
5. La vista se actualiza.

<br><img width="720" alt="Image" src="https://github.com/user-attachments/assets/61867d24-e345-4994-a0ee-9c811cd38bec" />

---

## Ventajas

- **Separación de preocupaciones**: Facilita el mantenimiento.
- **Reutilización**: Componentes pueden ser reutilizados.
- **Escalabilidad**: Fácil de extender.

---

## Desventajas

- **Complejidad**: Puede ser excesivo para aplicaciones pequeñas.
- **Curva de aprendizaje**: Requiere entender bien el patrón.

---

## Ejemplo de uso

- **Frameworks web**: Ruby on Rails, Django, Laravel.
- **Aplicaciones de escritorio**: Java Swing, .NET.
