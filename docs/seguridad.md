# Políticas de Seguridad de la Aplicación Móvil

## 1. Introducción

PixelVault Store es un proyecto académico desarrollado con React Native y JavaScript.

La aplicación utiliza almacenamiento local mediante AsyncStorage para conservar información relacionada con usuarios, sesión y compras.

## 2. Almacenamiento local

PixelVault utiliza AsyncStorage para guardar información en el dispositivo.

Las principales claves utilizadas son:

- `@pixelvault_sesion`
- `@pixelvault_usuarios`
- `@pixelvault_compras`

La clave `@pixelvault_sesion` permite conservar la sesión activa del usuario.

La información de los usuarios y las compras también se mantiene localmente para permitir el funcionamiento de la aplicación después de cerrarla.

## 3. Autenticación

La aplicación cuenta con:

- Registro de usuarios.
- Inicio de sesión.
- Cierre de sesión.
- Recuperación de contraseña.
- Validación de credenciales.

Durante el inicio de sesión se comprueba que el correo y la contraseña coincidan con una cuenta registrada.

## 4. Validaciones

PixelVault realiza diferentes validaciones antes de ejecutar determinadas operaciones.

Entre ellas:

- Verificación de credenciales durante el inicio de sesión.
- Verificación de correos registrados.
- Comprobación de coincidencia de contraseñas durante la recuperación.
- Verificación de disponibilidad de productos.
- Validación de los datos utilizados en el pago simulado.
- Validación de longitud de tarjeta y CVV.

## 5. Protección de la sesión

Cuando un usuario inicia sesión correctamente, su correo electrónico se almacena utilizando la clave:

`@pixelvault_sesion`

Al abrir nuevamente la aplicación, se comprueba la información almacenada para determinar si existe una sesión válida.

Al cerrar sesión, se elimina la sesión activa.

## 6. Seguridad del proceso de pago

El proceso de pago de PixelVault es únicamente una simulación.

La aplicación no se conecta con:

- Bancos.
- Plataformas financieras.
- Pasarelas de pago reales.
- Servicios externos de procesamiento de tarjetas.

Por esta razón, no deben utilizarse datos reales de tarjetas dentro de la aplicación.

## 7. Limitaciones actuales de seguridad

PixelVault es un proyecto académico y actualmente utiliza almacenamiento local.

Las cuentas se almacenan mediante AsyncStorage y las contraseñas no cuentan actualmente con un sistema de hashing o cifrado mediante un servidor.

Además, no existe un sistema de autenticación conectado a un backend.

## 8. Mejoras de seguridad futuras

Para una versión futura podrían implementarse:

- Backend para gestionar la autenticación.
- Base de datos en la nube.
- Hashing seguro de contraseñas.
- Almacenamiento seguro de credenciales.
- Autenticación más robusta.
- Gestión segura de sesiones.
- Integración con una pasarela de pago real.
- Protección de información sensible.

## 9. Recomendaciones

Mientras PixelVault se mantenga como proyecto académico:

- No utilizar contraseñas reales.
- No introducir números reales de tarjetas.
- No utilizar información bancaria real.
- Mantener la aplicación como una demostración académica.
- No considerar el sistema actual como una plataforma de comercio electrónico real.

## 10. Conclusión

PixelVault incorpora validaciones, control de sesión y almacenamiento local para permitir el funcionamiento de sus principales características.

Sin embargo, debido a que se trata de un proyecto académico basado en almacenamiento local, existen limitaciones de seguridad que deberán solucionarse mediante un backend, autenticación segura y almacenamiento protegido en futuras versiones.
