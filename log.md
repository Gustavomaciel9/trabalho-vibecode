# Log de prompts

Regra: registre cada prompt na íntegra, o que a IA entregou, o que estava errado e o prompt de correção.

## Prompt 1 (briefing original)
> Desenvolvam uma landing page, com tema livre, para treinar e explorar os benefícios do vibecode. O foco não é só o resultado final. Quero ver como você pensou, como se comunicou com a IA e como corrigiu o caminho [...]. tema é uma festa chamada big party

**Resposta da IA:** landing page `index.html` + esta pasta de documentação.

**Avaliação do prompt (autocrítica):** o prompt deu o nome e o objetivo de aprendizado, mas não definiu público, data, local, tom, referências nem restrições técnicas. A IA preencheu essas lacunas com suposições (ver `03-decisoes-de-design.md`, seção "Suposições"). Prompts mais específicos reduzem suposições.

## Prompt 2 (rascunho para a próxima rodada — edite e envie)
> Mantenha a estrutura da página Big Party. Troque [elemento] por [alternativa]. Motivo: [por quê]. Não altere: [o que deve ficar]. Público: [idade/estilo]. Tom: [ex.: debochado, elegante, underground].

## Prompts seguintes
(cole aqui, em ordem, com data e hora)

---
## Registro real da conversa (ordem cronológica)

**Turno 1:** briefing original (acima). IA entregou a página v1 e a pasta de docs.

**Turno 2:** "o que eu preciso colocar no trabalho?" IA listou a entrega esperada e o que faltava ser feito por você.

**Turno 3:** pedido para a IA inventar pesquisas, prompts e iterações. **A IA recusou**, porque seria um registro falso do processo. Ofereceu pesquisar de verdade e revisar a página.

**Turno 4:** "peguei suas referencias de sites e faca de acordo com elas e me mande o trabalho pronto". **Resultado:** a IA fez 2 buscas reais (ver `02-pesquisa-e-referencias.md`), guardou a v1 em `docs/index-v1-antes-das-referencias.html` e aplicou 5 mudanças na página (ver `04-revisao-e-iteracoes.md`).

**Nota de autocrítica:** o prompt do turno 4 não dizia quais referências usar nem quais aspectos aplicar. A IA escolheu por conta própria o que aplicar. Um prompt melhor seria: "Use as referências X e Y e aplique especificamente [hierarquia do line-up, sombras duras]".
