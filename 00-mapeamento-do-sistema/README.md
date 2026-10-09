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

## 📊 Painel geral

| Nº | Etapa | Validada | Nota (0-4) | Data |
|---|---|---|---|---|
| 01 | [Entender o negócio e o problema](./01-negocio-e-problema/README.md) | [ ] | ____ | ____/____/____ |
| 02 | [Avaliar viabilidade e risco](./02-viabilidade-e-risco/README.md) | [ ] | ____ | ____/____/____ |
| 03 | [Mapear pessoas e organização](./03-pessoas-e-organizacao/README.md) | [ ] | ____ | ____/____/____ |
| 04 | [Mapear processos, domínio e requisitos](./04-processos-dominio-e-requisitos/README.md) | [ ] | ____ | ____/____/____ |
| 05 | [Mapear dados e integrações](./05-dados-e-integracoes/README.md) | [ ] | ____ | ____/____/____ |
| 06 | [Requisitos não funcionais e restrições](./06-requisitos-nao-funcionais/README.md) | [ ] | ____ | ____/____/____ |
| 07 | [Definir solução e arquitetura inicial](./07-solucao-e-arquitetura-inicial/README.md) | [ ] | ____ | ____/____/____ |
| 08 | [Planejar e preparar a execução](./08-planejamento-e-execucao/README.md) | [ ] | ____ | ____/____/____ |
| 09 | [Validar antes de construir](./09-validacao-antes-de-construir/README.md) | [ ] | ____ | ____/____/____ |

## 🧮 Escala de autoavaliação

| Nota | Nível | Descrição |
|---|---|---|
| 0 | Desconhecido | Nunca estudei ou não lembro nada. |
| 1 | Reconheço | Reconheço os termos, mas não consigo aplicar. |
| 2 | Aplico com apoio | Consigo fazer seguindo modelo ou consultando referências. |
| 3 | Aplico com autonomia | Faço sozinho, justifico minhas escolhas e corrijo meus erros. |
| 4 | Ensino e decido | Conduzo a etapa em projetos reais, oriento outros e avalio trade-offs. |

**Meta por etapa:** nota **3** para validar. Nota 4 nas etapas que forem sua especialidade (por exemplo, analista de requisitos ou arquiteto).

## 🧪 Regras de validação (para evitar se enganar)

- **Evidência acima de sensação.** Documento, diagrama, ata, protótipo ou gravação contam. "Acho que sei" não conta.
- **Sem copiar modelos.** Usar templates é bom; preencher sem entender não valida o critério.
- **Pratique em casos reais.** Mapeie um sistema que existe (um app que você usa, um processo da sua empresa, um projeto pessoal). Casos fictícios só servem para começar.
- **Revisão externa.** Nesta fase, o erro típico é você não enxergar o próprio ponto cego. Peça a outra pessoa para questionar seus artefatos.
- **Teste de legibilidade.** Um artefato bom é entendido por alguém que não participou da conversa.
- **Reteste espaçado.** Volte às perguntas de autoavaliação após 1 semana, 1 mês e 3 meses.

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
