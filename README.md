

https://github.com/user-attachments/assets/cf70ed9b-1725-44bb-881a-86e1d4f1392c

# Agente Educacional de IA para Conscientização sobre Fraudes

## Visão Geral

Este projeto implementa um sistema de agentes de IA desenvolvido para gerar conteúdo educativo sobre diversos tipos de fraudes. O sistema tem como objetivo aumentar a conscientização e fornecer dicas práticas para proteger indivíduos, especialmente grupos vulneráveis como idosos, de serem vítimas de golpes.

## Funcionalidades

O sistema utiliza uma abordagem multiagente, onde cada agente é especializado em uma tarefa específica:

1.  **Agente de Recuperação de Informações sobre Fraudes:** Este agente utiliza ferramentas de busca para coletar as informações mais recentes sobre tópicos específicos de fraude, incluindo golpes comuns, métodos utilizados por golpistas, estratégias de prevenção e notícias recentes sobre fraudes.
2.  **Agente de Planejamento de Conteúdo Educacional:** Este agente utiliza as informações coletadas pelo agente de recuperação para criar um plano detalhado de conteúdo educativo adequado para plataformas de mídia social. O plano inclui:
    * Tema central (por exemplo, "Golpes do Pix")
    * Tópicos específicos (por exemplo, "Como identificar e-mails de phishing")
    * Público-alvo (com ênfase na acessibilidade para idosos)
    * Tom de voz (claro, objetivo, informativo e empático)
    * Formatos de postagem sugeridos (por exemplo, threads no Twitter, posts no Facebook, infográficos no Instagram)
    * Chamadas para ação (por exemplo, "Compartilhe com seus amigos")
    * Ideias para recursos visuais (por exemplo, imagens, vídeos)
3.  **Agente de Geração de Conteúdo para Mídias Sociais:** Este agente gera o conteúdo textual real para as postagens em mídias sociais com base no plano educacional, adaptando o estilo e o formato para cada plataforma (Twitter, Facebook, Instagram, etc.).
4.  **Agente de Revisão de Conteúdo:** Este agente revisa o conteúdo gerado quanto à precisão, clareza, concisão, engajamento, adequação à plataforma, tom de voz e eficácia na educação sobre prevenção de fraudes.

## Tópicos Abordados

O sistema pode gerar conteúdo sobre uma ampla gama de tópicos relacionados a fraudes, incluindo, mas não se limitando a:

* Como identificar um golpe
* Os sinais de alerta de uma fraude
* Dicas práticas para se proteger
* O que fazer se você for vítima de um golpe
* Exemplos de casos reais de fraudes

## Público-Alvo

O público-alvo é o público em geral, com um forte foco em tornar o conteúdo acessível e relevante para pessoas idosas, que muitas vezes são desproporcionalmente afetadas por fraudes.

## Tecnologias Utilizadas

* (Liste as bibliotecas e tecnologias específicas que você utilizou, por exemplo:)
    * Python
    * `google-adk` (ou o kit de desenvolvimento de agentes específico)
    * `google.genai` (ou a API LLM que você usou)
    * (Quaisquer outras bibliotecas relevantes)

## Configuração e Instalação

1.  **Pré-requisitos:**
    * Python 3.x
    * (Quaisquer requisitos de sistema específicos)
2.  **Instalação:**
    * Clone o repositório: `git clone <URL_do_repositório>`
    * Instale as bibliotecas necessárias: `pip install -r requirements.txt` (Se você tiver um arquivo `requirements.txt`)
    * Configure as chaves de API ou credenciais (Forneça instruções específicas sobre como configurar as chaves de API necessárias, variáveis de ambiente, etc.)
3.  **Uso:**
    * Execute o script principal: `python main.py` (ou o comando apropriado para executar seu código)
    * Siga as instruções para inserir o tópico de fraude desejado.
    * O sistema irá gerar o conteúdo educativo.
