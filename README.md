# Caixa de Ferramentas

Conjunto de ferramentas para provisionar um ambiente de desenvolvimento/testes em estação de trabalho.

O ansible deve ser instalado manualmente para a execução do playbook.

```bash
sudo apt install ansible -y
```

A seguir execute o playbook com:

```bash
ansible-playbook playbook.yaml
```

Após a execução do playbook serão instalados os recursos:

- docker
- terraform

## Docker

Após a instalação do docker o usuário é adicionado ao grupo docker.

## Disclaimer

Estes recursos são providos 'como estão', as configurações de segurança, hardening são de responsabilidade do usuário.
