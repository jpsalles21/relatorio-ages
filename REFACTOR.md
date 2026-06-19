# REFACTOR.md

Guia para refatorar o conteúdo da AGES I e da AGES II sem alterar a estrutura do relatório.

## Objetivo

Este arquivo orienta a revisão e melhoria textual da AGES I e da AGES II. A refatoração deve melhorar clareza, profundidade, coerência técnica, formatação acadêmica e voz autoral, sem criar novas partes no documento.

Use AGES III e AGES IV como base de comparação para avaliar se o conteúdo da AGES I e da AGES II está suficientemente completo, bem explicado e consistente. A ideia não é copiar o nível técnico ou os fatos dessas etapas, mas usar a qualidade do relato, a organização e a profundidade como referência.

## Regras principais

- Não criar novos capítulos, seções, subseções, sprints, anexos ou arquivos estruturais.
- Não criar Sprint 5. Em cada AGES existem apenas Sprint 0, Sprint 1, Sprint 2, Sprint 3 e Sprint 4.
- Não alterar a ordem oficial definida por `main.tex` e pelos `index.tex` de cada AGES.
- Não apagar contexto histórico importante, como dificuldades, limitações, aprendizados, colaboração e evolução técnica.
- Não transformar o texto em linguagem impessoal genérica. O relatório deve permanecer em primeira pessoa.
- Não inventar fatos técnicos, tecnologias, decisões, datas, entregas, responsabilidades ou participantes.
- Se existir uma seção, ela precisa ser preenchida de forma adequada, mesmo que o aluno não tenha atuado diretamente naquela área.
- Ao revisar, priorizar clareza, correção gramatical, fluidez e coerência com o restante do relatório.

## Referência de qualidade

Ao revisar AGES I e AGES II, comparar com AGES III e AGES IV observando:

- profundidade dos relatos de sprint;
- presença de contexto antes das decisões técnicas;
- explicação das dificuldades e soluções adotadas;
- conexão entre tarefas individuais e resultado do projeto;
- uso consistente da primeira pessoa;
- explicação das tecnologias, banco de dados, arquitetura e protótipos;
- qualidade das conclusões e reflexões pessoais.

A comparação deve considerar a maturidade esperada em cada etapa. AGES I não precisa parecer tecnicamente tão madura quanto AGES III ou IV, mas não pode ficar rasa, incompleta ou sem explicação das seções obrigatórias.

## Orientações para AGES I

Na AGES I, o aluno deve aparecer principalmente como uma pessoa iniciante atuando como desenvolvedor. O texto deve refletir aprendizado, adaptação ao processo, contato inicial com práticas de Engenharia de Software e evolução ao longo das sprints.

Pontos esperados:

- relatar atuação prática como desenvolvedor iniciante;
- explicar dificuldades técnicas de forma honesta e proporcional ao momento da trajetória;
- mostrar aprendizado com colegas, professor, cliente, revisão de código e organização do time;
- evitar exigir ou inserir decisões técnicas muito avançadas que não façam sentido para AGES I;
- ainda assim, preencher adequadamente as seções técnicas existentes;
- incluir informações sobre banco de dados na seção correta, mesmo que o aluno não tenha sido o principal responsável por essa parte;
- explicar o banco de dados de forma simples, descrevendo seu papel na aplicação e como ele se relacionava com o produto desenvolvido.

## Orientações para AGES II

Na AGES II, o texto deve demonstrar maior maturidade em relação à AGES I. O aluno já deve conseguir explicar melhor o funcionamento técnico da aplicação, especialmente o banco de dados.

Pontos esperados:

- apresentar entendimento claro sobre o banco de dados utilizado pela aplicação;
- explicar, na seção adequada, por que o banco foi usado e qual era seu papel no sistema;
- relacionar banco de dados, arquitetura, tecnologias e funcionalidades desenvolvidas;
- detalhar melhor as responsabilidades individuais nas sprints;
- mostrar dificuldades técnicas e decisões tomadas com mais profundidade do que na AGES I;
- manter coerência com o que já aparece no restante do relatório;
- evitar descrições genéricas que poderiam servir para qualquer projeto.

## Sprints e atividades

Os relatos de sprint da AGES I e da AGES II não podem ser minúsculos ou superficiais. Cada sprint deve ter conteúdo suficiente para o leitor entender o que aconteceu, qual foi a participação individual do aluno e o que foi aprendido.

Cada sprint deve cobrir, em parágrafos corridos quando possível:

- contexto e foco da sprint;
- tarefas executadas pelo aluno;
- dificuldades, bloqueios ou limitações reais;
- como os problemas foram resolvidos ou contornados;
- resultado obtido na sprint;
- aprendizados técnicos ou comportamentais.

Evitar relatos que digam apenas que o time desenvolveu funcionalidades. A seção “Atividades desempenhadas pelo aluno” precisa tratar das tarefas individuais do aluno, não somente das tarefas gerais do grupo ou do AGES.

## Seções obrigatórias não podem ser ignoradas

Mesmo que o aluno não tenha atuado diretamente em uma área, a seção correspondente precisa existir com conteúdo útil e verdadeiro. Exemplos:

- se existe seção de banco de dados, explicar o banco utilizado, sua função no projeto e o que o aluno entendeu sobre ele;
- se existe seção de arquitetura, descrever a arquitetura adotada e como as partes principais se conectavam;
- se existe seção de tecnologias, citar as tecnologias usadas com breve apresentação;
- se existe seção de protótipos, comentar os protótipos e sua relação com o desenvolvimento das telas;
- se existe seção de repositório, explicar onde o código foi organizado e como o time utilizou versionamento.

Não usar a falta de atuação direta como motivo para deixar uma seção vazia, vaga ou ignorada.

## Checklist de revisão

Use este checklist ao revisar AGES I e AGES II.

### Figuras e tabelas

1. [ ] O relatório possui figura do banco de dados, e não apenas link para o Figma ou outra ferramenta.
2. [ ] O relatório possui figura da arquitetura da aplicação, e não apenas link externo.
3. [ ] O relatório possui figuras dos protótipos de telas, e não apenas link para o Figma.
4. [ ] As figuras e tabelas são anunciadas antes de aparecerem no texto. Exemplo: “A Figura 1 apresenta...”.
5. [ ] Toda figura ou tabela possui um texto que a explique para o leitor.
6. [ ] O nome da figura aparece logo abaixo da figura. Exemplo: “Figura 1 - Foto da loja tal”.
7. [ ] Todas as figuras e tabelas possuem legenda, numeração e texto explicativo resumido.
8. [ ] A numeração das figuras e tabelas segue a forma núm1.núm2, em que núm1 representa o número do capítulo e núm2 representa o número sequencial da figura no capítulo.
9. [ ] Todas as figuras e tabelas estão referenciadas no texto.
10. [ ] Todas as figuras aparecem na Lista de figuras.
11. [ ] Todas as tabelas aparecem na Lista de tabelas.

### Conteúdo

12. [ ] O professor orientador é citado.
13. [ ] Os stakeholders são citados.
14. [ ] O relatório apresenta a foto do time com o stakeholder, quando essa evidência existir no projeto.
15. [ ] O relatório descreve o processo de desenvolvimento utilizado.
16. [ ] As tecnologias utilizadas são citadas com uma breve apresentação.
17. [ ] A seção “Atividades desempenhadas pelo aluno” trata das tarefas individuais do aluno.
18. [ ] A seção “Atividades desempenhadas pelo aluno” não se limita às tarefas do time ou do AGES como um todo.
19. [ ] A seção “Atividades desempenhadas pelo aluno” apresenta dificuldades enfrentadas.
20. [ ] A seção “Atividades desempenhadas pelo aluno” apresenta lições aprendidas.
21. [ ] O relatório tem uma conclusão final, e não apenas conclusões individuais de cada projeto.
22. [ ] As seções de banco de dados, arquitetura, tecnologias, protótipos e repositório estão preenchidas com conteúdo adequado.
23. [ ] O conteúdo técnico está coerente entre introdução, desenvolvimento, sprints e conclusão.

### Apresentação

24. [ ] O texto possui concordância gramatical de grau, gênero e número.
25. [ ] O texto está escrito em forma pessoal, usando primeira pessoa.
26. [ ] O tipo de letra está consistente durante todo o texto.
27. [ ] O tamanho das letras está consistente durante todo o texto.
28. [ ] O espaçamento vertical entre parágrafos está consistente durante todo o trabalho.
29. [ ] O alinhamento horizontal está consistente durante todo o trabalho.
30. [ ] A formatação de nomes de capítulos, subcapítulos, seções, subseções e itens está consistente durante todo o texto.
31. [ ] Foi realizada uma verificação ortográfica no texto.
32. [ ] Toda abreviatura ou sigla, na primeira vez em que aparece no texto, está escrita por extenso.
33. [ ] Todas as abreviaturas e siglas aparecem na Lista de abreviaturas, quando aplicável.
34. [ ] Todas as abreviaturas e siglas listadas estão referenciadas no texto.

### Bibliografia

35. [ ] Todas as referências estão no padrão ABNT.
36. [ ] Todas as referências indicadas na bibliografia aparecem no texto.
37. [ ] Todas as referências que aparecem no texto estão indicadas na bibliografia.
38. [ ] As referências estão ordenadas alfabeticamente.

## Critérios de aceite da refatoração

A refatoração da AGES I e da AGES II só deve ser considerada concluída quando:

- a estrutura original estiver preservada;
- nenhuma nova sprint ou seção tiver sido criada;
- os relatos de sprint tiverem profundidade suficiente;
- as seções técnicas obrigatórias estiverem preenchidas;
- AGES I refletir uma atuação mais iniciante, mas ainda completa;
- AGES II demonstrar entendimento claro sobre o banco de dados da aplicação;
- o texto estiver em primeira pessoa, com tom humano e autoral;
- o conteúdo estiver coerente com AGES III, AGES IV e com o restante do relatório;
- figuras, tabelas, referências, siglas e bibliografia tiverem sido verificadas conforme o checklist;
- não houver fatos inventados ou extrapolações sem base no conteúdo existente.

Se houver dúvida entre criar conteúdo novo e adaptar o que já existe, adaptar o conteúdo existente.
