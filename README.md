# Leonardo José do Nascimento Guimarães

[Homepage no servidor da universidade](http://www.lmcg.ufpe.br/~leo/)

[Homepage no PAGES do GitHub - Método 1 (repositorio qualquer com branch gh-pages)](https://leojnguimaraes.github.io/leo/)

[Homepage no PAGES do GitHub - Método 2 (repositorio qualquer no branch master)](https://leojnguimaraes.github.io/leo2/)

[Homepage no PAGES do GitHub - Método 3 (repositorio especial leojnguimaraes.github.io)](https://leojnguimaraes.github.io/)

---

# Git tips

## Para colocar um projeto novo no repositório:

> cd (vai para diretorio do projeto)  

> git init

> git status

> git add .

> git status

> git commit -m "Meu primeiro commit"

> git push -f origin main (na primeira vez de dar o push, indicar o branch, no caso 'main')

## Para atualizar um arquivo modificado:

> vi README.md ==> aqui eu modifico este arquivo

> git status

> git add README.md (ou, para adicionar todos os arquivos modificados: git add .)

> git status

> git commit -m "modifiquei novamente o README.md"

> git push 

## Para atualizar arquivos deletados:

> rm (lista de arquivos)

> git status

> git rm (lista de arquivos)

> git status

> git commit -m "deletei arquivos *.obj"

> git push 

## Outros comandos legais de para monitorar alterações:

> git show

> git log

## Voltar do tempo:

> git checkout (código do commit)

## Ainda tem os de controle de ramificações:

> git branch (opcionalmente com nome do branch a ser criado)

> git checkout (nome do branch)

> git merge

## Clonar um repositório:

> git clone (URL do repositório que vai ser clonado para minha máquina local)

> git pull (atualiza reposotório local a partir do repositório remoto)

<!---
- 👋 Hi, I’m @leojnguimaraes
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

leojnguimaraes/leojnguimaraes is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
