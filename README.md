# NewByte Unlimited — Landing page

Landing page institucional de **NewByte Unlimited (NBU)**, una empresa ficticia de desarrollo de software creada como parte de un proyecto educativo de la **Tecnicatura en Desarrollo de Software**.

> [!IMPORTANT]
> NewByte Unlimited no es una empresa comercial real. La marca, los servicios, los perfiles profesionales y los datos presentados en este sitio fueron creados con fines académicos y demostrativos.

## Sobre el proyecto

NBU representa al equipo formado por:

- Nahuel Pedraza
- Benjamín Basiluk
- Ulises Sosa

El proyecto académico busca simular un proceso profesional completo: entrevistar a un cliente, relevar sus necesidades, analizar requisitos, diseñar una solución, implementarla y validarla mediante pruebas y devoluciones periódicas.

Como caso de estudio, el equipo trabaja con una persona de la institución **El Nacional** en el análisis y desarrollo de una aplicación de escritorio. La solución prevista utiliza C# y .NET, Windows Forms para la interfaz y SQLite para la persistencia local.

La landing presenta la identidad ficticia del estudio, sus capacidades, metodología de trabajo, integrantes y el proyecto educativo actualmente en desarrollo.

## Características de la web

- Diseño responsive para computadoras, tablets y teléfonos.
- Identidad visual basada en el logo original de NBU.
- Secciones de servicios, proceso, proyecto, equipo y contacto.
- Perfiles individuales con enlaces a GitHub.
- Animaciones de entrada y microinteracciones.
- Indicador de progreso de lectura.
- Compatibilidad con la preferencia de accesibilidad `prefers-reduced-motion`.
- Contacto mediante redacción web de Gmail y copia del teléfono al portapapeles.

## Tecnologías

La página está desarrollada sin frameworks ni proceso de compilación:

- HTML5
- CSS3
- JavaScript
- Google Fonts

## Estructura

```text
newbyte-unlimited-web/
├── imagenes/
│   ├── logo.png
│   ├── favicon.svg
│   ├── ulises.png
│   ├── nahuel.png
│   └── benjamin.png
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Ejecutar localmente

No requiere instalación de dependencias. Se puede abrir `index.html` directamente en un navegador o iniciar un servidor estático desde la carpeta del proyecto:

```bash
python3 -m http.server 8000
```

Luego visitar [http://localhost:8000](http://localhost:8000).

## Aviso

Este repositorio forma parte de una actividad académica. Aunque utiliza nombres y fotografías de los integrantes reales del equipo, la empresa, su trayectoria, sus servicios y las descripciones profesionales publicadas en la landing son ficticios.
