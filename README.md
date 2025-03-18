# Amigo Secreto

## Descripción

"Amigo Secreto" es una aplicación web interactiva que permite ingresar nombres de amigos y realizar un sorteo aleatorio para asignar un amigo secreto a cada participante. Este proyecto está desarrollado con HTML, CSS y JavaScript.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (ES6)

## Características

- Permite agregar nombres a la lista de participantes.
- Evita la duplicación de nombres.
- Posibilidad de eliminar nombres de la lista.
- Realiza el sorteo aleatorio de un amigo secreto.
- Interfaz amigable con diseño responsivo.

## Instalación y uso

1. Iniciar un repositorio Git en el proyecto:
   ```bash
   git init  # Iniciar el repo vacío
   git status  # Ver lo que está añadido
   git add .  # Agregar todo ingresado para ser confirmado
   git status  # Ver lo que se subió
   git commit -m "Primer commit"  # Comitear los archivos
   git log  # Ver los cambios realizados
   ```

2. Crear un repositorio en GitHub:
   - Ir a [GitHub](https://github.com/)
   - Clic en "New repository"
   - Ingresar el nombre del repo y una descripción
   - Elegir público o privado

3. Conectar el repositorio local con GitHub:
   ```bash
   git branch -M main
   git remote add origin https://github.com/LujoMontero/amigo-secreto.git
   git push -u origin main
   ```

4. Configurar autenticación con token en GitHub:
   - Ir a "Settings" en GitHub
   - Clic en "Developer settings"
   - Clic en "Personal access tokens"
   - Clic en "Tokens classic"
   - "Generate new token" → "Generate new token classic"
   - Agregar título, seleccionar "repo" y generar la clave
   - Copiar el token generado
   
5. Configurar las credenciales en Git:
   ```bash
   git config --global user.name "nombre_del_usuario"
   git config --global user.email "correo"
   git config --global user.password "tokengeneradoengithub"
   ```

6. Clonar el repositorio:
   ```bash
   git clone https://github.com/LujoMontero/amigo-secreto.git
   ```

7. Navegar al directorio del proyecto:
   ```bash
   cd amigo-secreto
   ```

8. Abrir el archivo `index.html` en un navegador web.

## Archivos principales

- `index.html`: Contiene la estructura del proyecto.
- `style.css`: Define los estilos y apariencia de la aplicación.
- `app.js`: Contiene la lógica del programa.

## Uso

1. Escribir un nombre en el campo de entrada y presionar "Añadir".
2. Se mostrará la lista de amigos agregados.
3. Para eliminar un nombre, presionar el botón ❌ junto al nombre.
4. Para sortear un amigo secreto, presionar el botón "Sortear amigo".
5. Se mostrará el resultado del sorteo en pantalla.

## Mejoras futuras

- Implementar almacenamiento local para guardar la lista de participantes.
- Agregar la posibilidad de enviar los resultados por correo electrónico.
- Crear una versión en forma de aplicación móvil.

## Contribución
Si deseas contribuir a este proyecto, puedes hacerlo mediante un `fork`, creando una nueva rama y enviando un `pull request` con tus mejoras.

## Autor

Desarrollado por **Luis Montero**. Puedes ver más de mis proyectos en [mi perfil de GitHub](https://github.com/LujoMontero).
