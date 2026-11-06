# Mídias Indoor — Plataforma de Conteúdo para Condomínios

**Categoria:** CMS · players distribuídos · aplicações desktop · operação digital  
**Status:** solução consolidada e testada, conforme documentação do projeto  
**Repositório de referência:** [condominio-player-cms](https://github.com/mayconabentes-bi/condominio-player-cms)

## Problema

A operação com players isolados gera versões duplicadas, atualizações manuais e maior risco de falhas na reprodução das telas. A conectividade instável também pode interromper a exibição de conteúdo.

## Minha responsabilidade

- levantar requisitos operacionais e orientar a definição do modelo centralizado de conteúdo;
- coordenar a consolidação entre CMS e players;
- priorizar segurança, confiabilidade e automação;
- acompanhar a evolução da experiência administrativa e da operação distribuída.

## Evidências

O projeto documenta um CMS para condomínios, dispositivos, mídias, playlists e planos; players Electron em modo quiosque; sincronização com retry e download atômico; validação de integridade; heartbeat e watchdog; autenticação por dispositivo; testes unitários e de integração; e CI/CD.

## Resultados técnicos documentados

Na consolidação registrada no repositório:

- quatro cópias foram reunidas em um monorepo;
- as linhas duplicadas foram reduzidas em aproximadamente 94%;
- os arquivos duplicados caíram cerca de 75%;
- a cobertura de testes passou de zero para aproximadamente 70%;
- a implantação foi registrada como quatro vezes mais rápida.

Esses números são resultados técnicos documentados pelo projeto; não representam métricas auditadas de adoção comercial ou desempenho em clientes.

## Confidencialidade

Endereços, redes, dispositivos, clientes e configurações operacionais permanecem privados.
