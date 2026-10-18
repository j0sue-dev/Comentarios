# Comentarios bíblicos para Infobase

Comentarios de dominio público (módulos SWORD de CrossWire) para la descarga
opcional de la app, organizados por idioma y autor:

    <idioma>/<autor>/<id>.json.xz

`catalogo.json` lista lo disponible (id, idioma, autor, título, archivo,
tamaño). Cada archivo es JSON en formato tabular comprimido con xz: una lista
de secciones {b: libro 1..66, c: capítulo, v: versículo, e: versículo final,
k: bloques}, con bloques ["p", texto] (referencias como [[ref:b:c:v:c2:v2]]),
["c", capítulo], ["o", texto, "1-2"] (esquema) y ["v", "3-5"].

Las traducciones al español son de Infobase.
