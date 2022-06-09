# Resumão sobre Git e GitHub :computer:

### Descrição

-  Baixar e instalar o Git no PC

- Configurar chave SHH

- Versionamento

  - Abrir Git bash na pasta local
  - git init (inicializador)
  - git config
    - --list (lista as configurações)
    - --global user.email " email" (adiociona o email, inserir o da conta do GitHub)
    - -- global user.name "nome" (adiociona o nome, inserir o mesmo do GitHub)
  - git add * (adiciona todos arquivos que não estão no GitHub)
  - mv (move arquivos e pastas)

  ### Configurar repositório do GitHub para Git

- Abrir Git bash na pasta local

- git remote add origin "link do repositório do github"

- Atualizar pastas

  - git push origin master ou main (empurrar as atualizações para ao github)
  - git pull origin master ou main (puxar o conteúdo modificado no github)