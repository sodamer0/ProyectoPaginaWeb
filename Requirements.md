Plan de Desarrollo - Proyecto HTML5 y CSS
Información del Proyecto
Fecha límite de entrega: 28 de abril de 2025
Modalidad: Entrega por aula virtual
Puntuación total: 10 puntos
Presentación oral: 5 minutos + turno de preguntas
Objetivo
Desarrollar un sitio web de al menos 3 páginas HTML interconectadas, aplicando conocimientos de HTML5 y
CSS3 de forma semántica y estructurada.
Estructura de Archivos Recomendada
FASE 1: Planificación (Días 1-2)
1.1. Elegir Temática
Opciones sugeridas:
• Portfolio personal
• Sitio de recetas de cocina
• Blog de viajes
• Página de un hobby (fotografía, música, deportes)
• Sitio educativo sobre un tema de interés
• Página de negocio ficticio
Acción: Decidir temática y anotar en el diario de trabajo.
apellido1_apellido2_nombre/
│
├── index.html
├── pagina2.html
├── pagina3.html
│
├── css/
│ ├── styles.css
│ └── estilos-extras.css (opcional)
│
├── img/
│ ├── imagen1.jpg
│ ├── imagen2.png
│ └── ...
│
├── diario_trabajo.pdf
│
└── README.txt (opcional, con instrucciones)

1.2. Diseñar Estructura de Páginas
Definir qué contendrá cada página:
Página 1 (index.html): Página principal/inicio
• Header con título y navegación
• Sección de bienvenida
• Contenido destacado
• Footer con información de contacto
Página 2: Contenido secundario
• Galería de imágenes
• Información detallada
• Tabla con datos
Página 3: Formulario de contacto
• Formulario funcional
• Información adicional
1.3. Crear Wireframes/Bocetos
Dibujar a mano o digitalmente la estructura visual de cada página.
FASE 2: Desarrollo HTML (Días 3-5)
2.1. Estructura Base de Cada Página
2.2. Elementos HTML Obligatorios a Incluir
✓ Estructura semántica:
html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Descripción de la página">
<meta name="keywords" content="palabras, clave, relevantes">
<meta name="author" content="Tu Nombre">
<title>Título de la Página</title>
<link rel="stylesheet" href="css/styles.css">
</head>
<body>
<!-- Contenido aquí -->
</body>
</html>

• <header> - Cabecera de la página
• <nav> - Menú de navegación
• <section> - Secciones de contenido
• <article> - Contenido independiente (opcional)
• <aside> - Contenido lateral (opcional)
• <footer> - Pie de página
✓ Encabezados: <h1> a <h6> (usar jerárquicamente)
✓ Texto:
• <p> - Párrafos
• <ul> y <ol> - Listas
• <li> - Elementos de lista
✓ Multimedia:
• <img src="..." alt="descripción"> - Imágenes con texto alternativo
✓ Enlaces:
• <a href="pagina2.html">Texto del enlace</a> - Enlaces internos
• <a href="https://..." target="_blank">Enlace externo</a> - Enlaces externos
✓ Tabla:
✓ Formulario:
html
<table>
<thead>
<tr>
<th>Encabezado 1</th>
<th>Encabezado 2</th>
</tr>
</thead>
<tbody>
<tr>
<td>Dato 1</td>
<td>Dato 2</td>
</tr>
</tbody>
</table>

2.3. Comentarios en el Código
Añadir comentarios explicativos:
FASE 3: Desarrollo CSS (Días 6-8)
3.1. Crear Hoja de Estilos Externa
Archivo: css/styles.css
html
<form action="#" method="post">
<label for="nombre">Nombre:</label>
<input type="text" id="nombre" name="nombre" required>
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>
<label for="mensaje">Mensaje:</label>
<textarea id="mensaje" name="mensaje" rows="5"></textarea>
<button type="submit">Enviar</button>
</form>
html
<!-- Inicio de la navegación principal -->
<nav>
<!-- Menú de navegación -->
</nav>
<!-- Fin de la navegación -->

css
/* ===========================
RESET Y ESTILOS GENERALES
=========================== */
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}
body {
font-family: Arial, sans-serif;
line-height: 1.6;
color: #333;
}
/* ===========================
TIPOGRAFÍA
=========================== */
h1 {
font-size: 2.5rem;
color: #2c3e50;
}
h2 {
font-size: 2rem;
color: #34495e;
}
p {
font-size: 1rem;
margin-bottom: 1rem;
}
/* ===========================
MODELO DE CAJA
=========================== */
.contenedor {
max-width: 1200px;
margin: 0 auto;
padding: 20px;
}
/* ===========================
NAVEGACIÓN
=========================== */
nav {
background-color: #2c3e50;
padding: 1rem;
}
nav ul {
list-style: none;

3.2. Elementos CSS Obligatorios
✓ Estilos de texto:
• color , font-family , font-size , font-weight
• text-align , text-decoration , line-height
✓ Modelo de caja:
• margin (márgenes externos)
• padding (relleno interno)
• border (bordes)
• width , height
✓ Colores y fondos:
• background-color , background-image
• Colores en formato hexadecimal, RGB o nombres
✓ Posicionamiento:
• display (block, inline, flex, grid)
• position (relative, absolute)
• float (opcional)
3.3. Estilos a Nivel de Página (en <head> )
FASE 4: Refinamiento (Días 9-10)
4.1. Checklist de Verificación
display: flex;
justify-content: center;
}
nav a {
color: white;
text-decoration: none;
padding: 0.5rem 1rem;
}
nav a:hover {
background-color: #34495e;
}
html
<style>
/* Estilos específicos solo para esta página */
.destacado {
background-color: #f39c12;
padding: 10px;
}
</style>

 Las 3 páginas están conectadas correctamente
Todos los enlaces funcionan
Todas las imágenes tienen atributo alt
El formulario tiene todos los elementos requeridos
La navegación es consistente en todas las páginas
El diseño es coherente y legible
El código está correctamente indentado
Hay comentarios explicativos en el código
Los archivos están bien organizados en carpetas
4.2. Validación del Código
Usar validadores online:
• HTML: https://validator.w3.org/
• CSS: https://jigsaw.w3.org/css-validator/
4.3. Pruebas de Usabilidad
• Navegar por todas las páginas
• Probar todos los enlaces
• Verificar que las imágenes se cargan correctamente
• Comprobar la legibilidad del texto
FASE 5: Diario de Trabajo (Días 11-12)
Estructura del Diario (PDF)
1. Portada
• Título del proyecto
• Nombre del autor
• Fecha
• Módulo/Curso
2. Descripción del Proyecto
• Temática elegida y justificación
• Objetivos específicos
• Público objetivo
3. Decisiones de Diseño
• Paleta de colores elegida y por qué
• Tipografías seleccionadas
• Estructura de navegación
• Distribución del contenido
4. Proceso de Desarrollo

• Fases seguidas
• Herramientas utilizadas (editor de código, navegador, etc.)
• Tiempo dedicado a cada fase
5. Dificultades y Soluciones
• Problemas encontrados
• Cómo se resolvieron
• Aprendizajes obtenidos
6. Recursos Utilizados
• Páginas web consultadas
• Tutoriales seguidos
• Fuentes de imágenes (con licencia adecuada)
• Referencias de código (si se usaron)
7. Conclusiones
• Valoración personal del proyecto
• Aspectos que se podrían mejorar
• Conocimientos adquiridos
FASE 6: Preparación de la Presentación (Días 13-14)
Estructura de la Presentación (5 minutos)
1. Introducción (30 segundos)
• Presentación personal
• Temática del proyecto
2. Demostración (3 minutos)
• Navegación por las páginas
• Mostrar características principales
• Destacar elementos HTML y CSS implementados
3. Aspectos Técnicos (1 minuto)
• Estructura del código
• Decisiones de diseño
• Desafíos superados
4. Conclusiones (30 segundos)
• Aprendizajes
• Posibles mejoras futuras
Consejos para la Defensa

• Practicar varias veces cronometrando el tiempo
• Preparar respuestas a preguntas técnicas comunes:
• ¿Por qué elegiste esta estructura?
• ¿Qué dificultades tuviste con CSS?
• ¿Cómo organizaste tu código?
• Usar vocabulario técnico apropiado
• Mantener la calma y ser claro en las respuestas
Desglose de Puntuación
Criterio
Puntos
Cómo Maximizar
Estructura y semántica HTML
2
Usar etiquetas semánticas, estructura clara, nomenclatura coherente
Aplicación de CSS
2
Estilos bien organizados, uso del modelo de caja, clases e IDs bien definidos
Diseño y usabilidad
1
Diseño coherente, buena legibilidad, jerarquía visual clara
Interactividad y navegación
1
Enlaces funcionando, navegación intuitiva, formulario completo
Calidad del código
1
Código limpio, bien indentado, con comentarios
Diario de trabajo
1.5
Documentación completa, reflexión profunda, justificaciones claras
Exposición y defensa
1.5
Discurso coherente, dominio técnico, gestión del tiempo, respuestas precisas
Puntos Críticos a Evitar
•
No copiar código sin referenciar la fuente
•
No usar estilos inline excesivamente (solo externos y a nivel de página)
•
No olvidar el atributo alt en las imágenes
•
No entregar sin validar el código HTML y CSS
•
No superar los 5 minutos en la presentación
•
No dejar la entrega para el último día
Checklist Final de Entrega
Carpeta nombrada correctamente: apellido1_apellido2_nombre
Al menos 3 páginas HTML
Hoja de estilos CSS externa
Carpeta de imágenes organizada
Diario de trabajo en PDF incluido
Código validado (HTML y CSS)
Todos los archivos funcionando correctamente
Carpeta comprimida (.zip o .rar)
Subida al aula virtual antes del 28.04.2025
Presentación preparada y ensayada
Cronograma Sugerido (14 días)

Días
Fase
Actividad
1-2
Planificación
Elegir tema, diseñar estructura, crear bocetos
3-5
HTML
Desarrollar las 3 páginas con todos los elementos
6-8
CSS
Crear estilos, aplicar diseño, modelo de caja
9-10
Refinamiento
Validar código, corregir errores, mejorar diseño
11-12
Documentación
Escribir y completar el diario de trabajo
13-14
Presentación
Preparar y ensayar la defensa oral
Recursos Útiles
Validadores:
• HTML Validator: https://validator.w3.org/
• CSS Validator: https://jigsaw.w3.org/css-validator/
Referencias:
• MDN Web Docs: https://developer.mozilla.org/es/
• W3Schools: https://www.w3schools.com/
Imágenes libres:
• Unsplash: https://unsplash.com/
• Pexels: https://www.pexels.com/
• Pixabay: https://pixabay.com/
Paletas de colores:
• Coolors: https://coolors.co/
• Adobe Color: https://color.adobe.com/
Resumen Ejecutivo
Este proyecto requiere crear un sitio web de 3 páginas con HTML5 y CSS3, demostrando dominio de estructura
semántica, estilos, navegación y formularios. El éxito depende de una buena planificación, código limpio y bien
documentado, y una presentación profesional. Sigue este plan paso a paso y maximizarás tu puntuación.
¡Éxito en tu proyecto!
<img width="668" height="944" alt="imagen" src="https://github.com/user-attachments/assets/983feb74-5912-409a-a87d-bf42bebde495" />
