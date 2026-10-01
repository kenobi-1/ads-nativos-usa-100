# Biblioteca de 100 anuncios nativos

## Enlaces para compartir

- [Abrir la galería online](https://kenobi-1.github.io/ads-nativos-usa-100/)
- [Descargar el paquete completo](https://github.com/kenobi-1/ads-nativos-usa-100/releases/latest)
- [Índice de las 100 fichas](INDICE.md)

Instantánea de investigación del 1 de octubre de 2026. Las imágenes son referencias de los anunciantes; este repositorio no otorga derechos para reutilizar sus creativos.

Abrí **index.html** con tu navegador. Podés enviar esta carpeta completa a otra persona. Los estilos, datos y filtros están incluidos en el archivo HTML; las imágenes están guardadas en **imagenes/** para verlas sin conexión. Los enlaces a Meta y a las tiendas requieren internet.

## Qué contiene

- **index.html**: galería con filtros de anunciante y categoría, búsqueda, fuentes y adaptación de ideas.
- **anuncios.csv**: tabla UTF-8 compatible con Excel y Google Sheets. Algunos campos reciben un apóstrofo protector si podrían interpretarse como fórmula; JSON conserva el texto original.
- **catalogo.json**: datos normalizados y fuentes por referencia, sin el copy completo.
- **fichas/**: un Markdown por anuncio, con resumen propio, análisis visual, adaptación y evidencia.
- **GUIA_DE_ADAPTACION.md**: diez fórmulas de foto y copy largo.
- **AUDITORIA.md** y **evidencia.json**: alcance, selección y datos de respaldo.

## Criterios de selección

- Anuncio marcado activo al momento de la consulta registrada.
- Al menos 30 días de antigüedad entre el inicio publicado y la observación. **No demuestra entrega continua durante esos 30 días**.
- Página anunciante con **más de 200 anuncios activos globales** según la fuente registrada. El signo ≈ indica conteos aproximados mostrados por Meta. Cada fila conserva el conteo y su evidencia; los valores pueden cambiar después de la observación. No se agregaron conteos de distintas páginas por compartir una tienda.
- Consulta orientada a Estados Unidos, enlazada en cada ficha.
- Imagen nativa con copy largo, revisada y aprobada por el equipo de selección: fotos, testimonios o piezas editoriales que encajan en el feed. Se excluyen videos.
- IDs de anuncios sin duplicados. Una variante DCO está indicada como tal: la fecha es la del registro, no necesariamente la de esa combinación de imagen y texto.

La permanencia y el volumen son señales de investigación. **No prueban ROAS, conversiones, presupuesto, rentabilidad ni la veracidad de los claims.** El conteo de palabras corresponde al copy original observado; la ficha muestra un extracto breve y un resumen.

## Cómo replicar la idea

Usá las secciones «Por qué es nativo» e «Idea para adaptar» para reconstruir el mecanismo con tu marca. Creá tus propias imágenes, usá testimonios auténticos y verificá cualquier afirmación de producto antes de publicarla. El objetivo es adaptar la estructura, el ángulo y la forma de presentar el problema.

## Páginas anunciantes incluidas

El campo histórico `brand` del CSV/JSON representa **el nombre de la página emisora**, no una certificación de propiedad de marca. `destination_domain` indica el dominio del enlace observado. Algunas páginas son editoriales o personajes publicitarios. No se verificó su identidad ni su relación societaria con las tiendas.

- Anna Rodriguez: 3 referencias
- Based Supplies: 2 referencias
- Caroline Moore: 1 referencias
- DearPerson.Co: 1 referencias
- Denture Care Tips: 1 referencias
- Dog Owners Support Group: 1 referencias
- Dr. Sarah Mitchell: 1 referencias
- Emma's Mom Hacks: 1 referencias
- Essential Health Finds: 5 referencias
- FLAIR Fútbol: 1 referencias
- Happy Mammoth: 3 referencias
- Heart & Soil: 1 referencias
- HoneyNoir: 2 referencias
- Jacob Nash: 2 referencias
- Libra Cases: 1 referencias
- Mama Bear Oasis: 1 referencias
- NatPat: 1 referencias
- NativePath: 1 referencias
- One Compress: 1 referencias
- Onecompress: 3 referencias
- PAP MD: 1 referencias
- Radiancy: 23 referencias
- Raising Toddlers with Bec: 3 referencias
- Ready Nation USA: 29 referencias
- Rivanta Power: 1 referencias
- USA Ready Families: 10 referencias

## Verificación técnica del catálogo

El generador revisa cantidad, IDs únicos, campos obligatorios, fechas consistentes, antigüedad >=30, conteo global >200, actividad explícita y revisión aprobada. **El generador no hace scraping ni verifica por sí mismo las fuentes**: depende de la evidencia validada durante la selección. Las imágenes locales conservan su hash SHA-256; sus URLs de origen pueden vencer.
