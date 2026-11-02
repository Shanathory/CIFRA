# Política de Privacidad — CIFRA

**Última actualización:** 01 de Noviembre de 2026  
**Aplicación:** CIFRA — Finanzas Personales & Control de Francos  
**Paquete (Package Name):** `com.finanzastool.app`  
**Desarrollador:** Shanathory / CIFRA Team  
**Contacto:** `cifra.app.contact@gmail.com` (o abrir un issue en [GitHub Repository](https://github.com/Shanathory/CIFRA))

---

## 1. Introducción y Compromiso de Privacidad

En **CIFRA** creemos firmemente que tus datos financieros y personales son exclusivamente tuyos. Esta Política de Privacidad describe cómo funciona nuestra aplicación móvil y web con respecto a tu información.

Nuestra filosofía de diseño es **Local-First (100% Local y Fuera de Línea)**:
* **No requerimos registro de cuentas ni contraseñas.**
* **No poseemos servidores remotos que almacenen o procesen tus datos.**
* **Tus finanzas jamás se envían a internet ni a terceros.**

---

## 2. Información que Introduce el Usuario

CIFRA permite gestionar finanzas personales y registros laborales mediante la introducción voluntaria de:
* **Ingresos:** Cobros semanales, quincenales o mensuales en Pesos Argentinos (ARS) o USDT (criptoactivos).
* **Gastos y Pagos Fijos:** Montos, fechas de vencimiento, tarjetas de crédito, cuotas pendientes y prioridades.
* **Gastos Diarios:** Categorías, métodos de pago, notas descriptivas y montos consumidos.
* **Metas de Ahorro y Fondos:** Fondos de emergencia, compras deseadas y viajes.
* **Control de Francos:** Días de descanso acumulados, feriados trabajados y descansos gozados.

### ¿Dónde se guarda esta información?
Todos los datos antes mencionados se almacenan **única y exclusivamente en la memoria local de tu dispositivo** (mediante la base de datos interna `IndexedDB` y `localStorage` en un entorno seguro y aislado por el sistema operativo Android).

---

## 3. Recopilación, Transmisión y Compartición de Datos

* **Sin recolección externa:** CIFRA **NO** recolecta, transmite, vende, alquila ni comparte ningún dato personal, financiero o de uso con el desarrollador ni con terceras empresas.
* **Sin analíticas ni rastreo publicitario:** La aplicación **NO** incluye SDKs de publicidad (como Google AdMob), herramientas de telemetría, analíticas de comportamiento (como Google Analytics, Firebase Analytics) ni rastreadores de terceros.
* **Sin sincronización en la nube automática:** La aplicación funciona de manera completamente autónoma sin conexión a internet.

---

## 4. Permisos del Dispositivo

CIFRA solicita únicamente los permisos técnicos estrictamente indispensables para su funcionamiento en el entorno Android:

| Permiso | Finalidad |
| :--- | :--- |
| `android.permission.INTERNET` | Requerido por el motor de renderizado nativo WebView/Capacitor para la ejecución de la interfaz gráfica local. **No se utiliza para transmitir datos financieros a ningún servidor.** |
| `FileProvider` / Acceso a archivos temporales | Utilizado única y exclusivamente cuando el usuario decide voluntariamente **Exportar** una copia de seguridad o **Importar** un archivo `.json` de respaldo mediante el menú de Ajustes. |

CIFRA **NO** solicita acceso a tus contactos, ubicación geográfica (GPS), cámara, micrófono ni identificadores de hardware personal.

---

## 5. Copias de Seguridad (Backup) y Control del Usuario

El usuario tiene el control total sobre la portabilidad y permanencia de sus datos:
* **Exportación:** Podés generar en cualquier momento un archivo `.json` cifrado o plano para guardarlo donde prefieras (Google Drive personal, almacenamiento local, correo propio, etc.).
* **Eliminación definitiva:** Si deseás borrar todos tus datos, podés hacerlo instantáneamente desde el botón *"Restablecer datos"* en la pantalla de Ajustes, o simplemente borrando el almacenamiento de la app o desinstalándola de tu dispositivo. No queda rastro alguno de tus datos en ningún servidor externo.

---

## 6. Privacidad de Menores (COPPA y Regulaciones Aplicables)

Nuestra aplicación no está dirigida a menores de 13 años (ni menores de 16 años en jurisdicciones aplicables) y, dado que no recopilamos ningún tipo de datos personales de ningún usuario, no recopilamos a sabiendas información de niños.

---

## 7. Seguridad de los Datos

Dado que la información reside de forma nativa en tu dispositivo móvil, la seguridad de los datos depende de los mecanismos de protección de tu propio sistema operativo Android (como bloqueo por huella dactilar, PIN, patrón y el aislamiento de aplicaciones "App Sandbox").

---

## 8. Cambios a esta Política de Privacidad

Cualquier cambio menor o actualización técnica se reflejará en esta página con la fecha de "Última actualización" revisada. Dado que la aplicación no se conecta a internet para recopilar identificadores de contacto, te recomendamos revisar esta política a través del repositorio oficial de la app o la ficha de Google Play Store al actualizar la versión.

---

## 9. Contacto

Si tenés preguntas, sugerencias o dudas relativas a esta Política de Privacidad o al funcionamiento de CIFRA, podés contactarnos a través de:
* **Repositorio de GitHub:** [https://github.com/Shanathory/CIFRA](https://github.com/Shanathory/CIFRA)
* **Correo electrónico de soporte:** `cifra.app.contact@gmail.com`
