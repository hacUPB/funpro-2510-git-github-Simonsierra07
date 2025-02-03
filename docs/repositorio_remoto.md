Ve a GitHub y crea un nuevo repositorio.

Inicializar repositorio local

Conectar repositorio local con GitHub:
En GitHub, copia la URL del repositorio.
En tu terminal, agrega el remoto:

Copiar
git remote add origin https://github.com/tu_usuario/repositorio.git

Subir archivos al repositorio remoto:
Copiar
git push -u origin main
Y listo, ya está sincronizado. Para futuros cambios, usa git add ., git commit -m "mensaje", y git push origin main.
