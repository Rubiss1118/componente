    TECNOLÓGICO NACIONAL DE MEXICO

     INSTITUTO TECNOLÓGICO DE OAXACA			

		 Departamento de Ingeniería en Sistemas Computacionales

		 Materia:PROGRAMACION WEB

		 “Componente visual  Enlace de repositorio de Github y/o GitHub Pages”

		 Profesor: Martinez Nieto Adelina

	  Equipo: 
		MORALES OSORIO RUBI ESMERALDA 
		JIMENEZ CASTILLEJOS FABIAN DE JESUS

	  Grupo:   VSI
	  Oaxaca de juarez  a 05 de julio de 2025.

   Nombre de la librería:
   # componente
Descripción: Componente interactivo que añade un ojo animado a campos de contraseña, proporcionando feedback visual intuitivo sobre la visibilidad de la contraseña. El ojo reacciona con diferentes emociones: contento al mostrar la contraseña, enojado y llorando al ocultarla, además de seguir el cursor del mouse para una experiencia más inmersiva.

# Qué problema resuelve?

Mejora la experiencia de usuario en formularios de contraseña
Proporciona feedback visual claro sobre el estado de visibilidad
Hace más atractivos e interactivos los campos de contraseña
Reduce la confusión sobre si la contraseña está visible u oculta

# Instalación
Método 1: Descarga directa

Descarga los archivos del repositorio
Incluye los archivos en tu proyecto:

html<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Página</title>
    <link rel="stylesheet" href="css/componente.css">
</head>
<body>
    <!-- Tu contenido aquí -->
    <script src="js/componente.js"></script>
</body>
</html>
Método 2: Clonar repositorio
bashgit clone https://github.com/Rubiss1118/componente.git
cd componente

# Funcionalidades incluidas

👁️ Seguimiento del mouse: Los ojos siguen el cursor por toda la página
😊 Estados emocionales:

Verde (contento) cuando la contraseña es visible
Rojo (enojado) cuando se oculta la contraseña
Azul (siguiendo) cuando rastrea el mouse


💧 Lágrimas animadas: Aparecen cuando se oculta la contraseña
👀 Parpadeo automático: Los ojos parpadean naturalmente cada 3 segundos
🤾 Animación de salto: El ojo "salta" enojado al ocultar la contraseña
📱 Responsive: Se adapta a diferentes tamaños de pantalla
# Personalización
Puedes modificar los colores y animaciones editando las variables CSS:
css/* Cambiar colores de estados */
.contenedor-ojo.contraseña-visible .globo-ocular {
    background: #27ae60; /* Verde para visible */
}

.contenedor-ojo.contraseña-oculta .globo-ocular {
    background: #e74c3c; /* Rojo para oculta */
}

.contenedor-ojo.mirando .globo-ocular {
    background: #3498db; /* Azul para siguiendo */
}
# Capturas de pantalla
# Vídeo de demostración

El video muestra:

Cómo el ojo sigue el cursor del mouse
Transición entre estados (visible/oculto)
Animaciones de parpadeo y salto
Efecto de lágrimas
Interactividad completa del componente

# GitHub Pages
Demo en vivo: 
