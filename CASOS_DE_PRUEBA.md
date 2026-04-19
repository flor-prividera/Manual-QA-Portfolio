# 📝 Casos de Prueba - Flow Web

En este documento se detallan los pasos para validar las funcionalidades principales de la plataforma.


| ID | Título | Pasos | Resultado Esperado | Prioridad |
|:---|:---|:---|:---|:---|
| CP001 | Búsqueda de contenido válido | 1. Entrar a Flow. <br> 2. Clic en buscador. <br> 3. Escribir "Matrix". | El sistema debe mostrar la película o serie "Matrix" en los resultados. | Alta |
| CP002 | Login con campos vacíos | 1. Ir a sección Login. <br> 2. Dejar campos vacíos. <br> 3. Clic en "Ingresar". | Debe aparecer un mensaje de error: "Por favor, completa tus datos". | Media |
| CP003 | Filtro por género | 1. Ir a Películas. <br> 2. Seleccionar filtro "Terror". | Solo deben visualizarse contenidos categorizados como Terror. | Baja |



| ID | Título | Pasos | Resultado Esperado | Prioridad |
|:---|:---|:---|:---|:---|
| CP004 | Recuperación de contraseña | 1. Ir a Login. <br> 2. Clic en "Olvidé mi contraseña". <br> 3. Ingresar mail válido. | El sistema debe confirmar el envío del mail de recuperación. | Alta |
| CP005 | Control Parental | 1. Entrar a un perfil de Niños. <br> 2. Intentar buscar contenido "Adultos". | El sistema no debe mostrar resultados o debe pedir un PIN de seguridad. | Crítica |
| CP006 | Responsive Design | 1. Achicar la ventana del navegador al tamaño de un celular. | El menú y los pósters de las pelis deben acomodarse sin cortarse. | Media |

