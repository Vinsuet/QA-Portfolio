# Plan de Pruebas Funcionales (Test Plan) - SauceDemo

- Proyecto: E-Commerce SauceDemo
- Autor: Vincent Leonardo Arias
- Rol: QA Tester Jr.
- Versión: 1.0

## 1. Alcance (Scope)
El objetivo de este plan es evaluar la calidad y el comportamiento funcional de los módulos principales del sitio e-commerce SauceDemo (https://www.saucedemo.com/).

### Funcionalidades DENTRO del alcance:
- Módulo de Autenticación (Login / Logout) con distintos tipos de usuario.
- Catálogo de productos: Agregar y remover artículos.
- Carrito de compras: Confirmación de ítems seleccionados.
- Flujo de Checkout: Formulario de datos de envío y pantalla de resumen.

### Funcionalidades FUERA del alcance:
- Pruebas de rendimiento y carga (Performance Testing).
- Pruebas de seguridad avanzadas.
- Integración con pasarelas de pago reales.

## 2. Tipos de Pruebas a Ejecutar
- Pruebas de Humo (Smoke Testing): Validación del flujo crítico principal (Login -> Agregar producto -> Checkout exitoso).
- Pruebas Funcionales (Black Box): Verificación de reglas de negocio en listas y botones.
- Pruebas Negativas: Manejo de errores al omitir campos obligatorios o usar credenciales inválidas.

## 3. Entorno de Pruebas (Environment)
- Navegador: Google Chrome
- Sistema Operativo: Windows 11
- URL objetivo: https://www.saucedemo.com/
- Usuarios de prueba: standard_user, locked_out_user
- Contraseña universal: secret_sauce

## 4. Criterios de Aceptación y Cierre
- Ejecución del 100% de los casos de prueba definidos.
- Registro detallado de cualquier inconsistencia en la carpeta de reportes de bugs.
