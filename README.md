# Guia Coplan no Novo SAT

Ajuda guiada dentro das telas do Novo SAT (GeneXus), usada no apoio ao treinamento da SEFAZ Salvador. Um botão de ajuda em cada tela oferece passo a passo guiado e manual da tela.

**Site com demonstração e passo a passo do desenvolvedor:** https://diegoloureiro84.github.io/novo-sat-guia/

## Como funciona

O Guia Coplan é uma camada em JavaScript que roda sobre a tela do GeneXus, aplicada uma vez na Master Page. Por padrão, não é preciso escrever nenhum texto: o passo a passo (campos obrigatórios ou todos) e o manual da tela são gerados a partir da própria tela.

Textos escritos pelos analistas são um recurso opcional, para as telas prioritárias.

## Pacotes para download (versão 1.2)

| Pacote | O que é | Obrigatório |
|---|---|---|
| `guia-coplan-v1.2-1-base.zip` | Motor, estilos e configuração. Gera passo a passo e manual automáticos | Sim |
| `guia-coplan-v1.2-2-opcao-pasta.zip` | Textos escritos em arquivos .json, um por tela | Não |
| `guia-coplan-v1.2-3-opcao-tabela.zip` | Textos escritos em uma tabela do GeneXus, com cadastro e Procedure | Não |
| `guia-coplan-v1.2-4-opcao-evidencia.zip` | Registro de uso da ajuda por tela e usuário | Não |

Cada pacote tem um LEIA-ME com o passo a passo de instalação e a estimativa de esforço. O site traz a página "Escolher as opções", que compara implantação e manutenção de cada uma.

## Estado atual

- Validado pelo Bruno Marchetto no GeneXus 16 (KB do Tributário): o passo a passo escrito da tela de NFS-e.
- Ainda não testado em uma KB real: a geração automática do passo a passo e do manual.
- O código GeneXus das opções Tabela e Evidência não foi compilado.
- As estimativas de esforço são aproximações e precisam de confirmação do desenvolvedor.

## Créditos

- Driver.js 1.8.0 (licença MIT): https://github.com/nilbuild/driver.js
- Coplan, área de Inovação.
