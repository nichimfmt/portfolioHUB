# 🌐 PortfolioHUB + IA GEMINI

Este repositório contém a implantação oficial do **PortfolioHUB**, uma plataforma centralizada para exibir e gerenciar meus projetos digitais e evolução acadêmica[cite: 3]. Este projeto foi desenvolvido como o Desafio - Entrega Final da disciplina de Bootcamp do 1º período de Engenharia de Software[cite: 3].

🔗 **Portfólio em Produção:** [Acesse o site aqui](https://nichimfmt.github.io/portfolioHUB/)[cite: 2]
📺 **Apresentação no YouTube:** [Assista ao vídeo explicativo](https://youtu.be/8eQBLfJMebQ)[cite: 2]
💼 **Meu Perfil Profissional:** [Conecte-se comigo no LinkedIn](https://www.linkedin.com/in/nickolas-felipe-23447a2a2)[cite: 2]

---

## 📝 Documentação de Implantação (Relatório Final)

### 1. Planejamento da Implantação
O planejamento estratégico foi desenhado para garantir que a transição do ambiente local para a nuvem ocorresse de forma segura e organizada[cite: 3].
* **Plano de Implantação Detalhado:** Dividido em quatro fases essenciais: Auditoria de Código e Links[cite: 2, 3]; Estruturação do Versionamento Git[cite: 3]; Gestão de Acessos e 2FA[cite: 3]; e por fim, Testes de Homologação em Produção[cite: 3].
* **Configuração do Google GEMINI:** A inteligência artificial foi configurada desde o início como guia técnico (DevSecOps)[cite: 3]. O Gemini auxiliou gerando roteiros de comandos Git[cite: 3], revisando a integridade dos códigos HTML/CSS[cite: 3] e garantindo conformidade com padrões de governança[cite: 3].

### 2. Configuração Inicial e Integração com GitHub
A preparação da infraestrutura remota foi realizada seguindo as melhores convenções de Engenharia de Software[cite: 3]:
* **Ambiente GitHub Dedicado:** Inicialização local via `git init` e mapeamento remoto para o repositório público `portfolioHUB`[cite: 2, 3]. A branch padrão de produção foi definida como `main`[cite: 3].
* **Blindagem de Arquivos:** Uso estratégico do arquivo `.gitignore` para bloquear metadados de IDEs (como `.vscode/`) e arquivos residuais do sistema[cite: 3].
* **Hospedagem Automatizada:** Ativação do *GitHub Pages* atrelado à branch `main`[cite: 2, 3], estabelecendo um fluxo onde qualquer commit aceito atualiza o site automaticamente em ambiente real[cite: 3].

### 3. Gestão de Usuários e Segurança
Controles rígidos de acesso foram implantados para garantir a blindagem e a confiabilidade do código público[cite: 3]:
* **Gestão de Usuários:** Conta administrativa protegida por Autenticação de Dois Fatores (2FA)[cite: 3]. Regras de proteção de branch foram configuradas para exigir que qualquer alteração passe obrigatoriamente por revisão manual[cite: 3].
* **Políticas com Apoio do Gemini:** Sob orientação da IA[cite: 3], validou-se a ausência completa de chaves de API ou dados sensíveis expostos no código[cite: 3]. Ativou-se o *GitHub Dependabot* para varreduras automáticas de vulnerabilidades[cite: 3] e aplicou-se o atributo de segurança `rel="noopener noreferrer"` em todos os links externos que abrem em novas abas[cite: 3].

### 4. Compartilhamento e Controle de Acesso com GitHub
A arquitetura pública do repositório foi projetada para fomentar a colaboração da comunidade acadêmica de forma estruturada[cite: 3]:
* **Versionamento e Rastreabilidade:** Cada incremento foi isolado em commits semânticos, permitindo auditoria histórica e reversão rápida de código (*rollback*) caso necessário[cite: 3].
* **Fluxo de Trabalho Colaborativo (Workflow):** Desenvolvedores externos interagem com o projeto de forma segura através do modelo de *Fork*, criação de branches dedicadas (`git checkout -b feature/Nome-Da-Melhoria`) e abertura de *Pull Requests*[cite: 3]. O canal de *Issues* também foi documentado para centralizar relatos de bugs e novas ideias[cite: 3].

### 5. Finalização da Integração e Testes
O encerramento do ciclo de desenvolvimento consistiu em validar a qualidade da plataforma em produção[cite: 3]:
* **Ajustes Finais com o Gemini:** A IA auxiliou na correção de rotas locais de ativos (evitando erros HTTP 404) e na aplicação de CSS para compatibilidade cross-browser (Chrome, Safari, Firefox e Edge)[cite: 3].
* **Homologação:** Testes de responsividade foram realizados para garantir um design fluido em celulares e desktops[cite: 3], além da checagem manual do funcionamento dos links do LinkedIn e YouTube[cite: 2, 3].

### 6. Revisão Final e Apresentação
* **Apresentação em Vídeo:** Gravação de um vídeo técnico publicado no YouTube demonstrando o código, os desafios superados e a arquitetura visual da plataforma[cite: 3].
* **Desafios e Soluções:** O maior obstáculo foi dominar os fluxos de versionamento e segurança em servidores públicos logo no início da graduação[cite: 3]. A parceria contínua com a IA Gemini encurtou a curva de aprendizado, atuando como um mentor sob demanda altamente eficiente[cite: 3].

---
_Projeto desenvolvido por Nickolas Felipe para fins educacionais e de construção de portfólio profissional._[cite: 2, 3]
