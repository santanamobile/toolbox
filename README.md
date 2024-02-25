# Caixa de Ferramentas

Conjunto de ferramentas para provisionar um ambiente de desenvolvimento/testes em estação de trabalho.

O ansible deve ser instalado manualmente para o provisionamento do ambiente:

    sudo apt install ansible -y

A seguir execute o playbook com:

    ansible -i playbook.yaml

Após a execução do playbook serão instalados os recursos:

- docker
- terraform

## Docker

Após a instalação do docker é preciso configurar as permissões.

    sudo usermod -aG docker $(whoami)

## Disclaimer

Estes recursos são providos 'como estão', as configurações de segurança, hardening são de responsabilidade do usuário.
