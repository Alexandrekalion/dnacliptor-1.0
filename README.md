# DNA Cliptor 1.0

Aplicacao web educacional para simular leitura de QR Code e codigo de barras em atividades de logistica.

## Visao geral

DNA Cliptor 1.0 e uma plataforma educacional com frontend React e backend FastAPI. O projeto oferece uma experiencia de aprendizagem voltada a leitura optica, rastreabilidade, materiais logisticos, atividades de aluno e acompanhamento por professor.

O repositorio combina uma interface web, API, geracao de QR Code, leitura de codigo de barras, historico de atividades e suporte a banco MongoDB ou banco em memoria para desenvolvimento local.

## Problema resolvido

Atividades sobre logistica e rastreabilidade podem ficar abstratas quando explicadas apenas em teoria. Este projeto transforma conceitos de QR Code, codigo de barras e identificacao de materiais em uma experiencia pratica para alunos e professores.

## Publico e contexto de uso

- Professores que querem demonstrar leitura de codigos em atividades praticas.
- Alunos aprendendo conceitos de logistica, estoque e rastreabilidade.
- Projetos educacionais que precisam de uma simulacao web para leitura e acompanhamento.

## Principais funcionalidades confirmadas

- Cadastro e login de aluno/professor.
- Modo de demonstracao identificado no projeto.
- Painel do aluno.
- Painel do professor.
- CRUD de materiais.
- Leitura de QR Code e codigo de barras.
- Geracao de QR Code para materiais e conteudos.
- Registro de leituras e atividades.
- Estatisticas e historico.
- Upload de imagem para geracao de conteudo.
- Exportacao/relatorio identificados nas telas e dependencias.

## Como funciona

O aluno ou professor acessa a aplicacao, utiliza os paineis correspondentes e interage com materiais por meio de QR Code ou codigo de barras. O backend registra usuarios, materiais, leituras e atividades; o frontend apresenta dashboards, historico, geradores e scanners.

## Tecnologias utilizadas

- Python
- FastAPI
- MongoDB
- React
- JavaScript
- Tailwind CSS
- html5-qrcode
- qrcode.react
- jsPDF
- Docker
- Railway e Render identificados por arquivos de deploy

## Arquitetura resumida

- `backend/`: API FastAPI, endpoints, persistencia, uploads e testes.
- `frontend/`: aplicacao React, paginas educacionais, scanners, geradores e componentes.
- `frontend/public/`: assets e versao standalone identificada.
- `test_reports/`: registros historicos de testes.
- `memory/`: documentacao de produto.

## Status

Versao 1.0 em desenvolvimento/manutencao. O projeto tem conteudo suficiente para portfolio educacional, mas deve passar por revisao antes de divulgacao ampla.

## Relacao com outras versoes

Existe um repositorio `dnacliptor-1.9`, mas ele aparece sem conteudo suficiente na listagem atual. Esta versao 1.0 e a base documentavel identificada ate aqui.

## Limitacoes conhecidas

- O uso em producao nao foi confirmado.
- Ha recursos de demonstracao e uploads no repositorio que exigem revisao antes de exposicao publica ampla.
- Algumas informacoes originais eram voltadas a ambiente local e foram reorganizadas aqui como apresentacao de portfolio.

## Participacao no desenvolvimento

O projeto demonstra capacidade de construir uma aplicacao educacional full stack, integrar leitura de codigos, organizar experiencias por perfil de usuario, criar dashboards e transformar processos logisticos em atividades praticas.

## Autoria

Desenvolvido por Michele Santana — Kalion Tecnologia
