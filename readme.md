# Alke Wallet - Simulación de Billetera Digital

Este proyecto es una aplicación web de billetera digital que permite a los usuarios gestionar su saldo, registrar contactos y realizar transferencias simuladas. El sistema utiliza **jQuery** para la lógica de la interfaz y **LocalStorage** para la persistencia de datos.

## 🚀 Funcionalidades

- **Gestión de Saldo:** Visualización del saldo actual actualizado en tiempo real con formato de moneda local (`es-CL`).
- **Depósitos:** Interfaz para cargar fondos a la cuenta con validaciones de montos.
- **Agenda de Contactos:** - Registro de contactos con nombre, cuenta y banco.
  - Selección visual de contactos mediante una lista interactiva.
- **Transferencias:** Sistema de envío de dinero con validación de fondos suficientes.
- **Historial de Movimientos:** Registro automático de los últimos 5 movimientos (depósitos y envíos) detallando fecha, hora y beneficiario.
- **Persistencia:** Los datos se mantienen guardados en el navegador aunque se cierre la sesión o se refresque la página.

## 🛠️ Tecnologías Utilizadas

* [jQuery](https://jquery.com/) - Biblioteca de JavaScript para manipulación del DOM.
* [Bootstrap 5](https://getbootstrap.com/) - Framework CSS para el diseño responsivo y componentes.
* [JavaScript (ES6+)](https://developer.mozilla.org/es/docs/Web/JavaScript) - Lógica de programación.
* **LocalStorage API** - Almacenamiento local de datos.

## 📂 Estructura del Código

El proyecto ha sido migrado de Vanilla JS a **jQuery**, optimizando procesos como:

* **Selectores:** Uso de `$('#id')` en lugar de `document.getElementById`.
* **Eventos:** Implementación de `.on('submit')` y `.on('click')`.
* **DOM Dinámico:** Uso de `.append()` y `.empty()` para la renderización de listas de contactos y movimientos.

## 🔧 Instalación

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/claudio-hcn/actividad-l6-m2.git](https://github.com/claudio-hcn/actividad-l6-m2.git)