# CASO-02 — Atividade de Modelagem Psicossocial

**Estado:** caso em organização  
**Disciplina:** Introdução à Ciência da Computação  
**Curso:** Bacharelado em Meteorologia — UFCG  
**Professor:** Prof. Dr. Marcelo de Barros  
**Estudante:** Mayra Clara Albuquerque Venâncio dos Santos  
**Atividade:** Atividade 2 — Modelagem Computacional de Problemas  
**Nome público do caso:** Atividade de Modelagem Psicossocial  

## 1. Síntese

Este caso registra a **Atividade de Modelagem Psicossocial**, desenvolvida na disciplina **Introdução à Ciência da Computação**.

A atividade teve como foco representar o risco psicossocial no trabalho por meio de variáveis numéricas, construir um modelo matemático simples e propor uma aplicação computacional educativa capaz de simular cenários de risco a partir de condições de trabalho.

Tema registrado nos materiais:

```text
Calculando os riscos psicossociais da sua jornada de trabalho
```

## 2. Situação-problema

Os materiais partem da discussão sobre riscos psicossociais no trabalho como ameaça à saúde dos trabalhadores e ao desempenho das organizações.

Entre os fatores citados aparecem:

- jornadas de trabalho excessivas;
- exposição a situações de violência, assédio e bullying;
- condições organizacionais inadequadas;
- pressão por desempenho;
- baixa autonomia;
- pouco apoio organizacional;
- descanso insuficiente.

A pergunta geral da atividade pode ser sintetizada assim:

```text
Como representar o risco psicossocial de um trabalhador por meio de uma variável numérica e, a partir disso, construir uma ferramenta que permita simular diferentes níveis de risco com base nas condições de trabalho?
```

## 3. Perfil considerado

A atividade considera trabalhadores em geral, especialmente aqueles que apresentam sinais de desgaste físico e/ou mental.

Em algumas versões do material, o perfil é descrito como trabalhador que:

- possui jornada superior a 40 horas semanais;
- enfrenta pressão no ambiente de trabalho;
- pode estar exposto a conflitos, violência ou assédio;
- possui pouca autonomia;
- recebe pouco apoio organizacional;
- apresenta sinais de desgaste físico e mental.

## 4. Variável principal

A variável central representa o risco psicossocial.

Nos materiais aparecem formulações como:

```text
S = índice de risco psicossocial
```

ou:

```text
R = nível de risco psicossocial
```

A diferença de notação será preservada nos registros do processo, mas a interpretação geral é a mesma: representar numericamente o nível de risco associado às condições psicossociais do trabalho.

## 5. Variáveis que afetam o problema

### Variáveis que aumentam o risco

- demanda de trabalho;
- pressão por desempenho;
- horas trabalhadas por semana;
- exposição a violência, conflitos ou assédio;
- carga de trabalho.

### Variáveis que diminuem o risco

- autonomia no trabalho;
- apoio organizacional;
- clareza das funções;
- qualidade das condições de trabalho;
- descanso e recuperação.

## 6. Pergunta matemática

Uma das formulações registradas nos materiais é:

```text
Qual deve ser o nível de apoio organizacional necessário para que o índice de risco psicossocial permaneça abaixo de um valor aceitável, considerando altos níveis de demanda e pressão no trabalho?
```

Outra formulação trabalha com a pergunta sobre como manter o risco psicossocial em nível aceitável considerando jornadas longas e exposição a situações de risco.

## 7. Modelo matemático

Os materiais apresentam diferentes versões de modelo, todas com a mesma estrutura conceitual:

```text
risco = fatores que aumentam o risco / fatores que reduzem o risco
```

Exemplo de estrutura:

```text
S = (D² + P²) / (A + O)
```

Em que:

- `S` é o índice de risco psicossocial;
- `D` é a demanda de trabalho;
- `P` é a pressão por desempenho;
- `A` é a autonomia no trabalho;
- `O` é o apoio organizacional.

Outra versão usa:

```text
R = (H² + V²) / (A + C)
```

Em que:

- `R` é o nível de risco psicossocial;
- `H` é o número de horas trabalhadas por semana;
- `V` é o nível de exposição à violência ou assédio;
- `A` é o nível de apoio organizacional;
- `C` é a qualidade das condições de trabalho.

## 8. Cenário de simulação

A atividade propõe inserir valores numéricos nas variáveis para observar como o risco se altera quando fatores de proteção aumentam ou fatores de risco diminuem.

Interpretação geral registrada:

```text
Quando o apoio organizacional é baixo, o risco assume valores elevados.
Quando o apoio organizacional aumenta, o risco diminui.
```

## 9. Aplicação computacional proposta

A solução proposta é uma **calculadora de risco psicossocial**, estruturada como teste interativo.

A aplicação poderia:

- receber respostas sobre carga de trabalho, pressão, autonomia e apoio organizacional;
- converter respostas em valores numéricos;
- calcular o índice ou nível de risco psicossocial;
- apresentar uma classificação interpretativa;
- permitir simulação de cenários;
- mostrar como mudanças nas condições de trabalho podem reduzir ou aumentar o risco.

Observação importante:

```text
A ferramenta possui caráter educativo e não substitui avaliação médica, psicológica ou profissional.
```

## 10. Materiais relacionados

Materiais identificados na pasta da disciplina:

| Material | Função |
|---|---|
| `Missão Ajudar 1.pdf` | roteiro/folha de avaliação ou orientação ligada à criação/otimização de jogo |
| `modelagem_psicossocial_mayra_clara.pdf` | versão em PDF da atividade de modelagem psicossocial |
| `modelagem_psicossocial_mayra_clara_v3.pdf` | versão posterior da modelagem psicossocial |
| `modelagem_risco_psicossocial_v1.docx` | versão editável inicial |
| `modelagem_risco_psicossocial_v2.docx` | versão editável posterior |
| `Roteiro Modelagem Computacional 2026.pdf` | roteiro da atividade de modelagem computacional |
| `Executive Summary SafeDay2026 Portuguese O ambiente psicossocial de trabalho.pdf` | referência principal da OIT sobre ambiente psicossocial de trabalho |
| `InfoGene_AdverGame.html` | protótipo ou referência de jogo/interação com indicador de risco |

## 11. Referência principal

A referência principal registrada nos materiais é o sumário executivo da Organização Internacional do Trabalho sobre ambiente psicossocial de trabalho, preparado por ocasião do Dia Mundial da Segurança e Saúde no Trabalho de 2026.

## 12. Status

Estado atual:

```text
caso identificado
+ materiais localizados
+ README inicial criado
+ registro do caso em preparação
```

Próximas ações:

- revisar os materiais da Atividade de Modelagem Psicossocial;
- decidir quais versões serão apenas referenciadas;
- selecionar uma formulação principal do modelo matemático;
- registrar a aplicação computacional proposta;
- avaliar se `InfoGene_AdverGame.html` deve ser tratado como protótipo, referência ou material relacionado;
- manter materiais de terceiros e arquivos brutos fora do repositório público, salvo autorização específica.
