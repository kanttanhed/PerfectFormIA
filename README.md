# PerfectFormIA
<p align="center">
  <img src="/PerfectFormLogo.png" width="600" alt="Descrição da imagem"></p>

## PerfectFormIA - Fluxo do Negócio
 <p> <img src="/PerfectFormArquitetura.png" width="600" alt="Descrição da imagem"></p>

## 🚧 Roadmap de Desenvolvimento (8 Semanas)
### Semana 1: Planejamento e Setup do Projeto
- Definir requisitos do MVP (ex: 3 exercícios principais: agachamento, flexão, abdominal)
- Criar repositórios (GitHub/GitLab)
- Configurar ambiente de desenvolvimento (Docker, Node/Java, React Native)
- Setup do banco PostgreSQL com Docker
- Setup de autenticação (Firebase Auth)

## Semana 2: Base do App e Backend
- Criar telas iniciais: login, cadastro, dashboard
- Criar backend com Spring Boot:
- Endpoints de usuários
- Registro de treino
- Histórico de correções

Deploy inicial no Heroku ou AWS (EC2)

## Semana 3: Integração de IA no Frontend
- Integrar MediaPipe ou MoveNet com React Native
- Captura de movimentos com câmera
- Exibir pontos do corpo na tela (esqueleto)
- Salvar execuções para testes

## Semana 4: Lógica de Correção Básica
- Implementar regras simples:
- Verificação de ângulo (ex: joelhos em agachamento)
- Feedback em tempo real (texto/áudio)
- Criar modelo inicial de IA simples com Python (offline)

## Semana 5: IA como Serviço
- Criar API em Python (FastAPI) para correção de postura
- Integrar backend Java → Python API (via HTTP ou gRPC)
- Enviar dados de postura do frontend para análise no backend

## Semana 6: Histórico e Feedback
- Tela de histórico de treinos e correções
- Ranking de desempenho
- Enviar resumo para usuário (ex: "Hoje você corrigiu 3 execuções!")

## Semana 7: Estabilização e Testes
- Testes unitários e de integração
- Melhoria da UX e correções de bugs
- Analytics com Firebase ou Mixpanel

## Semana 8: Lançamento MVP + Monitoramento
- Deploy final (app + backend + IA)
- Configurar observabilidade (logs + métricas)
- Estratégia de onboarding para primeiros usuários
- Coletar feedback real
