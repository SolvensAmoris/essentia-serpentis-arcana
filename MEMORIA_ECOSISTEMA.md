# 🧙‍♂️ Ecosistema: Essentia Serpentis Arcana
## Estado de la Construcción: Fase 1 (MVP) Concluido

### 1. Arquitectura Actual
- **Frontend:** Monolito HTML5/CSS3 alojado en Vercel.
- **Identidad:** Firma de autoría "Solvens Amoris" con sigilo oculto (Easter Egg: 3 toques en la firma).
- **Embudo (Funnel):** Estructura de 2 fases (Evaluación $5 USD + High-Ticket videollamadas).
- **Rutas de Pago:** WhatsApp (Trigger: `/INICIAR_PACTO`) y PayPal (Marcador listo).

### 2. Checklist de Activación (Pendientes)
Para que el sistema sea 100% operativo, la administradora debe ejecutar:
- [ ] **PayPal:** Generar Payment Link y sustituir `#ENLACE_DE_PAYPAL_AQUI` en `index.html`.
- [ ] **Telemetría:** Sustituir `G-XXXXXXXXXX` (Google) y `TU_PIXEL_ID` (Meta) en `index.html`.
- [ ] **Assets:** Subir `og-image.jpg` a la carpeta `/assets/` para la previsualización social.
- [ ] **Bot de WhatsApp:** Configurar el autómata (ManyChat/Twilio) para responder al comando `/INICIAR_PACTO`.

### 3. Hoja de Ruta (Fases Futuras)
- **Fase 2 (Automatización de Entrega):** Integrar webhooks de PayPal a un sistema de envío automático de correos (Mailchimp/SendGrid) con el archivo PDF adjunto.
- **Fase 3 (Agente Nativo):** Sustituir el botón de WhatsApp por un Widget de IA que converse con el usuario dentro de la misma página web.
- **Fase 4 (Base de Datos):** Implementar Supabase para centralizar los leads, los diagnósticos entregados y el historial de pagos.

---
*Arquitectura de sistemas: Solvens Amoris*
*Última actualización: 01/07/2026*
