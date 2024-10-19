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

## Estructura del Proyecto

El proyecto sigue la estructura estándar de una aplicación TypeScript:

facturacion-typescript/ │ ├── src/ │ ├── Articulo.ts # Clase para la gestión de artículos │ ├── Cliente.ts # Clase para la gestión de clientes │ ├── DetalleFactura.ts # Clase para la gestión de los detalles de las facturas │ ├── Factura.ts # Clase para la gestión de facturas │ ├── TestB.ts # Clase para ejecutar el test del sistema de facturación │ ├── dist/ │ └── (archivos compilados en JavaScript) │ ├── node_modules/ │ ├── tsconfig.json # Configuración de TypeScript ├── package.json # Dependencias y scripts del proyecto └── README.md # Este archivo


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
    node TestB.js
    ```

Esto generará una salida en la terminal que mostrará el total facturado en efectivo y con tarjeta de crédito para el cliente de prueba.

### Ejemplo de Salida

```bash
Total facturado en efectivo: 850.0
Total facturado con tarjeta de crédito: 2500.0


¡Por supuesto! Aquí tienes el contenido del README.md completo para que puedas copiarlo todo de una vez:

markdown
Copiar código
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

## Estructura del Proyecto

El proyecto sigue la estructura estándar de una aplicación TypeScript:

facturacion-typescript/ │ ├── src/ │ ├── Articulo.ts # Clase para la gestión de artículos │ ├── Cliente.ts # Clase para la gestión de clientes │ ├── DetalleFactura.ts # Clase para la gestión de los detalles de las facturas │ ├── Factura.ts # Clase para la gestión de facturas │ ├── TestB.ts # Clase para ejecutar el test del sistema de facturación │ ├── dist/ │ └── (archivos compilados en JavaScript) │ ├── node_modules/ │ ├── tsconfig.json # Configuración de TypeScript ├── package.json # Dependencias y scripts del proyecto └── README.md # Este archivo

markdown
Copiar código

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
    node TestB.js
    ```

Esto generará una salida en la terminal que mostrará el total facturado en efectivo y con tarjeta de crédito para el cliente de prueba.

### Ejemplo de Salida

```bash
Total facturado en efectivo: 850.0
Total facturado con tarjeta de crédito: 2500.0
Consideraciones
Asegúrate de compilar el código antes de ejecutarlo, ya que este proyecto está desarrollado en TypeScript y debe ser transformado a JavaScript.
El proyecto utiliza tsconfig.json para compilar automáticamente todo el código fuente dentro de la carpeta src.
Herramientas Utilizadas
Node.js: Plataforma para la ejecución de código JavaScript fuera del navegador.
TypeScript: Superconjunto de JavaScript que añade tipos estáticos.
npm: Gestor de paquetes de Node.js.
