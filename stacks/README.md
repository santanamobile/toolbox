# Docker Compose Stacks

Lista de stacks:

- Portainer

## Deploy

Para faciliar a utilização do docker, sugiro começar pelo portainer.

Acesse stacks/portainer e provisione o container com:

'''bash
    docker-compose up -d
'''

Ou

'''bash
    docker-compose -f stacks/portainer/docker-compose.yaml up -d
'''

Após a execução acesse a interface através do endereço: <https://localhost:9443/>

As demais stacks podem ser provisionadas a partir da interface do portainer.
