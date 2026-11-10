##Mega Promt

# ATS Boost
Crie uma aplicação web completa chamada ATS Boost.
## Objetivo
ATS Boost é uma ferramenta que ajuda candidatos a melhorar seus currículos para sistemas ATS (Applicant Tracking System).
A aplicação deve comparar uma descrição de vaga com um currículo fornecido pelo usuário e gerar:
- Percentual de compatibilidade (Match ATS)
- Palavras-chave encontradas
- Palavras-chave ausentes
- Sugestões de melhoria
- Nova versão ATS Friendly do currículo
## Regra Fundamental
A aplicação NUNCA deve inventar experiências, cargos, certificações, projetos, tecnologias ou competências que não existam no currículo original.
Ela pode apenas:
- Reorganizar conteúdo
- Melhorar a redação
- Destacar palavras-chave existentes
- Reestruturar informações
- Ajustar a apresentação do currículo
Exibir essa observação de forma visível na interface:
"Esta ferramenta melhora a apresentação do currículo, mas nunca adiciona experiências ou competências inexistentes."
---
# Design System
Utilizar shadcn/ui em toda a aplicação.
## Estilo Visual
- Moderno
- Profissional
- Minimalista
- Inspirado em LinkedIn
- Mobile First
- Interface limpa
- Foco em legibilidade
## Paleta de Cores
### Primária
2563EB
## Sucesso
22C55E
## Atenção
F59E0B
## Fundo
FFFFFF
## Fundo Secundário
F8FAFC
## Texto
0F172A
## Bordas
E2E8F0
---
# Estrutura de Navegação
Criar menu superior responsivo.
Itens:
- Início
- Como Funciona
- Analisar Currículo
- Painel Administrativo
---
# Landing Page:
 Hero Section
Título:
"Passe pelos filtros ATS e aumente suas chances de entrevista."

Subtítulo:
Compare seu currículo com uma vaga, descubra o que está faltando e gere uma versão otimizada em segundos.
Botão principal:
Analisar Meu Currículo
Botão secundário:
Como Funciona
---
## Seção Como Funciona
Etapa 1
Cole a descrição da vaga.
Etapa 2
Cole seu currículo.
Etapa 3
Receba o diagnóstico ATS.
Etapa 4
Gere uma versão otimizada.
---
## Benefícios
Criar cards.
Card 1
Match ATS instantâneo.
Card 2
Identificação de palavras-chave.
Card 3
Sugestões de melhoria.
Card 4
Currículo ATS Friendly.
---
## FAQ
Perguntas:
- O sistema inventa experiências?
- Como funciona o score ATS?
- Posso exportar o currículo?
- Os dados ficam salvos?
---
# Página de Análise
 Formulário Principal
Campo 1
Descrição da vaga
Tipo:
Textarea grande
Placeholder:
"Cole aqui a descrição da vaga..."
---
Campo 2
Currículo
Tipo:
Textarea grande
Placeholder:
"Cole aqui seu currículo..."
---
Botão principal
"Analisar Currículo"
---
# Resultado da Análise
Exibir em cards.
## Score ATS
Mostrar percentual.
Exemplo:
82%
Adicionar barra de progresso.
---
## Palavras-chave Encontradas
Exibir como badges verdes.
Exemplo:
- React
- JavaScript
- Scrum
- SQL
---
## Palavras-chave Ausentes
Exibir como badges amarelas.
Exemplo:
- AWS
- Docker
- CI/CD
---
## Recomendações
Gerar lista de melhorias.
Exemplo:
- Destacar projetos relevantes.
- Melhorar o resumo profissional.
- Evidenciar experiência com metodologias ágeis.
---
## Currículo ATS Friendly

Gerar nova versão do currículo.
Exibir em área formatada.
Inserir observação:
"Todas as informações presentes nesta versão foram extraídas do currículo original."
---
## Exportação
Adicionar botão:
"Exportar Currículo"
Gerar PDF.
---
# Histórico de Análises
Salvar análises no Lovable Cloud.
Exibir:
- Data
- Match ATS
- Vaga analisada
- Currículo gerado
Permitir visualizar análises anteriores.
---
# Painel Administrativo
Criar painel administrativo.
Menu lateral.
---
## Dashboard
Mostrar indicadores:
- Total de análises
- Usuários cadastrados
- Currículos gerados
- Média de Match ATS
---
## Análises
Tabela com:
- Data
- Match
- Status
- Currículo
---
## Estatísticas
Mostrar:
- Match médio
- Palavras-chave mais encontradas
- Palavras-chave mais ausentes
---
## Feedbacks
Tabela de feedback dos usuários.
---
# Responsividade
Criar experiência completa para:
- Smartphones
- Tablets
- Desktop
---
# Backend
Utilizar exclusivamente Lovable Cloud.
Não utilizar banco de dados externo.
---
# Resultado Esperado
Aplicação pronta para produção contendo:
- Landing Page
- Ferramenta de comparação ATS
- Geração de currículo ATS Friendly
- Exportação para PDF
- Histórico de análises
- Dashboard administrativo
- Interface moderna usando shadcn/ui
- Layout responsivo

Esse projeto costuma ficar muito forte para apresentação porque demonstra:
•	IA aplicada a um problema real;
•	análise de texto;
•	geração de conteúdo;
•	dashboard administrativo;
•	foco em empregabilidade e RH, que é uma dor real do mercado.

Pronto — a entrada está liberada. Agora vá em "Não tem conta? Cadastre-se", crie sua conta e você entra na hora, sem precisar abrir e-mail de confirmação. Como você será o primeiro cadastro, já vira administrador e o painel abre para você.
Também deixei as mensagens de erro em português: se alguém tentar entrar sem conta, aparece o aviso para se cadastrar. Testei isso na tela e está funcionando.
Sobre os e-mails de verdade: para os e-mails de confirmação e de redefinição de senha chegarem, o app precisa enviar a partir de um domínio seu (ex.: notify@suadomain.com.br) — um @gmail.com não pode ser verificado. Se você não tem um domínio, dá para comprar um dentro do projeto (Configurações → Domínios → Comprar novo domínio).
Dois avisos sobre o que mudei:
•	A confirmação de e-mail está desligada, então qualquer pessoa com o link do app consegue criar conta sem provar que o e-mail é dela. Posso religar quando você quiser.
•	A checagem de senhas já vazadas ficou desligada (padrão). Me avisa se quiser ligar.
Para configurar seu domínio de e-mail:
