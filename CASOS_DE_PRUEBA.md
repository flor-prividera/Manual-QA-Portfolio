# Test Cases - Flow Web Platform

🌐 *Read this in [Español](#casos-de-prueba---plataforma-flow-web)*


| ID | Module | Title | Precondition | Steps | Expected Result | Priority | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **TC-001** | Search | Successful search by exact movie title | User is on the Home page | 1. Click search icon. 2. Type "The Matrix". 3. Press Enter. | Display movie details for "The Matrix". | High | Passed |
| **TC-002** | Search | Search with no results | User is on the Home page | 1. Click search icon. 2. Type "xyz123abc". 3. Press Enter. | Show "No results found" message. | Medium | Passed |
| **TC-003** | Filters | Apply "Action" genre filter | Content catalog is open | 1. Open filters menu. 2. Select "Action" genre. 3. Click Apply. | Display only action movies/series. | High | Passed |
| **TC-004** | Login | Login with invalid credentials | User is on Login page | 1. Enter invalid email. 2. Enter wrong password. 3. Click Login. | Show "Invalid credentials" error message. | High | Passed |
| **TC-005** | Playback | Play content as a guest user | User is not logged in | 1. Select a premium movie. 2. Click Play. | Prompt user to log in or subscribe. | High | Passed |
| **TC-006** | Responsive Design | 1. Resize the browser window to mobile dimensions. | The menu and movie posters should adjust correctly without being cut off. |  |  | Medium | Passed |




## Versión en español
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

