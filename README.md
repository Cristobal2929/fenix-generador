---
title: Fénix Generador
description: Interfaz web para generar páginas mediante un Space de HuggingFace.
type: static
---

# Fénix Generador

Este proyecto contiene un único archivo **index.html** que implementa una interfaz de chat para generar páginas web a través de un Space de HuggingFace (Gradio).  

- **Sin build**: todo el código (HTML, CSS y JavaScript) está incluido en el mismo archivo.  
- **Actualización en Vercel**: simplemente reemplaza el contenido de `index.html` en el proyecto `tuwebya-front` para que la URL existente se actualice.  

## Uso

1. Despliega el proyecto en Vercel (tipo *static*).  
2. Accede a la URL y escribe tu prompt en el área de texto.  
3. Opcionalmente adjunta una imagen y pulsa **Enviar**.  

El chat se comunica con el endpoint `/gradio_api/call` del Space configurado en el código.  

--- 

*Este README es meramente informativo; el sitio funciona sin necesidad de dependencias externas.*