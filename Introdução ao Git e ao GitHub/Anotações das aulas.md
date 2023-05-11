# Anotações das aulas:

- CD = "change directory"
  - / = volta pra raiz
  - [nome da pasta] = entra na pasta
  - .. = volta um nível
- cls = limpa o terminal (CTRL + L no Git Bash)
- Tecla tab autocompleta o texto
- mkdir = "make directory" - mkdir nomedapasta = cria pasta
- echo texto > texto.txt = cria um arquivo com o "texto"
- del = deleta arquivos 
- rmdir nomediretório /S /Q = remove diretório

## Comandos do Git:

- git init = inicia o Git na pasta
- git config --global user.email e git config --global user.name = adiciona credenciais (recomendado: usar mesmas credenciais do GitHub)
- git add * = adiciona tudo, TUDO aaaa rs
- git add nomedoarquivo = adiciona o arquivo
- git commit -m "mensagem do commit" = commita
- git status = status do repositório, coisas a commitar, etc
- mv nomedoarquivo ./pasta/ = move para a pasta
- git remote add origin linkdorepositório = 1º passo pra mandar as coisas pro GitHub
- git branch -M main + git push -u origin main = manda pro git (pesquisar mais esse ponto, fiz como estava no GitHub, diferente da aula #medo)
- git clone linkdorepositório = clona repositório para o computador