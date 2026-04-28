# Seguimiento SLA

Sitio estatico para publicar los dashboards de seguimiento SLA.

## Archivos publicados

- `index.html`: portada con acceso a los entregables.
- `seguimiento_sla_dashboard.html`: dashboard principal SLA.
- `seguimiento_sla_parada_reloj.html`: dashboard de parada de reloj.

## Actualizacion

Desde la carpeta principal `03 Seguimiento SLA`, ejecutar:

```powershell
.\actualizar_publicacion.ps1
```

Ese script regenera los dashboards y copia los HTML actualizados a esta carpeta.

Luego publicar los cambios con GitHub Desktop o con:

```powershell
git add .
git commit -m "Actualizar dashboards SLA"
git push
```
