

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

Habilidades Adquiridas no Desenvolvimento do Projeto
O projeto prático solidificou o aprendizado e permitiu o desenvolvimento de habilidades mais específicas e aplicadas:

Engenharia e Orquestração de Agentes de IA: Capacidade de projetar, implementar e coordenar múltiplos agentes de IA (Buscador, Educador, Redator, Revisor), cada um com um papel definido em um fluxo de trabalho complexo. Isso demonstra a habilidade de quebrar um problema grande em tarefas menores e delegá-las a componentes inteligentes.

Engenharia de Prompt (Prompt Engineering): Domínio na criação de instruções precisas e eficazes para os modelos de IA, direcionando seu comportamento e garantindo que as respostas sejam relevantes e alinhadas aos objetivos do projeto.

Integração de Ferramentas e APIs: Experiência prática na integração de diferentes tecnologias, como a API do Google Gemini, a ferramenta de busca do Google (google_search), e bibliotecas de PLN como spaCy ou NLTK.

Desenvolvimento de Interface Gráfica (GUI): Habilidade em construir uma interface de usuário funcional utilizando Tkinter, permitindo que usuários não técnicos interajam de forma intuitiva com o sistema de agentes. Isso envolve a criação de elementos visuais e a lógica de interação.

Gerenciamento de Fluxos de Trabalho Automatizados: Criação de uma sequência lógica de operações, onde a saída de um agente serve como entrada para o próximo, resultando em um processo automatizado de geração de conteúdo.

Tratamento de Dados e Formatação: Capacidade de manipular e formatar dados textuais para diferentes propósitos, seja para entrada em modelos de IA, para exibição na interface ou para otimização de busca.

Resolução de Problemas e Depuração (Debugging): Demonstração da capacidade de identificar, analisar e corrigir erros comuns em desenvolvimento de IA (como ModuleNotFoundError, NameError, RuntimeError e RESOURCE_EXHAUSTED da API), e de adaptar o código para diferentes ambientes de execução.

Aplicação Prática da IA para Impacto Social: Habilidade de aplicar conhecimentos de inteligência artificial para resolver um problema do mundo real com relevância social, como a conscientização sobre fraudes e a proteção de populações vulneráveis.

Compreensão de Limitações da IA: Desenvolvimento de um entendimento prático sobre as limitações e desafios da IA em cenários reais, como a gestão de quotas de API, a necessidade de revisão humana e a confiabilidade das fontes de informação.

Essas habilidades combinadas mostram um perfil profissional apto a trabalhar com projetos de IA, desde a concepção até a implementação e depuração, com um forte foco em aplicações práticas e com potencial de impacto.
