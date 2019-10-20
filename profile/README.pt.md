[EN](./README.md)  |  [PT](./README.pt.md)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/EconObs)

# CoinSnark 

**Laboratório de Pesquisa para Inteligência de Moedas e Criptomoedas**

O **CoinSnark** investiga a engenharia de sistemas automatizados de inteligência para moedas — fiduciárias e cripto — possibilitando monitoramento em tempo real, detecção de arbitragem entre corretoras (*cross-exchange*), análise de microestrutura de mercado e fusão de dados de múltiplas fontes.

Esta é uma pesquisa independente focada em:
- 💱 **Inteligência bimonetária (*dual-currency*)**: Observação unificada de sistemas fiduciários tradicionais (câmbio/forex, bancos centrais, tesouros) e redes cripto descentralizadas (blockchains, DEXs, CEXs).
- 📊 **Microestrutura de mercado**: Compreensão de livros de ofertas (*order books*), padrões de liquidez, dinâmica de *spread* e formação de preços entre plataformas.
- 🔄 **Correlação entre plataformas (*cross-venue*)**: Detecção de oportunidades de arbitragem, diferenciais de latência e ineficiências de fragmentação.
- 🛡️ **Pipelines de dados resilientes**: Sistemas projetados para monitoramento 24/7, mesmo diante de degradação de APIs, limites de requisição (*rate limits*), falhas de WebSocket ou interrupções em corretoras.
- ⚙️ **Abordagem orientada à engenharia**: Performance, determinismo e reprodutibilidade como princípios centrais de design.

O resultado é duplo: ferramentas funcionais de inteligência em código aberto (*open-source*) e os insights científicos derivados de sua construção.

> *"Cada tick conta uma história — se você estiver ouvindo sistematicamente."*

## :microscope: Perguntas de Pesquisa

As investigações atuais exploram:

- Como projetar abstrações unificadas para a extração de dados de moedas em arquiteturas fundamentalmente diferentes (REST, WebSocket, gRPC, RPC de blockchain, protocolo FIX)?
- Qual é o verdadeiro custo (latência, precisão, completude) da agregação entre múltiplas corretoras nos domínios cripto e fiduciário?
- Os sistemas de inteligência conseguem sobreviver a falhas em corretoras (indisponibilidade de API, remoções de listagem/*delistings*, ações regulatórias, *flash crashes*) por meio de degradação graciosa e *circuit breakers*?
- Como as oportunidades de arbitragem de latência evoluem entre diferentes plataformas, e quais *trade-offs* de engenharia são necessários para capturá-las de forma confiável?
- Quais sinais da dinâmica do livro de ofertas preveem de forma confiável a volatilidade de curto prazo ou crises de liquidez?

Linhas de pesquisa detalhadas estão documentadas no arquivo `RESEARCH.md` de cada repositório.

## :bulb: Projetos

**Status e roteiros (*roadmaps*)** são mantidos nos [**Projetos do CoinSnark no GitHub**](https://github.com/orgs/CoinSnark/projects).

Cada repositório é a **única fonte da verdade** para a sua respectiva ferramenta:
- 📋 Documentação principal e protocolos de inteligência
- 🔍 Matriz de cobertura de plataformas (selos/*badges* para corretoras, pares de moedas, tipos de dados)
- 🗂️ *Issues* e discussões de pesquisa
- 🌐 Documentação multilíngue (`README.pt.md`, `README.es.md`, etc.)

## :handshake: Colaboração

Esta pesquisa se beneficia do envolvimento de pesquisadores quantitativos, engenheiros de sistemas de negociação (*trading*), analistas de microestrutura de mercado, economistas financeiros e defensores de dados abertos.

| Recurso | Propósito |
|---------|-----------|
| [**CONTRIBUTING.md da Organização**](CONTRIBUTING.md) | Diretrizes gerais para colaborar com o CoinSnark |
| **CONTRIBUTING.md do Repositório** | Fluxos de trabalho de colaboração específicos de cada ferramenta |
| **Issues com a tag `research`** | Discussões sobre metodologias de inteligência de moedas |
| **Issues com a tag `good first issue`** | Pontos de entrada para novos contribuidores |

:globe_with_meridians: **Multilíngue**: A documentação principal está disponível em português, espanhol e inglês — procure pelos arquivos `.pt.md` e `.es.md` junto às versões em inglês.

## :link: Iniciativas de Pesquisa Relacionadas

Estas organizações exploram aspectos complementares da engenharia de software e da coleta de inteligência:

| Organização | Foco |
|-------------|------|
| [**EconObs**](https://github.com/EconObs) | Inteligência Financeira e Observação Econômica — indicadores macrofinanceiros e correlação entre fontes. |
| [**job-recon**](https://github.com/job-recon) | Inteligência de Mercado de Trabalho e Dados Corporativos Abertos — dinâmica da força de trabalho e demanda por habilidades. |

Juntas, elas formam uma investigação mais ampla sobre sistemas de inteligência resilientes e interdomínios, abrangendo **moedas**, **sistemas financeiros**, **mercados de trabalho** e **automação de infraestrutura**.

## :pushpin: Ritmo e Contexto

Pesquisa independente, conduzida em paralelo ao trabalho profissional. As atualizações são pragmáticas, não performáticas. Contribuições alinhadas às perguntas de pesquisa são bem-vindas.

## :balance_scale: Licença

Código: Apache 2.0  
Documentação: CC BY 4.0

<br />

---

<div align="center">
  <a href="https://github.com/CoinSnark"><img alt="Static Badge" src="https://img.shields.io/badge/-GitHub?style=social&logo=github&logoSize=auto&label=CoinSnark&link=https%3A%2F%2Fgithub.com%2FCoinSnark"></a>
  <a href="https://gitlab.com/CoinSnark"><img alt="Static Badge" src="https://img.shields.io/badge/-GitLab?style=social&logo=gitlab&logoSize=auto&label=CoinSnark&link=https%3A%2F%2Fgitlab.com%2FCoinSnark"></a>
</div>
