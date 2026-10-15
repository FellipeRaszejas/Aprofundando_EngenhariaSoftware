# Negócio e Problema

> "Durante a competição, o erro mais comum não é a falta de habilidade, e sim construir da maneira errada."

---

## 1. Antes de projetar o sistema

Existe uma série de perguntas que é de bom tom fazer antes de começar a projetar um sistema.

![Perguntas antes de projetar](imagens/perguntas.jpg)

### 1.1 Qual é a dor real que o sistema resolve? *(o problema de negócio)*

**Exemplo:** preciso de um sistema que gerencie quanto tempo você está treinando para a olimpíada da SPSKILLS.

### 1.2 Quem são os usuários e quais são as regras de ouro? *(escopo funcional essencial)*

**Aplicação imaginária ilustrativa:** sistema da Liga da Justiça para aceitar um novo membro.

- **Personagens:** pessoas da DC
- **Regras:** ser da DC e ser herói

![Liga da Justiça](imagens/liga.jpg)

Quem **não** atende às regras é recusado, mesmo sendo herói:

![Vingadores (Marvel) – não são da DC](imagens/vingadores.jpg)

### 1.3 Qual é o "Critério de Sucesso"?

O que valida o funcionamento do sistema (e garante a pontuação máxima).

---

## 2. Para a prova

### 2.1 Leitura da prova

Faça uma **leitura ativa** e divida o enunciado em blocos, buscando:

| Item | O que buscar | Exemplo / dica |
|---|---|---|
| **Core Business** (coração do sistema) | A funcionalidade sem a qual o sistema não serve para nada | Um banco: entrada e saída de dinheiro + cadastro de clientes |
| **Regras de negócio críticas** | Tudo que vira validação no backend e permissão | Palavras-chave: `DEVE`, `NÃO PODE`, `SOMENTE SE`, `CASO CONTRÁRIO` |
| **Fluxo de valor** | Como/por onde o dado chega à aplicação, como é processado e o que entregamos no final | Entrada → Processamento → Saída |

![Exemplo de Core Business: banco](imagens/banco.jpg)

---

## 3. Enxergando formas de criar e adaptar

### 3.1 Simplicidade vs. complexidade desnecessária

Você não vai desenvolver o sistema mais profissional que existe, e sim o que **mais atende aos critérios**. Claro, você não terá acesso a eles, mas deve desenvolver a melhor solução para o problema proposto.

> **"Busque o melhor da simplicidade."**

- ⚠️ **Armadilha:** querer usar arquiteturas ultramodernas (como microsserviços complexos ou padrões de projeto pesados) para um sistema que pode ser resolvido com uma aplicação modular bem estruturada em camadas.
- ✅ **Adaptação ideal:** escolher o caminho mais simples que atenda **100% dos requisitos funcionais** da prova, com alta manutenibilidade.

### 3.2 Reaproveitar código

> O que eu já fiz ou trago estruturado que resolve mais de uma parte?

---

## 4. Por onde começar a criar?

1. **Definição do MVP (Escopo Mínimo Viável):** o mínimo para o sistema ser considerado aceitável e servir de base para as outras etapas.
2. **Estrutura de domínio:** entender a lógica por trás das entidades básicas e seus relacionamentos. A modelagem das informações (dados) é o começo de tudo.
3. **Implementar funcionalidade por funcionalidade.**