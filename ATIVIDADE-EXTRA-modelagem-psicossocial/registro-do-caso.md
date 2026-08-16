# Registro do caso — Atividade extra de Modelagem Psicossocial

**Caso:** Atividade extra — Modelagem Psicossocial  
**Atividade:** Modelagem Computacional de Problemas  
**Disciplina:** Introdução à Ciência da Computação  
**Curso:** Bacharelado em Meteorologia — UFCG  
**Professor:** Prof. Dr. Marcelo de Barros  
**Estudante:** Mayra Clara Albuquerque Venâncio dos Santos  

## 1. Natureza do caso

Este caso registra uma atividade de modelagem computacional aplicada a um problema social e de saúde do trabalho: os riscos psicossociais associados à jornada, à pressão, à autonomia, ao apoio organizacional e a outros fatores do ambiente de trabalho.

A atividade se insere na disciplina como exercício de:

- identificação de situação-problema;
- escolha de variáveis numéricas;
- formulação de pergunta matemática;
- construção de modelo matemático simples;
- interpretação de cenário;
- proposição de aplicação computacional.

## 2. Problema trabalhado

O problema central é representar numericamente o risco psicossocial de um trabalhador e permitir simular como mudanças em variáveis do ambiente de trabalho podem alterar esse risco.

O material considera que os riscos psicossociais no trabalho estão associados a fatores como:

- jornadas excessivas;
- pressão por desempenho;
- assédio, violência ou conflitos;
- condições organizacionais inadequadas;
- falta de autonomia;
- baixo apoio organizacional;
- pouca recuperação e descanso.

## 3. Fonte de referência

O material usa como referência o sumário executivo em português do relatório da Organização Internacional do Trabalho sobre ambiente psicossocial de trabalho, publicado em 2026 por ocasião do Dia Mundial da Segurança e Saúde no Trabalho.

Essa referência é tratada como fonte contextual e conceitual para a construção da situação-problema.

## 4. Formulações identificadas

Durante a produção do material aparecem diferentes versões da modelagem.

### Versão com S

```text
S = índice de risco psicossocial
D = demanda de trabalho
P = pressão por desempenho
A = autonomia no trabalho
O = apoio organizacional
```

Estrutura do modelo:

```text
S = (D² + P²) / (A + O)
```

### Versão com R

```text
R = nível de risco psicossocial
H = horas trabalhadas por semana
V = nível de exposição à violência ou assédio
A = nível de apoio organizacional
C = qualidade das condições de trabalho
```

Estrutura do modelo:

```text
R = (H² + V²) / (A + C)
```

## 5. Interpretação computacional

A modelagem permite transformar uma situação social complexa em uma estrutura computável.

A ideia de aplicação é uma calculadora ou teste interativo que:

1. apresenta perguntas ao trabalhador;
2. converte respostas em valores numéricos;
3. calcula um índice de risco;
4. classifica o resultado;
5. permite simular mudanças em fatores de risco e proteção.

## 6. Relação com pensamento computacional

O caso mobiliza elementos centrais da disciplina:

- decomposição de um problema real;
- identificação de entradas;
- definição de variáveis;
- criação de regra de cálculo;
- interpretação de saída;
- possibilidade de implementação em ferramenta computacional;
- reflexão sobre limites da simulação.

## 7. Limites da modelagem

A atividade assume caráter educativo e preventivo.

O modelo não deve ser interpretado como diagnóstico médico, psicológico, jurídico ou profissional.

A simulação serve para:

- tornar visíveis fatores de risco;
- apoiar reflexão inicial;
- mostrar relações entre variáveis;
- indicar como apoio organizacional, autonomia e descanso podem reduzir risco;
- demonstrar como ferramentas computacionais podem apoiar análise de problemas reais.

## 8. Relação com outros materiais da disciplina

Este caso dialoga com:

- roteiros de modelagem computacional;
- FelizCidade e problemas sociais mediados por computação;
- atividades de criação de ferramentas educativas;
- possíveis protótipos de InfoGene ou AdverGame;
- uso de variáveis e modelos para representar problemas do mundo real.

## 9. Decisões pendentes

- Escolher qual versão do modelo será tratada como versão principal.
- Decidir se o caso terá uma página pública com a calculadora ou apenas documentação conceitual.
- Avaliar se `InfoGene_AdverGame.html` entra como protótipo relacionado ao caso.
- Selecionar trechos autorais que podem ser publicados sem reproduzir indevidamente material de aula ou de terceiros.
- Decidir se haverá uma implementação futura em HTML, JavaScript, Python ou MIT App Inventor.

## 10. Status de publicação

Este registro é público e curado.

Arquivos brutos, versões intermediárias e materiais de terceiros devem permanecer fora do repositório público, salvo curadoria e autorização específica.
