# Semana14
Activdad, 3° laboratorio, Programacion 2

# Tema: Git
## Materia: Programación 2

**Oscar Eliseo Torres Vásquez**

---

### Comandos de Git

#### 1. Configuración
- `git config --global user.name "Tu Nombre"`: Configura el nombre de usuario globalmente.
- `git config --global user.email "tuemail@dominio.com"`: Configura el correo electrónico globalmente.
- `git config --list`: Muestra las configuraciones actuales.

#### 2. Inicialización y clonado
- `git init`: Inicializa un repositorio Git en el directorio actual.
- `git clone <url-del-repo>`: Clona un repositorio remoto a tu máquina local.

#### 3. Gestión de archivos
- `git add <archivo>`: Añade un archivo al área de preparación (staging).
- `git add .`: Añade todos los archivos al área de preparación.
- `git rm <archivo>`: Elimina un archivo del repositorio.
- `git mv <archivo-origen> <archivo-destino>`: Mueve o renombra un archivo.

#### 4. Comprobación del estado
- `git status`: Muestra el estado actual de los archivos.
- `git diff`: Muestra las diferencias entre el área de trabajo y la preparación.
  
#### 5. Confirmación de cambios
- `git commit -m "Mensaje del commit"`: Confirma los cambios en el repositorio.
- `git commit -a -m "Mensaje"`: Añade y confirma todos los archivos modificados.
  
#### 6. Gestión de ramas
- `git branch`: Muestra todas las ramas del repositorio.
- `git branch <nombre-rama>`: Crea una nueva rama.
- `git checkout <nombre-rama>`: Cambia a la rama especificada.
- `git merge <nombre-rama>`: Fusiona la rama especificada con la actual.
- `git branch -d <nombre-rama>`: Elimina una rama local.
  
#### 7. Actualización y sincronización
- `git pull`: Trae los cambios del repositorio remoto y los fusiona con tu rama actual.
- `git push`: Envía los cambios confirmados al repositorio remoto.

#### 8. Historial de cambios
- `git log`: Muestra el historial de commits.
- `git log --oneline`: Muestra el historial de commits en una sola línea por cada uno.
- `git log --graph`: Muestra el historial de commits en forma de gráfico.

#### 9. Deshacer cambios
- `git reset <archivo>`: Elimina un archivo del área de preparación.
- `git reset --hard <commit>`: Restablece el área de trabajo al commit especificado.
- `git checkout -- <archivo>`: Restaura un archivo al último commit.

---

