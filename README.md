# ATS Boost 🚀

Sistema de análise e otimização de currículos para ATS (Applicant Tracking System).

## 🌐 Aplicação Publicada

https://pixel-perfect-replay-99565.lovable.app/

## 📋 Sobre o Projeto

O ATS Boost é uma aplicação web desenvolvida para auxiliar candidatos a melhorar seus currículos para sistemas ATS (Applicant Tracking System). A ferramenta compara a descrição de uma vaga com o currículo informado pelo usuário, identifica o nível de compatibilidade e gera uma versão otimizada do currículo sem criar informações inexistentes.

---

## 1. Qual problema a aplicação resolve

Atualmente, muitas empresas utilizam sistemas ATS (Applicant Tracking System) para realizar a triagem inicial de currículos antes da análise por recrutadores. Esses sistemas avaliam palavras-chave, competências e requisitos específicos presentes nos currículos enviados pelos candidatos.

Entretanto, candidatos qualificados podem ser eliminados nessa etapa por não apresentarem suas experiências e habilidades de forma alinhada aos critérios utilizados pelos sistemas ATS.

O ATS Boost foi desenvolvido para solucionar esse problema. A aplicação compara automaticamente a descrição de uma vaga com o currículo fornecido pelo usuário, identificando o nível de compatibilidade entre ambos, destacando palavras-chave relevantes, apontando requisitos ausentes e fornecendo recomendações de melhoria.

Além disso, a ferramenta gera uma versão otimizada do currículo, organizada de forma mais adequada para sistemas ATS, sem criar ou inventar experiências, cargos, certificações ou competências inexistentes.

## Estrutura do Projeto


```text
## 📁 Estrutura do Projeto

```text
ATS-Boost/
│
├── README.md        # Documentação principal do projeto
├── mega-prompt.md   # Prompt completo utilizado no desenvolvimento
├── telas.md         # Capturas e descrição das telas da aplicação
└── imagens/         # Imagens utilizadas na documentação

```

## 2. O mega prompt que você usou e o que mudou nele até a versão final

O prompt completo utilizado para desenvolvimento da aplicação ATS Boost está disponível no arquivo abaixo:

➡️ [Mega Prompt Completo](mega-prompt.md)

➡️ [Tela do Aplicativo Completo](telas.md)


Durante o desenvolvimento, o prompt passou por refinamentos para incluir funcionalidades como exportação em PDF, histórico de análises, dashboard administrativo, exibição de palavras-chave ausentes e reforço das regras de transparência e ética na geração do currículo.

## 3. Como a análise funciona, da vaga colada até o currículo ajustado

O processo de análise do ATS Boost ocorre em seis etapas:

### Passo 1 - Inserção da vaga

O usuário cola a descrição completa da vaga desejada no campo de entrada da aplicação.

### Passo 2 - Inserção do currículo

O usuário cola seu currículo atual para análise.

### Passo 3 - Análise comparativa

A aplicação analisa os dois textos e identifica:

- Palavras-chave encontradas;
- Palavras-chave ausentes;
- Competências alinhadas;
- Requisitos da vaga;
- Compatibilidade geral entre vaga e currículo.

### Passo 4 - Cálculo do Match ATS

Com base na comparação realizada, o sistema calcula um percentual de compatibilidade entre o currículo e a vaga.

Exemplo:

```text
Match ATS: 78%

```
## 5. O endereço da aplicação publicada

A aplicação foi publicada utilizando a plataforma Lovable e pode ser acessada pelo endereço abaixo:

🔗 https://pixel-perfect-replay-99565.lovable.app/

A plataforma permite que usuários realizem análises de compatibilidade entre currículos e vagas de emprego, recebam recomendações de melhoria e gerem versões otimizadas para sistemas ATS.

# Conclusão

O ATS Boost foi desenvolvido com o objetivo de auxiliar candidatos a melhorar a compatibilidade de seus currículos com sistemas ATS (Applicant Tracking System), amplamente utilizados nos processos modernos de recrutamento e seleção.

A solução permite analisar a aderência entre uma vaga e um currículo, identificar palavras-chave relevantes, apontar oportunidades de melhoria e gerar uma versão ATS Friendly sem alterar a veracidade das informações fornecidas pelo usuário.

Durante o desenvolvimento, foram incorporados recursos como histórico de análises, exportação em PDF, painel administrativo e mecanismos de transparência para garantir que nenhuma experiência ou competência inexistente fosse adicionada ao currículo.

Como resultado, o projeto demonstra a aplicação prática de Inteligência Artificial na resolução de um problema real do mercado de trabalho, contribuindo para que candidatos apresentem seus currículos de forma mais estratégica e aumentem suas chances de avançar em processos seletivos.
