# Comandos básicos Git

Aquí tienes una lista de los comandos básicos de Git que necesitas conocer para empezar a utilizarlo de manera efectiva:

### 1. **Configuración Inicial**
- `git config --global user.name "Tu Nombre"`: Configura tu nombre de usuario.
- `git config --global user.email "tuemail@example.com"`: Configura tu correo electrónico.

### 2. **Crear un Nuevo Repositorio**
- `git init`: Inicializa un nuevo repositorio de Git en el directorio actual.

### 3. **Clonar un Repositorio Existente**
- `git clone <URL>`: Clona un repositorio remoto a tu máquina local.

### 4. **Ver el Estado del Repositorio**
- `git status`: Muestra el estado actual del repositorio, incluyendo archivos modificados y no rastreados.

### 5. **Agregar Cambios al Staging Area**
- `git add <archivo>`: Agrega un archivo específico al área de staging.
- `git add .`: Agrega todos los archivos modificados y nuevos al área de staging.

### 6. **Confirmar Cambios (Commit)**
- `git commit -m "Mensaje descriptivo"`: Confirma los cambios en el área de staging con un mensaje descriptivo.

### 7. **Ver el Historial de Commits**
- `git log`: Muestra el historial de commits con detalles como autor, fecha y mensaje.
- `git log --oneline`: Muestra el historial de commits en una sola línea por commit.

### 8. **Trabajar con Ramas**
- `git branch`: Lista todas las ramas locales.
- `git branch <nombre-rama>`: Crea una nueva rama.
- `git checkout <nombre-rama>`: Cambia a una rama existente.
- `git checkout -b <nombre-rama>`: Crea una nueva rama y cambia a ella.
- `git merge <nombre-rama>`: Fusiona una rama con la rama actual.
- `git branch -d <nombre-rama>`: Elimina una rama local.

### 9. **Sincronizar con Repositorios Remotos**
- `git remote add <nombre> <URL>`: Añade un repositorio remoto.
- `git push <nombre-remoto> <nombre-rama>`: Sube los cambios locales a un repositorio remoto.
- `git pull <nombre-remoto> <nombre-rama>`: Descarga y fusiona cambios de un repositorio remoto.
- `git fetch <nombre-remoto>`: Descarga cambios de un repositorio remoto sin fusionarlos.

### 10. **Ver Diferencias**
- `git diff`: Muestra las diferencias entre el directorio de trabajo y el área de staging.
- `git diff --staged`: Muestra las diferencias entre el área de staging y el último commit.
- `git diff <commit1> <commit2>`: Muestra las diferencias entre dos commits.

### 11. **Deshacer Cambios**
- `git checkout -- <archivo>`: Deshace cambios en un archivo específico, volviendo a la versión del último commit.
- `git reset --hard <commit>`: Deshace todos los cambios desde el commit especificado.
- `git revert <commit>`: Crea un nuevo commit que deshace los cambios de un commit específico.

### 12. **Tags**
- `git tag <nombre-tag>`: Crea un tag para el commit actual.
- `git tag -a <nombre-tag> -m "Mensaje"`: Crea un tag anotado con un mensaje.
- `git tag`: Lista todos los tags.
- `git push <nombre-remoto> <nombre-tag>`: Sube un tag a un repositorio remoto.

### 13. **Ignorar Archivos**
- `.gitignore`: Archivo que lista los archivos y directorios que Git debe ignorar.

Estos comandos cubren la mayoría de las operaciones básicas que necesitarás para trabajar con Git. A medida que te familiarices más con la herramienta, podrás explorar comandos más avanzados y opciones adicionales.



[Volver](../README.md)