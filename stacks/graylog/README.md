# Graylog

O Graylog é uma plataforma de gerenciamento de logs e análise de registros, projetada para centralizar, processar e analisar logs de várias fontes em um ambiente corporativo. Ele oferece recursos como pesquisa avançada, alertas em tempo real e visualizações personalizadas, facilitando a identificação de problemas, monitoramento de segurança e análise de dados de registro em larga escala. O Graylog é útil para empresas que precisam gerenciar grandes volumes de logs, proporcionando visibilidade e insights cruciais para manutenção, segurança e solução de problemas em sistemas distribuídos.

## Requisitos

Em /etc/sysctl.conf é preciso alterar o parâmetro max_map_count para: 262144

'''bash
    sysctl -w vm.max_map_count=262144
'''
