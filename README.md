# Lab de Conversaciones Difíciles — UP Company

Landing page para difundir el **Lab de Conversaciones Difíciles para Líderes** de UP Company y captar consultas de empresas interesadas. La experiencia está pensada para comunicar una propuesta de práctica intensiva para líderes, mandos medios y coordinadores.

## Vista general

La página incluye:

- Hero con propuesta de valor y llamadas a la acción hacia el formulario.
- Sección interactiva para conocer qué es el Lab, para quién está dirigido y qué se llevan los participantes.
- Resumen del formato: duración, tamaño de grupo, modalidad y facilitación.
- Formulario de contacto con validación de nombre, empresa y mail corporativo.
- CTA flotante contextual, animaciones de entrada y diseño adaptable a pantallas pequeñas.

## Tecnologías

- HTML5
- CSS3 (variables, media queries y animaciones)
- JavaScript nativo
- Google Fonts: Poppins y Sofia Sans

No requiere instalación de dependencias ni proceso de compilación.

## Ejecutar localmente

Cloná el repositorio y abrí `main.html` en tu navegador. Si preferís levantar un servidor local:

```bash
python3 -m http.server 8000
```

Después visitá [http://localhost:8000](http://localhost:8000).

## Estructura

```text
.
├── main.html  # Landing completa: estructura, estilos e interacciones
└── README.md  # Documentación del proyecto
```

## Comportamiento del formulario

El formulario valida los campos en el cliente y muestra una confirmación al completarlo correctamente. Actualmente **no envía ni persiste datos en un servicio externo**; para usarlo en producción debe conectarse a un endpoint, CRM o herramienta de formularios.

## Accesibilidad y experiencia

- Estados de foco visibles para controles interactivos.
- Respeta `prefers-reduced-motion` para reducir animaciones.
- Carrusel con pestañas, indicadores y controles anterior/siguiente.
- Diseño responsive para escritorio y dispositivos móviles.

## Contexto de la propuesta

El Lab se ofrece en modalidad presencial o virtual, con grupos de hasta 12 personas y una duración de medio día. La modalidad presencial toma como base Córdoba, Argentina.

---

UP Company — Consultora de formación y liderazgo.
