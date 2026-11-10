# 🚀 Relatório do Projeto - ATS Boost

> Ferramenta inteligente para análise e otimização de currículos utilizando conceitos de ATS (Applicant Tracking System).

---

# 🎯 1. Qual problema a aplicação resolve

Atualmente, grande parte das empresas utiliza sistemas **ATS (Applicant Tracking System)** para realizar a triagem inicial de currículos antes da análise por recrutadores.

Embora muitos candidatos possuam experiência e qualificações compatíveis com determinadas vagas, seus currículos podem não conter as palavras-chave ou a estrutura esperada pelos sistemas automatizados, reduzindo suas chances de avançar no processo seletivo.

O **ATS Boost** foi desenvolvido para resolver esse problema. A aplicação compara a descrição de uma vaga com o currículo do candidato, identifica o nível de compatibilidade entre ambos e gera uma versão otimizada do currículo, sem criar ou alterar informações que não estejam presentes no documento original.

---

# 🤖 2. Mega Prompt Utilizado e Evoluções

O desenvolvimento do ATS Boost foi conduzido por meio de um **Mega Prompt**, responsável por definir funcionalidades, regras de negócio, fluxo da aplicação e requisitos da interface.

📄 **Prompt completo disponível em:**  
[mega-prompt.md](mega-prompt.md)

## Versão Inicial

A primeira versão do prompt contemplava:

- Landing Page
- Campo para descrição da vaga
- Campo para currículo
- Análise ATS
- Geração de currículo otimizado

### Objetivo

Permitir que o usuário recebesse um score de compatibilidade entre vaga e currículo, além de sugestões de melhoria para aumentar sua aderência aos requisitos da oportunidade.

## Evoluções Implementadas

Ao longo do desenvolvimento, novas funcionalidades foram incorporadas ao projeto.

### 📄 Exportação para PDF

**Motivo:** permitir que o usuário baixasse imediatamente o currículo gerado.

### 📚 Histórico de Análises

**Motivo:** armazenar análises anteriores para consultas futuras.

### 📊 Dashboard Administrativo

**Motivo:** disponibilizar métricas sobre a utilização da plataforma.

**Indicadores implementados:**

- Total de análises realizadas
- Média de Match ATS
- Quantidade de currículos gerados

### 🔍 Palavras-chave Ausentes

**Motivo:** informar quais requisitos presentes na vaga não foram identificados no currículo.

### 🛡️ Aviso de Transparência

**Motivo:** garantir uma utilização ética da ferramenta.

**Mensagem exibida ao usuário:**

> Esta ferramenta melhora a apresentação do currículo, mas nunca adiciona experiências, cargos ou competências que não existam no currículo original.

---

# ⚙️ 3. Como a análise funciona

O processo de análise do ATS Boost é dividido em seis etapas.

## Passo 1 — Inserção da Vaga

O usuário cola a descrição da vaga desejada.

### Exemplo

```text
Desenvolvedor Front-End
React
TypeScript
Docker
AWS
```

Desenvolvedor Front-End

Passo 2 — Inserção do Currículo

O usuário cola seu currículo para análise.

Exemplo
Plain Text
Desenvolvedor Front-End
React
JavaScript
Scrum
Git
 
Passo 3 — Comparação dos Conteúdos

A aplicação analisa ambos os textos e identifica:

Palavras-chave encontradas
Palavras-chave ausentes
Competências alinhadas
Compatibilidade geral
Passo 4 — Cálculo do Match ATS

Com base na análise realizada, é gerado um percentual de compatibilidade.

Exemplo
Plain Text
78% de compatibilidade
Passo 5 — Geração do Diagnóstico

A aplicação apresenta um relatório contendo:

✅ Palavras-chave encontradas
⚠️ Palavras-chave ausentes
📈 Recomendações de melhoria
Passo 6 — Geração do Currículo ATS Friendly

O sistema gera uma nova versão do currículo, reorganizando e destacando informações para melhorar sua aderência aos sistemas ATS.

Importante: nenhuma experiência profissional, competência ou certificação é criada automaticamente. Todo o conteúdo gerado tem como base as informações fornecidas pelo usuário.

🔧 4. Ajustes solicitados após a primeira geração

Após a primeira versão da aplicação, foram realizados diversos refinamentos para melhorar a experiência do usuário e aumentar o valor da solução.

🎨 Ajuste 1 — Melhoria da Interface
Problema

A interface inicial apresentava um visual simples para apresentação do projeto.

Solução

Implementação do Design System shadcn/ui, proporcionando uma aparência mais moderna, profissional e responsiva.

📄 Ajuste 2 — Exportação para PDF
Problema

O usuário precisava copiar manualmente o currículo gerado.

Solução

Criação da funcionalidade de exportação para PDF.

🔍 Ajuste 3 — Exibição de Palavras-chave Ausentes
Problema

Não era possível identificar claramente quais requisitos da vaga estavam faltando.

Solução

Criação da seção Palavras-chave Ausentes.

🗂️ Ajuste 4 — Histórico de Análises
Problema

As análises eram perdidas após o encerramento da sessão.

Solução

Armazenamento das análises utilizando o Lovable Cloud.

🛡️ Ajuste 5 — Reforço da Regra Ética
Problema

Evitar a geração de informações falsas ou enganosas.

Solução

Inclusão de avisos permanentes reforçando que a aplicação apenas reorganiza e aprimora informações existentes.

🌐 5. Endereço da Aplicação Publicada

A aplicação encontra-se disponível no endereço:

🔗 https://pixel-perfect-replay-99565.lovable.app/

✅ Conclusão

O ATS Boost foi desenvolvido com o objetivo de auxiliar candidatos a adaptar seus currículos aos requisitos dos sistemas ATS utilizados por empresas durante processos de recrutamento e seleção.

A solução permite analisar a compatibilidade entre currículo e vaga, identificar oportunidades de melhoria e gerar versões otimizadas de currículos sem comprometer a veracidade das informações apresentadas.

Além de demonstrar a aplicação prática da Inteligência Artificial na resolução de um problema real do mercado de trabalho, o projeto incorpora funcionalidades que agregam valor à experiência do usuário, como geração de currículo ATS Friendly, histórico de análises, exportação em PDF e dashboard administrativo.

Dessa forma, o ATS Boost contribui para aumentar as chances de sucesso dos candidatos em processos seletivos e evidencia o potencial da IA na construção de soluções voltadas à empregabilidade.


Essa versão fica muito bem no GitHub, cria um índice automático na lateral, tem boa leitura e aparência profissional para apresentação acadêmica.
React
JavaScript
Scrum
Git


