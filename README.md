# Facturación con TypeScript

Este proyecto implementa un sistema de facturación simple en TypeScript. A través de la creación de clases como `Cliente`, `Articulo`, `Factura` y `DetalleFactura`, el sistema permite simular la emisión de facturas y el cálculo de totales por tipo de pago.

## Requisitos Previos

Antes de ejecutar este proyecto, asegúrate de tener lo siguiente instalado en tu sistema:

- [Node.js](https://nodejs.org/) (versión 14 o superior)
- [TypeScript](https://www.typescriptlang.org/) (instalado globalmente)

## Instrucciones de Instalación

1. Clona el repositorio en tu máquina local:
    ```bash
    git clone https://github.com/tu_usuario/facturacion-typescript.git
    ```

2. Navega a la carpeta del proyecto:
    ```bash
    cd facturacion-typescript
    ```

3. Instala las dependencias necesarias:
    ```bash
    npm install
    ```

4. Compila el código TypeScript a JavaScript:
    ```bash
    tsc
    ```


### Descripción de Clases

- **Articulo:** Define los productos o servicios con precio y unidad de medida.
- **DetalleFactura:** Representa los detalles de una factura, incluyendo cantidad y el artículo asociado.
- **Factura:** Gestiona el total de ítems y el total final de la factura, considerando los recargos.
- **Cliente:** Almacena la información del cliente y permite calcular el total facturado por tipo de pago.
- **TestB:** Clase que realiza pruebas con instancias de cliente, artículos y facturas, calculando totales y mostrando resultados en la terminal.

## Ejecutar el Programa

1. Compila el código TypeScript:
    ```bash
    tsc
    ```

2. Navega a la carpeta `dist` (donde están los archivos compilados en JavaScript):
    ```bash
    cd dist
    ```

3. Ejecuta el archivo `TestB.js` utilizando Node.js:
    ```bash
    node TestB.js | node TestB.js
    ```

Esto generará una salida en la terminal que mostrará el total facturado en efectivo y con tarjeta de crédito para el cliente de prueba.