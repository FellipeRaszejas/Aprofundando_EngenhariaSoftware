# Mapeamento do Sistema · Painel de Validação

Este repositório organiza o seu estudo da **fase de mapeamento e análise de um sistema, antes de desenvolver**: entender o negócio, avaliar riscos, levantar requisitos, modelar, desenhar a arquitetura inicial, planejar e validar. Cada pasta numerada tem o seu próprio README de validação.

> **Ideia central:** quase tudo nesta fase existe para reduzir o risco de **construir a coisa errada**, que custa muito mais do que construir a coisa certa com imperfeições. Quanto antes um erro de entendimento é descoberto, mais barato é corrigi-lo.

## 🔄 Onde esta fase se encaixa

```
Negócio e problema → Viabilidade e risco → Pessoas → Processos, domínio e requisitos
       → Dados e integrações → Requisitos não funcionais → Arquitetura inicial
       → Planejamento → Validação → [ Construção, testes, operação ]
```

As etapas **não são estritamente sequenciais**. Na prática há iteração: o que você descobre na validação (09) pode reabrir requisitos (04) ou riscos (02). Isso é normal e esperado.

## 🧭 Como usar

1. Entre na pasta da etapa e abra o `README.md`.
2. Estude e produza os artefatos, guardando-os em `artefatos/`.
3. Marque tópicos, critérios e artefatos **somente com evidência**.
4. Responda às perguntas de autoavaliação sem consultar nada.
5. Peça revisão de pelo menos um artefato a outra pessoa.
6. Atribua nota de 0 a 4, preencha o parecer final e atualize a tabela abaixo.


## 📄 Projeto-âncora sugerido

Escolha **um único sistema** e atravesse as 9 etapas com ele. No fim você terá um **dossiê completo de pré-desenvolvimento**, que serve como portfólio. Estrutura sugerida do dossiê:

1. Visão, escopo e business case
2. Viabilidade e registro de riscos
3. Stakeholders, personas e jornadas
4. Processos, glossário, requisitos e casos de uso
5. Modelo de dados e mapa de integrações
6. Requisitos não funcionais e modelagem de ameaças
7. Arquitetura inicial e ADRs
8. Roadmap, backlog e plano de execução
9. Protótipo, relatório de validação e baseline

## 🗂️ Estrutura de pastas

```
mapeamento-do-sistema/
├── README.md          ← este painel
├── 01-negocio-e-problema/
├── 02-viabilidade-e-risco/
├── 03-pessoas-e-organizacao/
├── 04-processos-dominio-e-requisitos/
├── 05-dados-e-integracoes/
├── 06-requisitos-nao-funcionais/
├── 07-solucao-e-arquitetura-inicial/
├── 08-planejamento-e-execucao/
├── 09-validacao-antes-de-construir/
```

## 🔗 Relação com o guia de engenharia de software

Estas 9 etapas formam a fase **anterior** à construção. Elas se conectam às seções do guia de engenharia de software assim: requisitos não funcionais (06) e arquitetura inicial (07) alimentam a seção de arquitetura e design de sistemas; planejamento (08) alimenta processos e liderança; dados e integrações (05) alimentam bancos de dados e APIs; validação (09) conecta-se a testes e qualidade.

## 📈 Registro de progresso (opcional)

| Mês | Etapas em andamento | Horas totais | Principais aprendizados | Dificuldades |
|---|---|---|---|---|
|  |  |  |  |  |
