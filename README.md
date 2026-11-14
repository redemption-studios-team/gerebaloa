# gerebaloa

Web oficial de Gere (Portable Noise): https://gerebaloa.com

Sitio estático publicado con GitHub Pages desde `main` (raíz). No se edita a mano: se genera desde el repo `redemption-os` (plantilla `demos/plantilla-portafolio`) con:

```
python3 -I demos/plantilla-portafolio/generar.py --produccion <carpeta-de-salida>/ demos/plantilla-portafolio/conceptos/musica-gere.json
```

Luego se copia el contenido de la carpeta de salida (`index.html`, `img/`, `CNAME`, `robots.txt`, `sitemap.xml`) a la raíz de este repo.

Web por [Redemption Studios](https://getredemptionstudios.com).
