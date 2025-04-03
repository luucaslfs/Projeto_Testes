# Prompts para Pesquisa sobre Testes de API REST com LLMs

## Orientação Geral

Todos os prompts seguem um padrão comum:
1. Extrair informações relevantes sem exigir que o artigo responda diretamente à questão
2. Focar na coleta de dados brutos para posterior consolidação
3. Capturar qualquer menção, mesmo tangencial, relacionada à questão
4. Fornecer formato estruturado para facilitar a posterior consolidação

---

# Prompts Revisados para Revisão Sistemática

## Prompt para Questão 1

```
Você é um assistente de pesquisa especializado em testes de software com LLMs.

Extraia informações sobre a eficácia de testes gerados por LLMs para APIs REST em diferentes contextos:

1. CONTEXTOS E DOMÍNIOS:
   - Quais domínios foram testados? Houve diferenças de resultados entre eles?
   - O artigo menciona variações de desempenho entre diferentes tipos de aplicação?

2. ESCALA E COMPLEXIDADE:
   - O artigo aborda APIs de diferentes tamanhos ou complexidades?
   - Existe correlação entre tamanho/complexidade da API e eficácia dos testes?

3. MÉTRICAS E RESULTADOS:
   - Quais métricas mediram a eficácia? Há resultados quantitativos?
   - Existem comparações de desempenho entre diferentes contextos?

Para cada ponto, forneça:
- Dados concretos (números quando disponíveis)
- Citações relevantes (página/seção)
- Indique claramente quando um ponto não é abordado

Se o artigo não contiver informações relevantes, responda apenas: "O artigo não contém informações sobre eficácia de testes LLM para APIs REST em diferentes contextos."
```

## Prompt para Questão 2

```
Você é um assistente de pesquisa especializado em testes de software com LLMs.

Extraia informações sobre fatores contextuais que influenciam o sucesso de testes LLM para APIs REST:

1. FATORES DE DOMÍNIO E API:
   - O artigo menciona como domínios específicos afetam resultados?
   - Como tamanho, estrutura ou complexidade da API impactam a eficácia?

2. ESPECIFICAÇÃO E DESIGN:
   - Como a qualidade da documentação/contrato da API afeta os resultados?
   - São mencionados padrões de design ou arquitetura que influenciam o sucesso?

3. OUTROS FATORES:
   - Há menção a fatores organizacionais, técnicos ou processuais?
   - O artigo identifica pré-requisitos ou condições que afetam resultados?

Para cada ponto, forneça:
- Dados concretos (números quando disponíveis)
- Citações relevantes (página/seção)
- Indique claramente quando um ponto não é abordado

Se o artigo não contiver informações relevantes, responda apenas: "O artigo não contém informações sobre fatores contextuais que influenciam testes LLM para APIs REST."
```

## Prompt para Questão 3

```
Você é um assistente de pesquisa especializado em testes de software com LLMs.

Extraia informações sobre práticas e lições na implementação de testes LLM para APIs REST:

1. PRÁTICAS E PADRÕES:
   - Quais práticas são recomendadas? Há abordagens metodológicas específicas?
   - O artigo descreve padrões de implementação ou integração?

2. DESAFIOS E SOLUÇÕES:
   - Quais problemas foram encontrados e como foram superados?
   - Há menção a tentativas que falharam e por quê?

3. LIÇÕES E LIMITAÇÕES:
   - Quais insights ou lições são explicitamente mencionados?
   - Quais limitações ou casos de uso inadequados são identificados?

Para cada ponto, forneça:
- Dados concretos (números quando disponíveis)
- Citações relevantes (página/seção)
- Indique claramente quando um ponto não é abordado

Se o artigo não contiver informações relevantes, responda apenas: "O artigo não contém informações sobre práticas ou lições em implementações de testes LLM para APIs REST."
```

## Prompt para Questão 4

```
Você é um assistente de pesquisa especializado em testes de software com LLMs.

Extraia informações sobre comparações entre ferramentas/abordagens LLM para testes de APIs REST:

1. MODELOS E ABORDAGENS:
   - Quais modelos LLM específicos são mencionados/utilizados?
   - O artigo descreve técnicas de prompting ou variações de abordagem?

2. FERRAMENTAS E COMPARAÇÕES:
   - Quais ferramentas ou frameworks são descritos?
   - O artigo compara diferentes LLMs ou abordagens? Com quais métricas?

3. VANTAGENS E LIMITAÇÕES:
   - Quais pontos fortes/fracos de diferentes abordagens são mencionados?
   - Há recomendações sobre quando usar cada abordagem?

Para cada ponto, forneça:
- Dados concretos (números quando disponíveis)
- Citações relevantes (página/seção)
- Indique claramente quando um ponto não é abordado

Se o artigo não contiver informações relevantes, responda apenas: "O artigo não contém informações comparando diferentes ferramentas ou abordagens LLM para testes de APIs REST."
```

## Prompt para Questão 5

```
Você é um assistente de pesquisa especializado em testes de software com LLMs.

Extraia informações sobre comparações entre testes LLM e testes manuais/outras ferramentas:

1. COMPARAÇÕES:
   - O artigo compara testes LLM com testes manuais ou outras ferramentas automatizadas?
   - Quais métricas são usadas nestas comparações? Há resultados quantitativos?

2. PONTOS FORTES E FRACOS:
   - Em que cenários os testes LLM superaram outras abordagens?
   - Em que cenários outras abordagens superaram os testes LLM?

3. CUSTO-BENEFÍCIO:
   - O artigo analisa aspectos de custo, tempo, esforço ou escalabilidade?
   - São mencionados trade-offs entre diferentes abordagens?

Para cada ponto, forneça:
- Dados concretos (números quando disponíveis)
- Citações relevantes (página/seção)
- Indique claramente quando um ponto não é abordado

Se o artigo não contiver informações relevantes, responda apenas: "O artigo não contém informações comparando testes LLM com testes manuais ou outras ferramentas."
```