# Guitar Wood - Validador de Formulario con React + TypeScript

##  Propósito del Proyecto

Este proyecto implementa un formulario de creación de cuenta utilizando **React + TypeScript**, aplicando validaciones dinámicas en tiempo real.

El objetivo principal es demostrar el uso de:

- Gestión de estado con React
- Tipado fuerte con TypeScript
- Validación dinámica de formularios
- Interfaz moderna con diseño responsivo

El formulario forma parte del módulo "Cuenta" del prototipo eCommerce **Guitar Wood**.

---

##  Tecnologías Utilizadas

- React 18
- TypeScript
- Vite (entorno de desarrollo rápido)
- CSS personalizado
- Node.js + npm

---

##  Implementación de Validaciones

Las validaciones se implementaron utilizando:

###  Gestión de Estado

Se utilizó `useState` para almacenar:

- Datos del formulario
- Estado de envío
- Visibilidad de contraseña

```ts
const [data, setData] = useState<FormData>({...})