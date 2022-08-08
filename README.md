# Playbook Ansible para execução Local
Playbook para execução local no Ubuntu

Este Playbook foi testado com a versão:
- SO: Ubuntu 22.04
- Ansible: 2.10

> Essa role traz informações de algumas APIs publicas.

Links para API

https://api.chucknorris.io/

https://deckofcardsapi.com


Comando para execução de todo o conjunto de playbook.

- `ansible-playbook -i hosts local.yml -vvv`
> Pode ser necessário executar o comando com previlégios de super-usuário utilizando o comando sudo.
