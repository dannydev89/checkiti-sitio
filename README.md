# checkiti.com.mx

Sitio estático (GitHub Pages) del dominio del autor de Check-ITI.

- `instituciones.json`: directorio que lee la app móvil para saber el API de cada institución.
  Es público: solo nombres y URLs públicas. **Nunca** poner contraseñas, llaves, tokens ni datos
  personales. La app solo acepta `https://` de dominios permitidos fijos en su código.
- Campos: `id` (fijo, no cambiarlo), `name`, `api`, `active` (false = no aparece en el login),
  `demo` (opcional). La app ignora campos que no conoce; si cambia el formato, subir `version`.
- `CNAME`: dominio de GitHub Pages (`checkiti.com.mx`).
