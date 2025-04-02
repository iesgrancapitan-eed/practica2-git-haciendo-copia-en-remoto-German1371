Siguiendo con la práctica anterior **"Tarea 4.6b Flujo básico en Git. Local"**, vas a realizar una copia del repositorio local en GitHub. Para ello envía un pantallazo de cada apartado:

### Estudia el estado del repositorio local
- Todos los commits (hasta "mi imagen") y con tu directorio de trabajo limpio (sin ningún cambio por añadir al repositorio).
- Confirma que no estás en modo detached HEAD (el último commit debe reflejar `HEAD -> master`).
![alt text](image.png)
### Acepta esta tarea de GitHub
- Crearás un repositorio remoto **VACÍO**. No tiene ni `README.md`.
- Fíjate en las sugerencias de GitHub. Como partes de un repositorio local ya creado, sigue las siguientes instrucciones que te sugiere GitHub... **PERO RECUERDA** que tu rama **NO TIENE POR QUÉ** ser la indicada.
![alt text](image-1.png)
### Configurar el repositorio remoto desde la línea de comandos
Ejecuta los siguientes comandos:
```bash
git remote add origin https://github.com/iesgrancapitan-eed/practica2-git-haciendo-copia-en-remoto-lmagarin.git
git branch -M main
git push -u origin main
```
![alt text](image-2.png)
### Trabaja en local y sincroniza con el remoto
- En local (no debes trabajar en el remoto) y siempre desde **Git Bash**, añade el fichero `README.md` con estas instrucciones y sus pantallazos.
- Sincroniza tus cambios con el repositorio remoto usando:
```bash
git push
```
![alt text](image-3.png)