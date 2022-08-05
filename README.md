# Playbook Ansible para execução Local
Playbook para execução local no Ubuntu

Este Playbook foi testado com a versão:
- SO: Ubuntu 20.04
- Ansible: 2.9

> Essa role traz informações referete a api Chuck Norris

> Link para API
https://api.chucknorris.io/

Comando para execução de todo o conjunto de playbook.

- `ansible-playbook -i hosts local.yml -vvv`
> Pode ser necessário executar o comando com previlégios de super-usuário utilizando o comando sudo.