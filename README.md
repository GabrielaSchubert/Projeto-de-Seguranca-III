# Projeto-de-Seguranca-III
## Projeto de segurança III da disciplina de segurança da informação

### 👨‍💻 Equipe

Projeto desenvolvido por 3 alunos da disciplina de Segurança da Informação.

- Github: [Jkvua](https://github.com/Jkvua)
- Github: [GabrielaSchubert](https://github.com/GabrielaSchubert)
- Github: [Sidneckel](https://github.com/Sidneckel) 

### 📌 1.0. Objetivo
Desenvolver uma ferramenta automatizada capaz de realizar um diagnóstico de vulnerabilidades em servidores web utilizando inteligência artificial e automação através do n8n.
A ferramenta realiza automaticamente a coleta de informações do alvo informado pelo usuário, identifica possíveis vulnerabilidades, classifica os riscos encontrados, sugere medidas corretivas e gera um relatório técnico.

#### 📌 1.1. Objetivos Específicos
Automatizar auditorias iniciais de segurança
Identificar configurações inseguras
Detectar problemas relacionados a SSL/TLS
Classificar riscos
Gerar recomendações
Produzir relatório automaticamente

### 📄 2.0. Descrição do Projeto
Esse projeto foi desenvolvido para que o usuário informe a URL do servidor web que deseja analisar. O workflow desenvolvido no n8n inicia automaticamente uma sequência de etapas responsáveis por coletar informações públicas do alvo, enviar os dados para análise utilizando IA, identificar vulnerabilidades relacionadas à configuração do servidor, classificar os riscos encontrados e gerar um relatório final contendo recomendações de mitigação. 

### 🏗️  3.0. Arquitetura da Solução 

![imagem arquitetura](./images/imagem%201.png)

### 🚀 4.0. Fluxograma do Projeto

![imagem fluxo](/images/imagem%20fluxo.png)

### 📊 5.0. Tecnologias Utilizadas

| Tecnologia              | Finalidade                   |
|-------------------------|------------------------------|
| n8n                     | Automação do fluxo           |
| Gemini 2.5 Flash        | Análise das vulnerabilidades |
| HTTP Request            | Coleta de informações        |
| SSL Labs API            | Verificação de SSL           |
| HTML/Gmail              | Geração do relatório         |

### 📚 6.0. Fluxo do Processo
O fluxo do processo deste projeto se apresenta dessa forma:

- Usuário informa o domínio
- O workflow é iniciado
- Coleta de informações do servidor
- Verificação de certificados SSL
- Coleta de cabeçalhos HTTP
- Envio dos dados para IA
- Identificação das vulnerabilidades
- Classificação do risco
- Geração das recomendações
- Geração do relatório

### ✅ 7.0. Protótipo Funcional

#### Workflow completo

![imagem workflow](/images/imagem%201.png)

#### Execução

![imagem execucao](/images/imagem%202.png)

#### Saída do relatório HTML e Gmail

![imagem saida](/images/imagem%203.png)
![imagem saida2](/images/imagem%204.png)

### 🔍 8.0. IA e prompts utilizados
ChatGPT (modelo GPT da OpenAI) - Prompt: “Organize os principais tópicos para distribuir o trabalho ”

### 📑 9.0. Relatório Gerado
Print de exemplo de relatório gerado no n8n

### 🎯 10.0. Resultados
Esta ferramenta conseguiu automatizar o processo de auditoria inicial de segurança, reduzindo o tempo necessário para análise e produzindo relatórios padronizados com auxílio de IA. 

### ⚪ 11.0. Conclusão
O desenvolvimento deste projeto demonstrou que é possível automatizar parte do processo de diagnóstico de vulnerabilidades em servidores web utilizando a plataforma n8n integrada a um modelo de Inteligência Artificial. A solução desenvolvida foi capaz de coletar informações do sistema alvo, analisar configurações relacionadas à segurança, identificar possíveis vulnerabilidades, classificar os riscos encontrados e gerar recomendações de mitigação de forma automatizada.

A utilização da IA contribuiu para tornar a análise mais rápida e organizada, auxiliando na interpretação dos dados coletados e na elaboração de um relatório técnico com informações relevantes 
para a tomada de decisão. Dessa forma, a ferramenta reduz o tempo necessário para uma avaliação inicial de segurança, fornece uma visão estruturada dos principais riscos identificados, é uma ferramenta útil para avaliações preliminares, identifica configurações inadequadas e apoia as atividades de segurança da informação.

### 🔐 12.0. Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
