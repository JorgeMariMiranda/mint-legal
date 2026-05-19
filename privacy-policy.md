# Política de privacidad de Mint

**Versión 1.0** · Última actualización: 19 de mayo de 2026

Esta política explica qué datos recoge Mint, para qué los usa y con quién los comparte. Está escrita para que la entienda cualquiera, no solo abogados.

---

## 1. Quién es el responsable

- **Responsable**: Jorge Miranda (en adelante "el desarrollador").
- **Email de contacto**: jorgemarimiranda@gmail.com
- **Aplicación**: Mint — CRM para autónomos y micropymes (en adelante "la app").

Si tienes cualquier duda sobre tus datos, escríbenos al correo de arriba.

---

## 2. Qué datos trata Mint

### 2.1 Datos del titular (la persona que usa la app)
Cuando configuras tu negocio en la app, guardamos en **tu dispositivo**:
- Nombre / razón social
- NIF / CIF
- Dirección, código postal, ciudad, provincia
- Teléfono y email de contacto
- IBAN
- Logo y colores de marca
- Datos de configuración (plantillas, etiquetas personalizadas, preferencias)

### 2.2 Datos de tus clientes
Si añades clientes a tu CRM, almacenamos en **tu dispositivo**:
- Nombre, empresa, NIF
- Direcciones, teléfonos, emails
- Notas, etiquetas y categorías personalizadas
- Historial de pedidos, presupuestos, facturas y citas

### 2.3 Datos fiscales y comerciales
- Pedidos, presupuestos, facturas y borradores
- Gastos (incluidas fotos de tickets si las haces)
- Cobros, vencimientos e historial de pagos
- Resúmenes fiscales calculados localmente (303 / 130 / 347 / 349 / 390)

### 2.4 Datos opcionales según funcionalidad
- **Cuentas de correo IMAP / SMTP**: si conectas tu correo para automatizar el procesado de pedidos, guardamos las credenciales (usuario, contraseña, host) cifradas en tu dispositivo.
- **WhatsApp Business**: si activas el lector de notificaciones, leemos únicamente el preview del mensaje recibido para clasificarlo como posible pedido. Nada se sube a ningún servidor: la clasificación es local.
- **Cámara**: si fotografías tickets para registrar gastos, las fotos quedan en tu dispositivo.
- **Asistente IA (Gemini)**: si activas el asistente, tu pregunta y los datos relevantes que el asistente consulte se envían a Google Gemini bajo tu propia API key. Tú decides cuándo activarlo.
- **Holded (Verifactu)**: si conectas tu cuenta Holded para emitir facturas legales, los datos de la factura (cliente, líneas, importes, NIF) se transmiten a Holded bajo tu propia API key.
- **Copia de seguridad en Google Drive**: si activas la copia, los datos van **cifrados con contraseña** a tu propia cuenta de Drive. La contraseña la decides tú, nosotros no la conocemos.

### 2.5 Datos que NO recogemos
- Mint **no recoge analíticas** de uso ni telemetría.
- Mint **no incluye trackers publicitarios** ni SDKs de medición.
- Mint **no recoge tu ubicación**.
- Mint **no recoge contactos de tu agenda**.
- Mint **no envía nada a servidores del desarrollador**.

---

## 3. Dónde se almacenan tus datos

Todos los datos se almacenan **localmente en tu dispositivo Android** (base de datos SQLite cifrada por Android Keystore).

Las únicas salidas de tu dispositivo son las que tú activas voluntariamente:

| Servicio | Qué sale del móvil | Propósito |
|---|---|---|
| Holded API | Datos de la factura que decides emitir | Emisión fiscal Verifactu |
| Google Gemini API | Tu pregunta + datos consultados | Asistente IA |
| Google Drive (tu cuenta) | Backup cifrado con tu contraseña | Copia de seguridad |
| Tu servidor SMTP | El correo que el usuario decide enviar | Notificación al cliente |

Ninguno de estos datos pasa por servidores del desarrollador.

---

## 4. Base legal del tratamiento (RGPD)

- **Consentimiento**: aceptas esta política en el primer arranque y al usar funcionalidades opcionales (asistente IA, sincronización Drive, etc.).
- **Ejecución de contrato**: la app es la herramienta a través de la cual prestamos el servicio que has aceptado al instalarla.
- **Obligación legal**: la conservación de los datos fiscales (facturas, gastos) responde a la normativa fiscal española (Ley 58/2003 General Tributaria).
- **Interés legítimo**: la mejora del servicio sin tratamiento de datos identificativos (no aplica analíticas — no se realiza).

---

## 5. Quién accede a tus datos

- **Tú**: acceso total desde tu dispositivo.
- **Tu gestoría / asesoría**: si tú decides exportar y compartirles documentos.
- **Holded (Astrolab Apps S.L.)**: si conectas tu cuenta Holded, en los términos de su propia política de privacidad: https://www.holded.com/es/privacy.
- **Google LLC**: si activas el asistente IA Gemini o la copia en Drive, en los términos de la política de Google: https://policies.google.com/privacy.
- **El desarrollador (Jorge Miranda)**: **no accede a tus datos en ningún caso**. La app no envía nada a servidores propios.

---

## 6. Cuánto tiempo conservamos los datos

- Los datos permanecen en tu dispositivo mientras tengas la app instalada.
- Si desinstalas la app, los datos del dispositivo se eliminan automáticamente (excepto los respaldos que hayas subido a tu Drive — esos los gestionas tú).
- Las facturas y gastos: legalmente debes conservarlos 4 años (Ley General Tributaria 58/2003).

---

## 7. Tus derechos (RGPD)

Tienes derecho a:

1. **Acceder** a tus datos: están en tu dispositivo. Puedes exportarlos en CSV / PDF / XLSX desde Ajustes → Exportar.
2. **Rectificar** datos incorrectos: edita lo que quieras desde la app.
3. **Suprimir** tus datos: desinstala la app o usa "Ajustes → Borrar todos los datos".
4. **Limitar el tratamiento**: desactiva en Ajustes las funcionalidades que no quieras (asistente IA, lector de notificaciones, sincronización Drive, etc.).
5. **Portabilidad**: exporta tus datos en formato CSV / PDF cuando quieras.
6. **Oponerte** al tratamiento: desinstala la app.
7. **Presentar reclamación**: ante la Agencia Española de Protección de Datos (https://www.aepd.es).

Para ejercer estos derechos sobre los datos almacenados en tu dispositivo basta con que uses la app. Si necesitas ayuda, escríbenos a jorgemarimiranda@gmail.com.

---

## 8. Menores

Mint no está dirigido a menores de 18 años. El servicio asume que el usuario es un autónomo o representante de una empresa con plena capacidad legal.

---

## 9. Cambios en esta política

Si hacemos cambios sustanciales, te lo notificaremos en la propia app en el primer arranque tras la actualización y deberás aceptarlos de nuevo para continuar usando funcionalidades sujetas a la nueva política.

Las versiones anteriores se conservan en el repositorio público del proyecto.

---

## 10. Contacto

Para cualquier consulta:
- Email: jorgemarimiranda@gmail.com

---

*Esta política se actualiza periódicamente. La versión más reciente está siempre disponible en la URL pública oficial de la app.*
