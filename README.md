# Mi Expansión · App de mentoría CODE

Prototipo funcional de **Mi Expansión**, la aplicación web de Tiby Hernández para diagnosticar oportunidades de negocio y acompañar procesos de mentoría con la metodología **CODE** (Convertir, Ordenar, Digitalizar, Escalar).

> Estado: **demo / prototipo**. Los datos se guardan solo en el navegador de quien la abre (localStorage). Preguntas, puntuaciones, recomendaciones y actividades son contenido de ejemplo pendiente de aprobación (PRD 5.12).

## Cómo verla

- **En línea:** active GitHub Pages en *Settings → Pages → Branch: main / (root)*. La app queda en `https://<usuario>.github.io/<repositorio>/`.
- **En su computadora:** abra `index.html` con doble clic en cualquier navegador. No requiere instalación.

## Cuentas de prueba

Contraseña para todas: `demo1234`

| Correo | Rol | Qué muestra |
| --- | --- | --- |
| maria@demo.co | Participante | Dos mentorías (una activa, una finalizada) con entregables en todos los estados |
| carlos@demo.co | Participante | Diagnóstico enviado, esperando validación |
| laura@demo.co | Participante | Cuenta suspendida (acceso bloqueado) |
| tiby@miexpansion.co | Administradora | Panel completo de mentora |

También puede cambiar de rol con la barra **DEMO · Ver como** y volver a los datos iniciales con **Reiniciar demo**.

## Qué incluye

**Experiencia pública:** portada, introducción, cuestionario de 12 preguntas, resultados con mapa CODE, fortaleza, prioridades (con empates), tres acciones y salida a WhatsApp; pausa del diagnóstico y recuperación en el navegador (7 días intentos, 30 días resultados).

**Participante:** panel con progreso oficial y trabajo presentado por separado, ruta CODE por etapas, actividades con autoguardado y versiones, retroalimentación por respuesta, portafolio, diagnóstico inicial y final con comparación, varias mentorías, modo consulta, perfil y solicitud de eliminación.

**Administración:** panel, participantes e invitaciones, suspensión, programas y cohortes, validación y corrección de diagnósticos, diseñador de rutas con historial y avisos, revisión de entregables, biblioteca versionada, versionado de cuestionarios, estadísticas anónimas, editor del sitio y solicitudes de eliminación.

## Estructura

```
index.html              Página principal
assets/css/styles.css   Estilos (identidad visual Tiby Hernández)
assets/js/app.js        Lógica, datos de ejemplo y pantallas
docs/                   Notas de UX y presentación de pantallas
```

## Próximos pasos para producción

1. Backend y base de datos (por ejemplo Supabase o Firebase) para reemplazar localStorage.
2. Autenticación real y envío del correo de invitación.
3. Aprobación de los contenidos metodológicos (PRD 5.12).

---
© 2026 Tiby Hernández · Mi Expansión · Metodología CODE
