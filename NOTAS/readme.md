# Funcionalidades de MPV RECORDATORIOS y NOTAS

## 1. Gestión de trámites  
- Agregar un trámite con:
  - Nombre (obligatorio)  
  - Detalle o descripción (multilínea)  
  - Enlace opcional  
  - Fecha de vencimiento, precargada al día siguiente por defecto  
- Editar un trámite existente: recarga el formulario con sus datos  
- Eliminar un trámite con confirmación
- **BUG** a corregir, si estas aditando la nota y le das borrar a la nota se queda colgado 

## 2. Persistencia offline  
- Almacenamiento local con localStorage  
- Los datos sobreviven al cerrar o recargar el navegador  
- Sin dependencias externas ni frameworks
- Exportacion e importacion de todas las notas juntas en JSON  

## 3. Visualización y organización  
- Lista de trámites ordenada por fecha de vencimiento !!!
- Destacar como “urgente” si faltan ≤ 2 días para el vencimiento !!!
- Tarjetas con diseño moderno, sombras y esquinas redondeadas  
 - Detalle expandido multilínea y preformateado (white-space: pre-wrap)  
- Enlace al trámite abre en nueva pestaña . **BUG** el link debe comenzar con http.....

## 4. Navegación rápida  
- Botón “Agends” en el header que desplaza suavemente hasta la lista  

## 5. Copiar al portapapeles  
- Botón único que genera un texto estructurado de todos los trámites  
- Soporta Clipboard API y fallback con `execCommand('copy')`  

## 6. Notificaciones locales  
- Solicita permiso al iniciar  
- Cada 10 segundos revisa los trámites que venzan en 2 días  
- Muestra notificación push con título, cuerpo y emoji cuando aplica  
- Evita duplicados gracias a un conjunto de índices notificados
- Mejoras pendientes: que la notificacion funcione en segundo plano y que funcione en horarios nornales, no a ls 2 AM  

## 7. UX y estilo  
- Cabecera con degradado y sombra  
- Formulario glassmorphism (fondo semitransparente + blur)  
- Inputs y botones con transiciones, sombras y efectos hover  
- Animaciones de entrada (`fadeIn`) y elevación al pasar el dedo por tarjetas  
- Totalmente responsive para Android y funcionamiento offline  
