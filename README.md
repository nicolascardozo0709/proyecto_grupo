proyecto_grupo

Laboratorio 1 de Principios de Desarrollo de Software

Integrantes
Nicolás Cardozo
Samuel Correa
Nicolás Espinosa
Repositorio

https://github.com/nicolascardozo0709/proyecto_grupo

Qué se hizo

Cada uno trabajó en su propia rama, agregó su nombre a la lista de integrantes en index.html, y subió su rama a GitHub. Después cada uno abrió su pull request y otro compañero lo revisó y aprobó. Al mergear el segundo y tercer PR salió un conflicto porque los tres estábamos editando la misma parte del archivo (la lista <ul>), así que tocó resolverlo a mano dejando los tres nombres.

Comandos que usamos

git clone - para bajar el repo a la máquina de cada uno
git config --global user.name / user.email - configurar quién eres en los commits
gh auth login - autenticarse con GitHub desde la terminal
git checkout -b nombre-rama - crear la rama propia
git add . / git commit -m "mensaje" - preparar y guardar los cambios
git push -u origin nombre-rama - subir la rama por primera vez
git pull origin main - traer lo nuevo que ya está en main
git merge main - traer los cambios de main a la rama propia (aquí salió el conflicto)
git log --oneline --graph --all --decorate - ver el árbol de commits


Estructura

src/
docs/
tests/
index.html
README.md
