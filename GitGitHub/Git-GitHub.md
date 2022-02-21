# Introdução ao Git e GitHub     
Durante o desenvolvimento de projetos, os códigos resultantes tendem a sofrer diversas modificações, tornando necessário gerenciá-las, de modo que seja possível realizar eventuais revisões e restaurações.

Esse gerenciamento é feito através de um sistema de controle de versões, um dos mais populares é o **GIT**.

Diferentemente do Git, o **GitHub** é utilizado como serviço de hospedagem de repositório Git, onde os projetos podem ser compartilhados e armazenados fora do servidor local, sendo baseado em nuvem.

---
## Etapas 
* **Working Directory**: Arquivos modificados.

* **Stanging directory**: Arquivos modificados adicionados à area de teste.

* **Committed**: Arquivos com modificações salvas.

---

## Principais Comandos

* `git init`: inicializa o repositório em um diretório

* `git remote add origin <link do repositório>` : conecta o repositório local ao remoto

* `git status`: verifica a situação do arquivo

* `git add`: adiciona o arquivo à area de teste

* `git clone [url]`: clona um repositório

* `git pull`: atualiza o repositório local

* `git commit -m "mensagem"`: realiza o commit

* `git push`: envia as alterações pro repositório remoto

---

## Conflitos e Resoluções
Quando um código sofre alterações simultâneas, podem ocorrer erros em sua sincronização, dessa forma as alterações precisam ser mescladas.

Assim, ao realizar o comando `pull` a versão mais recente será puxada, contudo o conflito de `merge` ocorrerá.

Para resolve-lo é necessário ir até o arquivo indicado e realizar a devida adaptação. Após isso deve-se realizar o processo de adição, o commit e envio para o repositório remoto.
