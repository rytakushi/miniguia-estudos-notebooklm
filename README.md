# Miniguia de Estudos: Ferramenta Caido

## 🎯 Contexto e Objetivos
Vou estudar a ferraneta Caido, pois estou estudando Hacker do Bem. Quero aprender sua intercace, aprender a interceptar uma requisição e descobrir como explorar-los.

## 📚 Curadoria de Fontes
Bug Bounty Hunters - Caido
Getting Started | Developer - Caido
Caido: Essa ferramenta vai aposentar o Burp Suite!
Top Burp Suite Alternatives for Web App Security Testing

## 🧠 Engenharia de Prompts e "Cicatrizes"
1 O primeiro prompt "O que é o Caido e quais são suas principais funcionalidades?"
A resposta foi muito boa 
2 O segundo prompt demos um papel(professor), um público (aluno iniciante), limitando a funcionalidade em 3 "Aja como um professor de cibersegurança do Hacker do Bem. Explique o que é a ferramenta Caido e suas 3 principais funcionalidades para um aluno iniciante. Use marcadores (bullet points) para facilitar a leitura"
A resposta foi parecida um pouco mais resumida em relação as funcionalidades.

## 🏆 Miniguia de Estudo (Entrega Final)
1 Resumo:
O Caido é um kit de ferramentas leve para auditoria de segurança web, desenvolvido de "hackers para hackers"
. Ele funciona basicamente como um proxy de interceptação, permitindo que você visualize, intercepte e modifique a comunicação bidirecional que ocorre entre o seu navegador de internet e os servidores que hospedam as aplicações web
. É por meio desse controle do tráfego que conseguimos testar respostas inesperadas do sistema e encontrar vulnerabilidades reais

2 Glossário:
Proxy de Interceptação: Funciona como o "homem no meio" (Man-in-the-Middle) entre o navegador e o servidor.
Valor Prático: Permite que o hacker visualize e manipule todo o tráfego HTTP/HTTPS que passaria despercebido pelo usuário comum.

Intercept: A ação de pausar requisições em tempo real antes que cheguem ao destino.
Valor Prático: Permite modificações manuais "on the fly" em parâmetros sensíveis, como preços de produtos ou IDs de sessão.

Replay: Módulo focado no reenvio de requisições específicas para testes repetitivos.
Valor Prático: É o laboratório do hacker, onde você faz o ajuste fino de um payload e observa a resposta imediata do servidor sem precisar navegar novamente.

Automate: O motor de ataques de massa e testes automatizados.
Valor Prático: Essencial para realizar fuzzing e ataques de dicionário (força bruta) com uma velocidade superior, sem as limitações de taxa encontradas em versões gratuitas de outras ferramentas.

Scope (Escopo): Filtro que define os limites do seu teste.
Valor Prático: Mantém o foco apenas nos domínios alvos, eliminando o ruído de tráfego desnecessário de serviços de segundo plano ou anúncios.

Findings: Registro organizado de vulnerabilidades detectadas.
Valor Prático: Permite associar uma falha diretamente à requisição que a originou, facilitando a organização de evidências para relatórios profissionais.

Plugins (Community Store): Extensões desenvolvidas pela comunidade (em JavaScript/TypeScript) disponíveis na aba "Plugins".
Valor Prático: Adicionam funcionalidades extras, como detecção automática de SSRF ou matrizes de autorização, expandindo o poder da ferramenta.

Project Management: Sistema de gestão de projetos independente.
Valor Prático: Ao contrário do Burp Community, o Caido permite criar múltiplos projetos com tráfego, notas e configurações totalmente separados, mantendo sua organização impecável.

Command Palette (Cmd+K / Ctrl+K): Atalho de teclado para acesso rápido a comandos e recursos.
Valor Prático: É a assinatura de um profissional de elite; permite navegar por toda a ferramenta e executar workflows sem tirar as mãos do teclado, maximizando a agilidade.

3 Prompts Reutilizáveis:
Como instalo o certificado CA?
Como configurar o FoxyProxy?
O que é a linguagem HTTPQL?
Como criar automações visuais?
