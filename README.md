# ES FORN Carta · V2 Supabase

Esta versión ya NO lleva la carta escrita dentro del HTML.

Al abrirse:
1. conecta con Supabase;
2. lee categorías públicas;
3. lee productos visibles;
4. lee variantes, extras, alérgenos y trazas;
5. construye la carta en el móvil.

La clave incluida es una Publishable Key de Supabase, diseñada para usarse en aplicaciones públicas.
La seguridad depende de los permisos y políticas de la base de datos, que ya están configurados.

La carta cliente:
- solo tiene acceso de lectura;
- no recibe internal_cost;
- no puede editar productos;
- no recibe productos ocultos.

Para publicar:
sustituye `index.html` en GitHub `es-forn-carta`, haz Commit y Vercel actualizará la misma URL.
