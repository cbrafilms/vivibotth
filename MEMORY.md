# MEMORY.md - Long-Term Memory

## 1) Hechos Estables

### Identidad y rol
- Nombre del sub-agente: **VIVI BOTTH** ("Vivi" para los amigos).
- Rol principal: **Productora Ejecutiva de CBRA FILMS**.
- Estilo de trabajo: servicial, súper profesional, resolutiva y orientada a ayudar.

### Humano principal
- Nombre: **Cristóbal Braun**.
- Rol: Director, socio y productor de **CBRA FILMS** (Santiago de Chile).
- Sitio: https://www.cbrafilms.com

## 2) Decisiones
- Usar este workspace como base operativa de Vivi: `/home/cbra-films/.openclaw/workspace-vivi-botth`.
- Usar identidad Git local del repo para Vivi:
  - `user.name`: `Vivi Botth`
  - `user.email`: `vivibotth@gmail.com`
- Estandarizar rama principal del repo en **`main`**.
- Programar ejecución diaria de MercadoPúblico vía OpenClaw cron (`vivi-mercadopublico-diario`) a las 08:00 (America/Santiago) con reporte automático por Telegram.

## 3) Pendientes Activos
- Confirmar/registrar ruta exacta del directorio destino en Escritorio ThinkStation C30 para guardar carpetas y adjuntos de cada licitación.
- Ajustar filtros de relevancia (si aplica: rubro, organismo, monto, región, plazos) para optimizar el reporte diario.

## 4) Infra / Accesos Técnicos
- Repo remoto configurado: `git@github-vivi:cbrafilms/vivibotth.git`
- Rama principal actual: `main`
- SSH dedicada de Vivi creada y activa: `~/.ssh/id_ed25519_vivi`
- Cuenta Google de trabajo con acceso configurado en `gog`: `vivibotth@gmail.com` (gmail, drive, docs, sheets)

## 5) Lecciones / Reglas de Operación
- Mantener `MEMORY.md` como memoria curada (no volcar ruido diario).
- Registrar eventos diarios en `memory/YYYY-MM-DD.md` y subir a `MEMORY.md` solo lo que sea durable.
- Hacer commits claros y atómicos para cambios relevantes.

## 6) Última Actualización
- 2026-02-27
