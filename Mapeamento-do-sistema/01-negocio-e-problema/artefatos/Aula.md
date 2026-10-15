# Negócio e Problema

> "Durante a competição, o erro mais comum não é a falta de habilidade, e sim construir da maneira errada."

---

## Antes de projetar o sistema

Existe uma série de perguntas que é de bom tom fazer antes de começar a projetar um sistema.

<img src="imagens/perguntas.jpg" alt="Perguntas antes de projetar" width="600">

### Qual é a dor real que o sistema resolve?

<span style="color:#1f6feb"><b>Problema de negócio</b></span>: o motivo pelo qual o sistema precisa existir.

**Exemplo:** preciso de um sistema que gerencie quanto tempo você está treinando para a olimpíada da SPSKILLS.

### Quem são os usuários e quais são as regras de ouro?

<span style="color:#1f6feb"><b>Escopo funcional essencial</b></span>: quem usa o sistema e o que ele obrigatoriamente precisa respeitar.

**Aplicação imaginária ilustrativa:** sistema da Liga da Justiça para aceitar um novo membro.

- **Personagens:** pessoas da DC
- **Regras:** ser da DC e ser herói

Quem não atende às regras é recusado, mesmo sendo herói.

<table>
  <tr>
    <td align="center"><img src="imagens/liga.jpg" alt="Liga da Justiça" width="260"><br><sub>Aceitos (DC)</sub></td>
    <td align="center"><img src="imagens/vingadores.jpg" alt="Vingadores" width="260"><br><sub>Recusados (Marvel)</sub></td>
  </tr>
</table>

### Qual é o "Critério de Sucesso"?

<span style="color:#1f6feb"><b>Critério de Sucesso</b></span>: o que valida o funcionamento do sistema e garante a pontuação máxima.

---

## Para a prova

### Leitura da prova

Faça uma **leitura ativa** e divida o enunciado em blocos, buscando:

- <span style="color:#1f6feb"><b>Core Business (coração do sistema)</b></span>: a funcionalidade sem a qual o sistema não serve para nada.
- <span style="color:#1f6feb"><b>Regras de negócio críticas</b></span>: tudo que vira validação no backend e permissão.
- <span style="color:#1f6feb"><b>Fluxo de valor</b></span>: como e por onde o dado chega à aplicação, como é processado e o que entregamos no final.

**Exemplo de Core Business:** um banco é a entrada e saída de dinheiro e o cadastro de clientes.

<img src="imagens/banco.jpg" alt="Exemplo de Core Business: banco" width="260">

---

## <span style="color:red">Palavras-chave</span>

<span style="color:red"><b>DEVE</b></span> · <span style="color:red"><b>NÃO PODE</b></span> · <span style="color:red"><b>SOMENTE SE</b></span> · <span style="color:red"><b>CASO CONTRÁRIO</b></span>

Indicam regras de negócio críticas no enunciado.

---

## Enxergando formas de criar e adaptar

### Simplicidade vs. complexidade desnecessária

Você não vai desenvolver o sistema mais profissional que existe, e sim o que mais atende aos critérios. Claro, você não terá acesso a eles, mas deve desenvolver a melhor solução para o problema proposto.

> **"Busque o melhor da simplicidade."**

- <span style="color:#d29922"><b>Armadilha</b></span>: querer usar arquiteturas ultramodernas (como microsserviços complexos ou padrões de projeto pesados) para um sistema que pode ser resolvido com uma aplicação modular bem estruturada em camadas.
- <span style="color:#2da44e"><b>Adaptação ideal</b></span>: escolher o caminho mais simples que atenda 100% dos requisitos funcionais da prova, com alta manutenibilidade.

### Reaproveitar código

> O que eu já fiz ou trago estruturado que resolve mais de uma parte?

---

## Por onde começar a criar?

- <span style="color:#1f6feb"><b>MVP (Escopo Mínimo Viável)</b></span>: o mínimo para o sistema ser considerado aceitável e servir de base para as outras etapas.
- <span style="color:#1f6feb"><b>Estrutura de domínio</b></span>: entender a lógica por trás das entidades básicas e seus relacionamentos. A modelagem das informações (dados) é o começo de tudo.
- <span style="color:#1f6feb"><b>Implementação</b></span>: funcionalidade por funcionalidade.

