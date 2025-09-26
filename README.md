# THM — Offensive Security: Intro

**Reporte del laboratorio:** enumeración y explotación de `fakebank.thm`  
**Herramientas:** gobuster  
**Autor:** Alicia Blanco Fernández

## Resumen
En este laboratorio se identificó un directorio `/bank-transfer` que permitía realizar transferencias sin autenticación. Se documenta el proceso de descubrimiento, pruebas y recomendaciones de mitigación.

## Estructura del repo
- `report.md` — Reporte completo (pasos, capturas, evidencias).
- `images/` — Capturas del proceso.
- `LICENSE` — Licencia del proyecto.

## Cómo reproducir (resumen)
1. `gobuster dir -u http://fakebank.thm -w wordlist.txt`
2. Acceder a `/bank-transfer` y verificar parámetros de transferencia.

## Conclusiones y mitigaciones
- Falta control de acceso en endpoints sensibles.
- Recomendaciones: autenticación, validación de input, logging.

---

Si quieres ver más reportes o contactar: s0mbrr4@gmail.com • https://www.linkedin.com/in/alicia-blanco-fernandez-783808378
