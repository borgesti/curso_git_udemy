Curso da Udemy de Git e GitHub do básico ao avançado.

Matheus Battisti.


Crie um novo repositório na linha de comando. (Create a new repository on the command line)

echo "# curso_git_udemy" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/borgesti/curso_git_udemy.git
git push -u origin main