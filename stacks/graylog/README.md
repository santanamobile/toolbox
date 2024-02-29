# Graylog

O Graylog é uma plataforma de gerenciamento de logs e análise de registros, projetada para centralizar, processar e analisar logs de várias fontes em um ambiente corporativo. Ele oferece recursos como pesquisa avançada, alertas em tempo real e visualizações personalizadas, facilitando a identificação de problemas, monitoramento de segurança e análise de dados de registro em larga escala. O Graylog é útil para empresas que precisam gerenciar grandes volumes de logs, proporcionando visibilidade e insights cruciais para manutenção, segurança e solução de problemas em sistemas distribuídos.

## Requisitos

Em /etc/sysctl.conf é preciso alterar o parâmetro max_map_count para: 262144

'''bash
    sysctl -w vm.max_map_count=262144
'''

## Matriz de compatibilidade

Caso esteja planejando realizar um upgrade de versão do graylog, é importante verificar a matriz de compatibilidade e seus requisitos.

[Requisitos](https://go2docs.graylog.org/5-0/planning_your_deployment/planning_your_upgrade_to_opensearch.htm)
