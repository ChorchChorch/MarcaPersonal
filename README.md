# MarcaPersonal
Con el tiempo ir dandome a conocer y aumentar la visibilidad
- marca personal y CV
- proyectos y curiosidades

Algo de Vibe Coding, guia para el prompt
Usar estructuras de markdown 


---

```markdown
# Documentación y Contexto

Este documento describe los requisitos funcionales, técnicos y visuales para el desarrollo de una aplicación web.
Está diseñado para facilitar la comprensión del pedido y asegurar una implementación eficiente y alineada con buenas prácticas.

---

## Objetivo del Proyecto

- **Propósito general**: Quiero una app que [describí brevemente qué debe hacer].
- **Solución esperada**: La solución debe [mencionar qué problema resuelve o qué valor aporta].
- **Lógica del caso**: Explicá brevemente el flujo o comportamiento esperado del usuario.

Ejemplo:
> Quiero una app que permita subir fotos, clasificarlas por etiquetas y visualizarlas en una galería accesible.
> La solución debe ser usable por personas sin conocimientos técnicos y funcionar en dispositivos móviles.
> La lógica incluye carga de archivos, asignación de etiquetas y visualización filtrada.

---

## Funcionalidades Clave

Listá las acciones que el usuario podrá realizar:

- Subir archivos
- Ver galería
- Buscar por etiqueta
- Descargar imágenes
- [Agregar otras funciones específicas]

---

## Guía de Buenas Prácticas

- Priorizar siempre soluciones simples. Mantener el código limpio, entendible y jerárquicamente organizado.  
- Iterar sobre código existente en lugar de crear desde cero, siempre que sea posible.  
- Evitar duplicación de código; reutilizar funciones o componentes similares.  
- Realizar solo los cambios solicitados o aquellos con plena confianza técnica.  
- Utilizar tabulación consistente para formatear el código correctamente.  
- Incluir comentarios explicativos en cada sección relevante del código.

---

## Stack Tecnológico

- La app deberá estar realizada con la versión **8 de [especificar tecnología]**.  
- Evitar el uso de [lenguaje o librería no deseada].  
- Tipo de aplicación: [Web estática / Web dinámica / Con backend].  
- Framework o enfoque preferido:
  - HTML/CSS/JS puro
  - React con Firebase
  - WordPress con plugin personalizado

> Generar el código completo en HTML/CSS/JS, listo para copiar en un archivo `.html`.
> Usar comentarios para explicar cada sección.
> Evitar dependencias externas innecesarias.

---

## Diseño Visual

Colores, estilo e inspiración visual deseada:

- Estilo minimalista, similar a Notion  
- Fondo blanco, tipografía clara y legible  
- Diseño responsivo para móviles  
- [Agregar preferencias de íconos, espaciado, animaciones, etc.]

---

## Extras opcionales (si aplica)

- Idioma principal: Español  
- Accesibilidad: Contraste alto, navegación por teclado, compatibilidad con lectores de pantalla  
- Posibles extensiones futuras: login, perfiles, exportación de datos, etc.  
```

---


## Y si toca algo mas profesional y no un MPV , recordar 
- escribir pruebas diferentes entre testing y produccion. 
- ante cambios de codigo reiniciar todas las isntancias para no tener codigo viejo mezclado


# (design system) para tus proyectos web, con componentes reutilizables y escalables.

```markdown

# Diseño visual detallado

Describí con precisión el estilo gráfico deseado. 
Esta sección influye directamente en la calidad del CSS generado.

### Estilo general
- Minimalista / Neomorfismo / Brutalismo / Flat / Material Design / Retro / Futurista
- Inspiración visual: [sitios, apps o marcas que te gusten]
- Sensación buscada: profesional, amigable, lúdico, técnico, accesible, etc.
- Importante: Asegurate de que el diseño sea responsivo y accesible. Usá comentarios explicativos. 

### Paleta de colores
- Color principal: `#1E90FF` (azul vibrante)
- Color secundario: `#F5F5F5` (gris claro)
- Color de acento: `#FF4081` (rosa fuerte)
- Fondo: claro / oscuro / degradado / imagen
- Contraste: alto para accesibilidad / suave para estética agradable

### Tipografía
- Fuente principal: `Inter`, `Roboto`, `Open Sans`, etc.
- Jerarquía: títulos grandes, subtítulos medianos, cuerpo legible
- Espaciado: interlineado generoso, márgenes amplios
- Accesibilidad: evitar fuentes decorativas difíciles de leer

### Layout y estructura
- Diseño responsivo: adaptable a móvil, tablet y escritorio
- Grid system: 12 columnas / flexbox / CSS Grid.
- Evitá librerías externas como Bootstrap, salvo que se indique lo contrario
- Navegación: barra superior fija / lateral / hamburguesa móvil
- Footer: con enlaces, redes sociales, contacto

### Componentes visuales
- Botones: estilo, hover, tamaño, íconos
- Tarjetas: para mostrar contenido visual o textual
- Formularios: campos accesibles, etiquetas claras
- Animaciones: transiciones suaves, efectos al hacer scroll o hover

### Accesibilidad visual
- Contraste mínimo AA/AAA según [WCAG](https://www.w3.org/WAI/WCAG21/quickref/)
- Navegación por teclado
- Indicadores visuales de foco
- Alternativas textuales para íconos e imágenes

### Buenas prácticas CSS
- Usar variables CSS (`:root`) para colores y fuentes
- Agrupar estilos por componente o sección
- Evitar estilos inline
- Minimizar uso de `!important`
- Comentar bloques clave para facilitar mantenimiento
- Generá el CSS completo con variables, clases reutilizables y estructura modular.

```

