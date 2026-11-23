# Registro-Ventas-Super-T-App
Sistema de registro de ventas en Solana para Super T.
# Super T — Sistema de registro de ventas en Solana

## 1. Descripción del proyecto

Super T es un programa desarrollado con Rust y Anchor para la blockchain de Solana. Permite administrar un registro de clientes y sus ventas, así como consultar y modificar la información almacenada.

El proyecto utiliza una cuenta PDA para guardar la información del negocio, los clientes y sus ventas.

## 2. Red y datos del programa

- **Red:** Solana Devnet.
- **Framework:** Anchor.
- **Lenguaje del programa:** Rust.
- **Cliente:** TypeScript.
- **Program ID:** `Hv2LRM6n6D8dw9xM4mUvynzCSuSCnNPbJvkDLeiqadNP`.
- **Nombre del negocio:** Super T.

## 3. Funcionalidades

El programa incluye las siguientes operaciones:

- Crear el registro del negocio.
- Registrar ventas asociadas a clientes.
- Registrar devoluciones.
- Cambiar el monto de una venta.
- Consultar la cantidad de compras de un cliente.
- Consultar los clientes y sus ventas.

El diseño contempla un máximo de 10 clientes y hasta 10 ventas por cliente.

## 4. Estructura del proyecto

- `lib.rs`: contiene la lógica del programa, las instrucciones, las cuentas y las estructuras de datos.
- `client.ts`: permite ejecutar las instrucciones y consultar la información del programa.
- `anchor.test.ts`: contiene las pruebas automatizadas del programa.

## 5. Pruebas realizadas

Se ejecutaron cinco pruebas automatizadas y todas finalizaron correctamente:

1. Crear el registro del negocio.
2. Registrar un cliente y sus ventas.
3. Cambiar el monto de una venta.
4. Realizar una devolución.
5. Consultar la cantidad de compras.

**Resultado:** 5 pruebas exitosas (*5 passing*).

## 6. Ejecución del cliente

El cliente TypeScript permite verificar la conexión y consultar los clientes registrados.

La consulta realizada mostró:

- Negocio: Super T.
- Último ID asignado: 1.
- Cantidad de clientes: 1.
- Cliente número 1.
- Compras: 1.
- Ventas en historial: 1.
- SKU: PAN.
- Descripción: Pan Bimbo.
- Monto: $50.

## 7. Resultado

El programa se compiló y desplegó correctamente en Solana Devnet. Las cinco pruebas automatizadas finalizaron satisfactoriamente y el cliente TypeScript logró consultar la información almacenada en la cuenta del programa.

**Proyecto: Super T — Sistema de registro de ventas en Solana.**
