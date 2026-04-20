# AGENTS.md

Guia para agentes que editam este repositório do relatório AGES.

## 1) Escopo e regra principal

- Este projeto **já tem toda a estrutura criada**. O trabalho é **editar conteúdo existente**, não criar novas partes.
- **Nunca criar** novos capítulos, seções, subseções, sprints, anexos ou arquivos estruturais.
- Em `Atividades`, existem apenas `Sprint 0` a `Sprint 4` em cada AGES. **Nunca criar Sprint 5**.
- A estrutura oficial vem de `main.tex` e dos `index.tex` de cada AGES.

## 2) Estrutura fixa do documento

Ordem do documento (imutável):

1. Pré-textuais (`conteudo/0 - pre/*`)
2. Apresentação da trajetória (`conteudo/1 - apresentacao/apresentacao.tex`)
3. AGES I (`conteudo/2 - ages I/index.tex`)
4. AGES II (`conteudo/3 - ages II/index.tex`)
5. AGES III (`conteudo/4 - ages III/index.tex`)
6. AGES IV (`conteudo/5 - ages IV/index.tex`)
7. Considerações finais (`conteudo/6 - consideracoes/consideracoes.tex`)
8. Referências e apêndices

Estrutura interna fixa por AGES (I, II, III, IV):

- `1 - introducao.tex`
- `2 - desenvolvimento.tex`
- `3 - atividades.tex` (com `sprint 0` a `sprint 4`)
- `4 - conclusao.tex`

## 3) Objetivo deste guia

- Preencher e revisar conteúdo mantendo:
  - sentido acadêmico de cada seção;
  - consistência técnica (arquitetura, banco, stack, processo);
  - voz autoral do aluno (primeira pessoa, tom humano, reflexão real).

## 4) Regras inegociáveis para edição

- **Não alterar a arquitetura documental** (ordem/nomes/numeração das seções).
- **Não adicionar novas sprints**.
- **Não apagar contexto histórico** importante (dificuldades, enchentes, aprendizados, colaboração).
- **Não transformar o texto em linguagem impessoal genérica**.
- **Não inventar fatos técnicos** (tecnologias, decisões, entregas, datas, papéis).
- Ao melhorar texto, priorizar clareza, correção gramatical e fluidez, preservando o conteúdo original.

## 5) O que cada seção deve conter (sem criar novas seções)

### Introdução (`1 - introducao.tex`)

Deve cobrir, de forma objetiva:

- contexto e problema do projeto;
- stakeholders/clientes;
- período de execução;
- professor orientador;
- objetivo do produto.

Tom: mais descritivo e contextual, menos opinativo.

### Desenvolvimento (`2 - desenvolvimento.tex`)

Manter exatamente estas subseções:

1. Repositório do Código Fonte do Projeto
2. Banco de Dados Utilizado
3. Arquitetura Utilizada
4. Protótipos das Telas Desenvolvidas
5. Tecnologias Utilizadas

Em cada uma, descrever decisões e justificativas técnicas com linguagem clara.

### Atividades / Sprints (`3 - atividades.tex` + `sprints/*.tex`)

Cada sprint deve relatar:

- o que foi feito na prática;
- dificuldades/bloqueios reais;
- como foi resolvido;
- resultado da sprint;
- lição aprendida (quando couber).

Estrutura recomendada de narrativa por sprint (em parágrafos corridos):

1. contexto e foco da sprint;
2. tarefas executadas;
3. problemas e solução;
4. fechamento com aprendizado/retrospectiva.

### Conclusão (`4 - conclusao.tex`)

Deve trazer reflexão pessoal sobre:

- atuação técnica e soft skills;
- contribuição ao time;
- autocrítica (o que faltou, o que faria diferente);
- aprendizado acumulado e impacto na trajetória.

### Considerações finais (`conteudo/6 - consideracoes/consideracoes.tex`)

Capítulo de fechamento da trajetória (AGES IV):

- evolução profissional (hard + soft skills);
- visão de Engenharia de Software antes vs. depois;
- lições aprendidas e sugestões de melhoria para AGES.

## 6) Guia da voz do aluno (estilo autoral)

Padrões observados no repositório (seguir):

- escrita em **primeira pessoa** (`eu`, `minha`, `aprendi`, `percebi`, `fiquei responsável`);
- tom humano e honesto, com vulnerabilidade técnica quando necessário;
- equilíbrio entre relato técnico e relato de colaboração com colegas;
- valorização de aprendizado, mentoria, pair programming, desbloqueio do time;
- fechamento frequente com retrospectiva da sprint/projeto.

Como escrever no mesmo tom:

- preferir frases como: `fiquei responsável`, `enfrentei`, `resolvi`, `aprendi`, `percebi`;
- contextualizar dificuldades sem dramatizar;
- explicar decisão técnica + efeito prático no time/projeto;
- manter postura de evolução contínua.

Evitar:

- texto excessivamente robótico ou corporativo;
- jargão vazio sem evidência prática;
- apagar autocrítica e pontos de melhoria.

## 7) Consistência técnica mínima

- Conferir coerência entre seção de tecnologias, banco, arquitetura e sprints.
- Se citar deploy/infra/API/testes, manter alinhamento com o que já foi relatado no AGES II/III.
- Manter nomenclatura consistente de papéis (`AGES I`, `AGES II`, etc.), ferramentas e projetos.

## 8) Estratégia de edição para AGES IV

Como AGES IV está com conteúdo-template em partes, usar AGES I, II e III como referência de:

- profundidade;
- ordem lógica de relato;
- tom pessoal em primeira pessoa;
- nível de detalhe técnico + reflexão.

Sem criar novas estruturas: apenas preencher os arquivos já existentes em:

- `conteudo/5 - ages IV/conteudo/1 - introducao.tex`
- `conteudo/5 - ages IV/conteudo/2 - desenvolvimento.tex`
- `conteudo/5 - ages IV/conteudo/sprints/sprint 0.tex` ... `sprint 4.tex`
- `conteudo/5 - ages IV/conteudo/4 - conclusao.tex`

## 9) Checklist antes de finalizar qualquer edição

- [ ] Estrutura original preservada (sem novas seções/sprints).
- [ ] Texto em primeira pessoa e com tom humano do aluno.
- [ ] Cada seção cobre seu objetivo sem fugir de escopo.
- [ ] Conteúdo técnico coerente com restante do documento.
- [ ] Ortografia, concordância e fluidez revisadas.
- [ ] Sem invenção de fatos, datas ou tecnologias.

---

Se houver dúvida entre "criar algo novo" e "adaptar o que já existe", a regra é:

**sempre adaptar o que já existe.**
