# SonarQube

O SonarQube é uma ferramenta de análise estática de código que avalia a qualidade do software. Ele identifica e relata automaticamente problemas como bugs, vulnerabilidades, duplicações e violações de padrões de codificação. O SonarQube é utilizado para melhorar a manutenibilidade, confiabilidade e segurança do código-fonte, proporcionando feedback contínuo aos desenvolvedores durante o ciclo de desenvolvimento, permitindo uma abordagem proativa na melhoria da qualidade do software.

## Requisitos

Em /etc/sysctl.conf é preciso alterar/acrescentar os seguintes parâmetros:

vm.max_map_count=524288
fs.file-max=131072
ulimit -n 131072
ulimit -u 8192

'''bash
    sysctl -w fs.file-max=131072
    sysctl -w vm.max_map_count=524288
    ulimit -n 131072
    ulimit -u 8192
'''

## Credenciais

Default user: admin, pass: admin
