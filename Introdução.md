Link para download do Git: https://git-scm.com/downloads

O Git Bash é um terminal estendido para otimizar o uso do Git.



## Comandos :desktop_computer: :

### **Alguns comandos importantes:**

- ### **git add**

  Quando criamos, modificamos ou excluímos um arquivo, essas alterações ocorrerão em nosso ambiente local. Então, precisamos usar esse comando para incluir as alterações de um arquivo em nosso próximo commit.

  Para adicionar apenas um arquivo:
  git add <arquivo>

  Para adicionar, de uma vez, todos os arquivos modificados:
  git add -A ou git add *

  *O comando git add não altera o repositório e as alterações não são salvas até usarmos o git commit.*

  

- ### git commit

  Este comando é como definir um ponto de verificação no processo de desenvolvimento, o qual você pode voltar mais tarde, se necessário.

  *git commit -m* "mensagem explicando a mudança no código".

  

- ### git push

  O comando git push envia e salva suas confirmações no repositório remoto.

  Após confirmar as alterações, a próxima coisa que você deseja fazer é enviar as alterações para o servidor remoto.

  

- ### git pull

  O comando git pull é usado para obter atualizações do repositório remoto, no qual estamos trabalhando ou queremos trabalhar e fazer as modificações.

  O comando de pull depende do referencial de onde ele foi feito, ou seja, um git pull feito da sua máquina vai puxar informações do repositório original para ela.

  Este comando é uma combinação de git fetch (baixa as alterações do repositório remoto, mas não mescla elas com o seu) e git merge (que mescla tudo junto), o que significa que, quando usamos o git pull, ele recebe as atualizações do repositório remoto (git fetch) e aplica imediatamente as alterações mais recentes no seu local (git merge).

  

- ### git clone

  comando para baixar o código-fonte existente de um repositório remoto.