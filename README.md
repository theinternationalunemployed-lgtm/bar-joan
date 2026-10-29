# Bar Joan · web

Web estática (HTML + CSS + ~6 líneas de JS), misma plantilla que `../bodega-del-gotic`, con paleta verde mercado.
Sin proceso de compilación: se sube tal cual.

```
index.html        castellano (por defecto)
ca/index.html     català
en/index.html     English
aviso-legal.html, privacidad.html, cookies.html   (solo en castellano)
styles.css, favicon.svg, robots.txt, sitemap.xml
```

## Editar menú u horario
Cada idioma es un archivo: busca `EDITAR` / `EDIT` y cambia **los tres**.
El horario también está en `openingHoursSpecification` del `<head>` de cada uno (es lo que lee Google).

## De dónde salen los datos (consultados el 29/10/2026)
- Dirección, paradas 108–110, teléfono y horario: ficha del bar en [mercatsantacaterina.com](https://mercatsantacaterina.com/parada/bar-joan/).
  Otras webs dan horarios distintos, así que hay que confirmarlo.
- Desde 1985, menú de 16 € de lunes a viernes (con pan, bebida y postre), sábados a la carta y platos típicos: artículo del diario Ara del 16/09/2026.
- Instagram [@bar_joanbcn](https://www.instagram.com/bar_joanbcn/): confirmado (la bio remite al Mercat de Santa Caterina).

## Pendiente de pedir al cliente
- [ ] Confirmar horario, teléfono y precio del menú del día (16 €)
- [ ] ¿Aceptan reservas? (no se ha encontrado nada; por eso no hay sistema de reservas)
- [ ] Carta de desayunos y bocadillos con precios
- [ ] Precios de los sábados (a la carta)
- [ ] Bebidas con precios
- [ ] Fotos: portada y 6 para la galería → `img/` en WebP; foto 1200×630 → `img/og.jpg`
- [ ] Email de contacto
- [ ] Razón social y NIF (aviso legal y privacidad)
- [ ] ¿Dominio propio? Hoy las URL canónicas, el sitemap y los datos de Google apuntan a GitHub Pages:
      al tener dominio, sustituir `https://theinternationalunemployed-lgtm.github.io/bar-joan` en todos los archivos

## Publicar
Igual que `../bodega-del-gotic`: repositorio público en GitHub con GitHub Pages (rama `main`, carpeta raíz).
