# Guia Completo de Engenharia de Software

*Mapa de tudo o que envolve a profissão, do básico à senioridade. Legenda: 🧱 fundamento durável (vale por décadas) · 🔄 ferramenta ou prática que evolui rápido (confirme o que está vigente).*

**Regra de ouro:** engenharia de software não é "saber programar". É construir, entregar e manter sistemas que continuam funcionando, sendo compreensíveis e evoluindo ao longo do tempo, trabalhando em equipe.

---

## Trilha sugerida

```
[1] Programação e lógica
 │
[2] Computação essencial (SO, redes, arquitetura)
 │
[3] Estruturas de dados e algoritmos
 │
[4] Ferramentas do dia a dia (Git, terminal, IDE)
 │
[5] Design e qualidade de código
 │
[6] Testes e depuração
 │
[7] Bancos de dados
 │
[8] Back-end, APIs e front-end
 │
[9] Arquitetura e design de sistemas
 │
[10] DevOps, nuvem e infraestrutura
 │
[11] Segurança, observabilidade e confiabilidade
 │
[12] Processos, produto e liderança
 │
[13] Especializações e IA aplicada à engenharia
```

Prazo realista: **2 a 3 anos** para ficar produtivo em equipe e **5 a 8 anos** de prática real para atuar como sênior. Senioridade vem de ter colocado coisas em produção, errado e consertado.

---

## 1. Programação e lógica

- 🧱 **Lógica e resolução de problemas**: decompor problemas, pensar em casos de borda, simular o código "na cabeça".
- 🧱 **Conceitos universais**: variáveis, tipos, controle de fluxo, funções, escopo, recursão, tratamento de erros, entrada e saída.
- 🧱 **Paradigmas**: imperativo, orientado a objetos, funcional (imutabilidade, funções puras, higher-order functions), declarativo, orientado a eventos.
- 🧱 **Tipagem**: estática vs. dinâmica, forte vs. fraca, inferência de tipos, generics.
- 🧱 **Gerenciamento de memória**: stack, heap, ponteiros, garbage collection, ownership.
- 🧱 **Concorrência e paralelismo**: threads, processos, race conditions, deadlocks, locks, async/await, modelo de atores, filas.
- 🔄 **Linguagens** (escolha uma para aprofundar e conheça outras para ampliar a visão):
  - Python (versátil, IA, scripts, back-end)
  - JavaScript/TypeScript (web, Node, front-end)
  - Java e Kotlin (empresas, Android)
  - C# (empresas, jogos)
  - Go (infraestrutura, serviços)
  - Rust (sistemas, segurança de memória)
  - C e C++ (desempenho, sistemas, jogos)
  - SQL (dados, sempre)
  - Bash (automação)
- **Dica:** aprender uma segunda linguagem de paradigma diferente é o que mais acelera seu crescimento.

---

## 2. Fundamentos de computação

- 🧱 **Sistemas operacionais**: processos, threads, escalonamento, memória virtual, sistema de arquivos, I/O, chamadas de sistema, containers vs. máquinas virtuais.
- 🧱 **Redes**: modelo OSI e TCP/IP, IP, DNS, HTTP/HTTPS, TLS, TCP vs. UDP, WebSockets, gRPC, balanceamento de carga, CDN, latência e largura de banda.
- 🧱 **Arquitetura de computadores**: CPU, cache, memória, barramentos, instruções, noções de GPU.
- 🧱 **Linux e terminal**: navegação, permissões, processos, pipes, redirecionamento, `grep`, `sed`, `awk`, `ssh`, `systemd`, cron.
- 🧱 **Teoria da computação (básico)**: autômatos, gramáticas, compiladores e interpretadores, noção de indecidibilidade.
- 🧱 **Matemática discreta**: lógica, conjuntos, combinatória, grafos, noções de probabilidade.

---

## 3. Estruturas de dados e algoritmos

- 🧱 **Estruturas**: arrays, listas ligadas, pilhas, filas, deques, tabelas hash, árvores (binárias, BST, AVL, rubro-negras, B-trees), heaps, tries, grafos, conjuntos disjuntos.
- 🧱 **Algoritmos**: ordenação, busca binária, recursão e backtracking, divisão e conquista, programação dinâmica, algoritmos gulosos, algoritmos de grafos (BFS, DFS, Dijkstra, ordenação topológica, árvore geradora mínima).
- 🧱 **Análise de complexidade**: notação Big-O, tempo vs. espaço, análise amortizada.
- 🧱 **Strings e padrões**: busca em texto, expressões regulares, hashing.
- 🔄 **Treino prático**: LeetCode, Codeforces, Advent of Code. Útil para entrevistas e raciocínio, mas não substitui construir projetos.
- **Aplicação real:** escolher a estrutura certa muda o desempenho do sistema em ordens de grandeza.

---

## 4. Ferramentas do dia a dia

- 🧱 **Git e controle de versão**: commits, branches, merge vs. rebase, resolução de conflitos, `cherry-pick`, `bisect`, `stash`, tags, histórico limpo, mensagens de commit boas.
- 🔄 **Fluxos de trabalho**: trunk-based development, GitHub Flow, Git Flow, pull requests, code review, monorepo vs. multirepo.
- 🔄 **Plataformas**: GitHub, GitLab, Bitbucket.
- 🔄 **IDEs e editores**: VS Code, JetBrains, Vim/Neovim, depuradores, atalhos, snippets.
- 🔄 **Gerenciadores de pacotes e build**: pip/uv/poetry, npm/pnpm/yarn, Maven/Gradle, Cargo, Go modules, Make, Bazel.
- 🧱 **Documentação**: README bom, comentários que explicam o *porquê*, diagramas, ADRs (registros de decisão de arquitetura).
- 🧱 **Ambientes**: variáveis de ambiente, gerenciamento de configuração, ambientes de desenvolvimento reproduzíveis (dev containers).

---

## 5. Design e qualidade de código

- 🧱 **Código limpo**: nomes claros, funções pequenas e coesas, baixo acoplamento, alta coesão, evitar duplicação (DRY), simplicidade (KISS), não antecipar (YAGNI).
- 🧱 **Princípios SOLID**: responsabilidade única, aberto/fechado, substituição de Liskov, segregação de interfaces, inversão de dependências.
- 🧱 **Padrões de projeto (design patterns)**: criacionais (Factory, Builder, Singleton), estruturais (Adapter, Decorator, Facade), comportamentais (Strategy, Observer, Command, State).
- 🧱 **Refatoração**: code smells, técnicas de refatoração segura, dívida técnica e quando pagá-la.
- 🧱 **Programação orientada a objetos e composição vs. herança**.
- 🧱 **Domain-Driven Design (DDD)**: linguagem ubíqua, contextos delimitados, agregados, entidades e objetos de valor.
- 🧱 **Arquitetura de código**: camadas, hexagonal (ports and adapters), clean architecture, injeção de dependência.
- 🧱 **Tratamento de erros e logs**: erros como parte do design, mensagens úteis, níveis de log, logs estruturados.
- 🔄 **Ferramentas de qualidade**: linters, formatadores, análise estática, type checkers, SonarQube.
- 🧱 **Revisão de código**: dar e receber feedback com foco no código, não na pessoa.

---

## 6. Testes, depuração e qualidade

- 🧱 **Pirâmide de testes**: unitários, de integração, de contrato, ponta a ponta (E2E).
- 🧱 **Técnicas**: TDD, BDD, testes baseados em propriedades, testes de mutação, testes parametrizados.
- 🧱 **Dublês de teste**: mocks, stubs, fakes, spies. Saber quando *não* usar mocks.
- 🧱 **Cobertura de testes**: o que mede e o que não mede.
- 🧱 **Testes não funcionais**: desempenho, carga, estresse, segurança, acessibilidade, compatibilidade.
- 🧱 **Depuração**: reproduzir o bug, isolar, formular hipóteses, usar depurador, logs, bisect, análise de causa raiz.
- 🧱 **Testes flaky** (instáveis) e como eliminá-los.
- 🔄 **Ferramentas**: pytest, JUnit, Jest/Vitest, Playwright, Cypress, k6, Locust, Testcontainers.
- 🧱 **Qualidade como cultura**: definição de pronto, quality gates no CI, testes em produção com segurança (feature flags, canary).

---

## 7. Bancos de dados e persistência

- 🧱 **Modelagem**: modelo entidade-relacionamento, normalização e desnormalização, chaves, integridade referencial.
- 🧱 **SQL avançado**: joins, subconsultas, CTEs, window functions, índices, planos de execução, otimização de consultas.
- 🧱 **Transações**: ACID, níveis de isolamento, locks, MVCC, deadlocks.
- 🧱 **Teorema CAP e consistência**: consistência forte vs. eventual, replicação, particionamento (sharding).
- 🔄 **Bancos relacionais**: PostgreSQL, MySQL/MariaDB, SQL Server, Oracle, SQLite.
- 🔄 **NoSQL**: documentos (MongoDB), chave-valor (Redis, DynamoDB), colunar (Cassandra), grafos (Neo4j), séries temporais, busca (Elasticsearch/OpenSearch).
- 🔄 **Bancos vetoriais** (para IA): pgvector, Qdrant, Milvus, Pinecone.
- 🧱 **Migrações de schema** sem derrubar o sistema, versionamento do banco.
- 🧱 **Cache**: estratégias (cache-aside, write-through), invalidação, TTL.
- 🧱 **Filas e mensageria**: Kafka, RabbitMQ, SQS, pub/sub, entrega at-least-once vs. exactly-once, idempotência.
- 🧱 **Backup, recuperação e retenção de dados**.

---

## 8. Back-end, APIs e front-end

### Back-end
- 🧱 **APIs REST**: recursos, verbos, códigos de status, versionamento, paginação, idempotência, HATEOAS (conceito).
- 🔄 **Outros estilos**: GraphQL, gRPC, WebSockets, Server-Sent Events, webhooks, tRPC.
- 🧱 **Autenticação e autorização**: sessões, JWT, OAuth 2.0, OpenID Connect, RBAC/ABAC, SSO.
- 🧱 **Contratos de API**: OpenAPI/Swagger, compatibilidade retroativa, deprecação.
- 🧱 **Processamento assíncrono**: jobs em segundo plano, filas, retries, dead-letter queues.
- 🔄 **Frameworks**: Django, FastAPI, Flask, Express/NestJS, Spring Boot, ASP.NET, Rails, Laravel, Gin.
- 🧱 **Rate limiting, throttling, circuit breaker, backpressure**.

### Front-end
- 🧱 **Fundamentos web**: HTML, CSS, JavaScript, DOM, eventos, como o navegador renderiza, acessibilidade (WCAG), SEO básico.
- 🧱 **Desempenho web**: Core Web Vitals, lazy loading, cache, bundles, renderização (CSR, SSR, SSG, ISR).
- 🔄 **Frameworks**: React, Vue, Angular, Svelte, Next.js, Nuxt, Astro.
- 🧱 **Gerenciamento de estado, componentização, design systems**.
- 🔄 **CSS moderno**: Flexbox, Grid, Tailwind, CSS-in-JS.
- 🧱 **Segurança no cliente**: XSS, CSRF, CORS, Content Security Policy.

### Outras plataformas
- 🔄 **Mobile**: nativo (Swift/iOS, Kotlin/Android) e multiplataforma (Flutter, React Native).
- 🔄 **Desktop, jogos (Unity, Unreal, Godot), embarcados/IoT, WebAssembly**.

---

## 9. Arquitetura e design de sistemas

- 🧱 **Requisitos**: funcionais e não funcionais (desempenho, disponibilidade, escalabilidade, segurança, manutenibilidade, custo).
- 🧱 **Estilos arquiteturais**: monólito, monólito modular, microsserviços, serverless, orientado a eventos, em camadas, hexagonal, CQRS e Event Sourcing.
- 🧱 **Escalabilidade**: vertical vs. horizontal, balanceamento de carga, cache, particionamento, replicação, CDN, bancos de leitura.
- 🧱 **Sistemas distribuídos**: falhas parciais, relógios e ordenação de eventos, consenso (Raft, Paxos, em conceito), consistência, idempotência, sagas, transações distribuídas, outbox pattern.
- 🧱 **Confiabilidade**: SLI, SLO, SLA, redundância, failover, degradação graciosa, timeouts, retries com backoff, bulkheads.
- 🧱 **Trade-offs**: custo vs. desempenho vs. complexidade vs. tempo de entrega. Sênior sabe justificar escolhas e registrar em ADRs.
- 🧱 **Entrevista de system design**: estimar capacidade, definir APIs, modelar dados, identificar gargalos. Exemplos clássicos: encurtador de URL, feed de rede social, chat, sistema de notificações, upload de vídeos.
- 🧱 **Migrações e modernização**: strangler fig pattern, reescrita vs. evolução, lidar com sistemas legados.
- 🧱 **Diagramas**: C4 model, UML essencial (classes, sequência), diagramas de fluxo e de implantação.
- 🧱 **Evolução arquitetural**: arquitetura evolutiva, fitness functions, evitar overengineering.

---

## 10. DevOps, nuvem e infraestrutura

- 🧱 **CI/CD**: integração contínua, entrega e implantação contínuas, pipelines, artefatos, gates de qualidade.
- 🔄 **Ferramentas de CI/CD**: GitHub Actions, GitLab CI, Jenkins, CircleCI, Argo CD.
- 🧱 **Estratégias de deploy**: rolling, blue-green, canary, feature flags, rollback.
- 🔄 **Containers**: Docker, boas práticas de imagens, registries.
- 🔄 **Orquestração**: Kubernetes (pods, deployments, services, ingress, HPA, Helm), alternativas mais simples (ECS, Nomad, Cloud Run).
- 🔄 **Infraestrutura como código**: Terraform/OpenTofu, Pulumi, CloudFormation, Ansible.
- 🔄 **Nuvem**: AWS, Azure, GCP. Conceitos comuns: computação, armazenamento, rede (VPC), IAM, bancos gerenciados, serverless, filas, CDN.
- 🧱 **FinOps**: entender e controlar custos de nuvem.
- 🧱 **GitOps, plataforma interna (platform engineering), ambientes efêmeros**.
- 🧱 **Gerenciamento de configuração e segredos**: Vault, gerenciadores de segredos da nuvem, nunca versionar credenciais.

---

## 11. Segurança, observabilidade e operação

### Segurança
- 🧱 **Princípios**: menor privilégio, defesa em profundidade, falhar de forma segura, confiar desconfiando.
- 🧱 **OWASP Top 10**: injeção, autenticação quebrada, exposição de dados, XSS, controle de acesso, configuração insegura, componentes vulneráveis, SSRF e outros.
- 🧱 **Criptografia aplicada**: hash de senhas (bcrypt, argon2), criptografia simétrica e assimétrica, assinaturas, TLS, gerenciamento de chaves. Nunca invente sua própria criptografia.
- 🧱 **Segurança da cadeia de suprimentos**: dependências, SBOM, verificação de assinaturas, escaneamento de vulnerabilidades.
- 🧱 **Modelagem de ameaças**: STRIDE e abordagens parecidas.
- 🧱 **Privacidade e conformidade**: LGPD, GDPR, minimização de dados, retenção.
- 🔄 **Ferramentas**: SAST, DAST, Dependabot/Renovate, scanners de contêineres, gestores de segredos.
- 🧱 **DevSecOps**: segurança integrada ao pipeline desde o início.

### Observabilidade e operação
- 🧱 **Três pilares**: logs, métricas e traces distribuídos.
- 🔄 **Ferramentas**: Prometheus, Grafana, OpenTelemetry, Datadog, ELK/Loki, Sentry.
- 🧱 **Alertas úteis**: alertar sobre sintomas, evitar fadiga de alertas, runbooks.
- 🧱 **Gestão de incidentes**: resposta, comunicação, postmortems sem culpados.
- 🧱 **SRE**: error budgets, toil, engenharia do caos, planejamento de capacidade.
- 🧱 **Plantão (on-call) saudável**.

---

## 12. Processos, produto e liderança

- 🧱 **Metodologias**: Scrum, Kanban, XP, Lean, Shape Up, e quando cada uma faz sentido.
- 🧱 **Planejamento e estimativas**: incerteza, decomposição de tarefas, fatiamento vertical, entrega incremental.
- 🧱 **Visão de produto**: entender o problema do usuário, métricas de produto, discovery, MVP, priorização.
- 🧱 **Métricas de engenharia**: DORA (frequência de deploy, lead time, taxa de falha, tempo de recuperação), SPACE, cuidado com métricas que viram metas.
- 🧱 **Comunicação**: escrever bem (design docs, RFCs), explicar decisões técnicas para públicos não técnicos, reuniões produtivas.
- 🧱 **Trabalho em equipe**: revisão de código, pair/mob programming, mentoria, onboarding, cultura de feedback.
- 🧱 **Dívida técnica**: tornar visível, priorizar, negociar tempo para pagá-la.
- 🧱 **Liderança técnica**: influenciar sem autoridade, tomar e registrar decisões, delegar, formar outras pessoas.
- 🧱 **Carreira**: trilha de especialista (staff, principal) vs. gestão (liderança de equipes, direção), portfólio, networking.
- 🧱 **Ética e responsabilidade profissional**: impacto das decisões, licenças de software, acessibilidade, privacidade.
- 🧱 **Open source**: como contribuir, licenças (MIT, Apache, GPL), manter projetos.

---

## 13. Especializações e IA aplicada à engenharia

### Especializações comuns
- **Back-end e sistemas distribuídos**
- **Front-end e experiência do usuário**
- **Mobile**
- **DevOps, SRE e Platform Engineering**
- **Segurança de aplicações (AppSec)**
- **Engenharia de dados** (pipelines, data lakes, streaming)
- **Engenharia de ML/IA e MLOps**
- **Sistemas embarcados, IoT e firmware**
- **Jogos e gráficos**
- **Blockchain e finanças** (nicho)
- **Qualidade e automação de testes (SDET)**
- **Arquitetura de software e de soluções**

### IA no dia a dia da engenharia 🔄
- **Assistentes e agentes de código**: autocomplete, chat, agentes que editam repositórios, revisão de PRs, geração de testes, migração de código legado, documentação automática.
- **Ferramentas**: Claude Code, Cursor, GitHub Copilot, Codex, Windsurf, entre outras. Mudam a cada poucos meses.
- **Habilidades que ganham valor**: especificar bem a tarefa, revisar criticamente, escrever bons testes, entender arquitetura e segurança. Sem fundamentos sólidos, você não consegue avaliar o que a IA entrega.
- **Riscos**: código plausível porém errado, falhas de segurança, dependências inventadas, perda de compreensão do próprio sistema, vazamento de dados sensíveis em prompts.
- **Boas práticas**: tratar saída da IA como código de um colega júnior (revisar sempre), manter testes automatizados, trabalhar em passos pequenos, documentar decisões e usar controle de versão para poder desfazer.
- **Construir sistemas com IA**: integrar LLMs a produtos, RAG, agentes, avaliação, observabilidade e custos. É uma especialização de engenharia por si só.

---

## Projetos para praticar (um por etapa)

1. **Lógica e linguagem:** CLI de tarefas ou conversor de unidades, com testes.
2. **Estruturas de dados:** implementar do zero uma tabela hash, uma árvore e um grafo com buscas.
3. **Git e colaboração:** contribuir com um projeto open source, mesmo que seja documentação.
4. **Design de código:** refatorar um projeto antigo aplicando SOLID e testes.
5. **Back-end:** API REST com autenticação, banco relacional, migrações e documentação OpenAPI.
6. **Front-end:** aplicação completa consumindo sua API, com acessibilidade e bom desempenho.
7. **Infra:** containerizar tudo, criar pipeline de CI/CD e implantar na nuvem com infraestrutura como código.
8. **Arquitetura:** evoluir o projeto para ter fila, cache e processamento assíncrono, e escrever um design doc justificando.
9. **Observabilidade:** adicionar logs estruturados, métricas, traces e alertas, e simular um incidente.
10. **Segurança:** auditar seu projeto pelo OWASP Top 10 e corrigir o que achar.
11. **Capstone:** um produto real com usuários de verdade, documentação, testes e monitoramento.

---

## Livros e referências clássicas

*(Livros duram décadas; ferramentas, não.)*

- **Código e design:** *Código Limpo* (Robert C. Martin), *Refatoração* (Martin Fowler), *O Programador Pragmático* (Hunt e Thomas), *Padrões de Projeto* (Gang of Four), *Domain-Driven Design* (Eric Evans).
- **Arquitetura e sistemas:** *Designing Data-Intensive Applications* (Martin Kleppmann), *Fundamentos da Arquitetura de Software* (Richards e Ford), *Building Microservices* (Sam Newman), *A Philosophy of Software Design* (John Ousterhout).
- **Operação:** *Site Reliability Engineering* (Google), *Accelerate* (Forsgren, Humble, Kim), *The Phoenix Project* e *The DevOps Handbook*.
- **Algoritmos:** *Introduction to Algorithms* (CLRS), *Algorithm Design Manual* (Skiena).
- **Carreira e equipes:** *The Staff Engineer's Path* (Tanya Reilly), *Peopleware* (DeMarco e Lister), *The Mythical Man-Month* (Brooks).

---

## Checklist de senioridade

Você está no caminho de sênior quando:

- Entrega funcionalidades complexas de ponta a ponta com pouca supervisão, incluindo testes, deploy e monitoramento.
- Explica o *porquê* das escolhas técnicas e os trade-offs, não só o *como*.
- Projeta sistemas considerando falhas, escala, custo e segurança.
- Faz boas revisões de código e ajuda outras pessoas a crescerem.
- Depura problemas difíceis em produção com método.
- Reduz complexidade em vez de aumentá-la.
- Comunica bem por escrito (design docs, postmortems) e com áreas não técnicas.
- Sabe quando *não* construir algo, ou quando usar a solução mais simples.
- Mantém-se atualizado sem correr atrás de cada nova ferramenta.
