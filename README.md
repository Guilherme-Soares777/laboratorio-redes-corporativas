PoC: Infraestrutura de Redes Corporativas (Matriz e Filial)

Este laboratório prático (Proof of Concept) foi desenvolvido para consolidar os fundamentos de redes corporativas, simulando um ambiente escalável com comunicação isolada entre departamentos e roteamento externo. A compreensão física do tráfego de dados é uma base essencial para a minha transição e estudos em Cloud Computing e Análise de Dados.

Tecnologias e Protocolos Utilizados:

Cisco Packet Tracer (Ambiente de simulação)

VLANs (802.1Q) para segmentação lógica de departamentos.

Router-on-a-Stick para roteamento Inter-VLAN.

DHCP Server configurado nativamente nos roteadores.

Roteamento Estático (Link WAN) conectando Matriz e Filial.

Configuração de portas Switchport (Access e Trunk).

Desafios e Troubleshooting:
Validação de conectividade ponta a ponta através de testes ICMP (Ping), analisando o decremento do TTL para confirmar o salto dos pacotes através dos roteadores da infraestrutura.
