---
id: pr1
title: Primer pull request de prueba
---

Para poder crear tu primer documento en Docusaurus es necesario que el ID presente en el siguiente archivo coincida con el nombre del archivo ubicado en la carpeta de docs cuya ubicación se encuentra en:

```sh
../website/
```

El nombre del archivo anterior debe de encontrarse en siteConfig.js, tal y como se muestra a continuación: 

```sh
  headerLinks: [
    {doc: 'pr1', label: 'Docs'},
    {page: 'help', label: 'Help'},
    {blog: true, label: 'Blog'},
  ]
```

Para poder acceder al document creado, la liga a acceder se muestra a continuación: 
```sh
http://localhost:3000/docs/doc9
```