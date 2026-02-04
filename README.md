# Estudos-e-carreira
DOSSIÊ: Planejamento de Carreira & Roteiro Acadêmico

Curso: Análise e Desenvolvimento de Sistemas (Foco em Web/Full Stack) Status: 1º Semestre (Fundação)
PARTE 1: A Linha do Tempo (Roteiro da Faculdade)
🔹 1º SEMESTRE — BASE + VISÃO DE CARREIRA (Fundação Absoluta)

Onde você está agora. Foco: Lógica e Ferramentas Básicas.

    Disciplinas Chave: Lógica de Programação, Arquitetura de Computadores, Segurança em TI.

    Conexão Prática:

        Python (Foco total em lógica).

        Git + GitHub (Versionamento).

        Terminal (Windows + WSL - perder o medo da tela preta).

    Metas de Entrega:

        3 Repositórios no GitHub.

        1 Mini sistema em Python (Projeto PyStock).

        Perfil do GitHub organizado (README, Pinned Repos).

🔹 2º SEMESTRE — PRIMEIRO CONTATO COM WEB (Tornando-se "Empregável")

Começa a construção visual e conectividade.

    Disciplinas Chave: Eng. de Software, Redes, Intro ao Desenvolvimento Web.

    Conexão Prática:

        HTML + CSS + JavaScript (O trio fundamental).

        Noções de HTTP e Cliente/Servidor.

    Metas: Construir sites simples e entender o fluxo de um projeto de software.

  

🔹 3º SEMESTRE — DADOS + ESTRUTURA (Nível Técnico)

O back-end ganha força. Aqui você vira um estagiário competitivo.

    Disciplinas Chave: Banco de Dados, Estrutura de Dados.

    Conexão Prática:

        SQL (Essencial).

        CRUD completo (Create, Read, Update, Delete).

        Integração Código + Banco de Dados.
        
       Status: Início da busca por vagas de estágio.
        
🔹 4º SEMESTRE — PERFIL DE DESENVOLVEDOR (Mentalidade Profissional)

Refinamento técnico e arquitetura.

    Disciplinas Chave: POO (Programação Orientada a Objetos), Sistemas Distribuídos, IA.

    Conexão Prática:

        APIs REST.

        Clean Code e organização.

        Destaque dentro do estágio.

🔹 5º SEMESTRE — PROFISSIONALIZAÇÃO (Rumo ao Júnior)

Consolidação e Projetos Reais.

    Disciplinas Chave: Mobile, Web Avançado, Gerência de Projetos, UX/UI.

    Meta Final: Efetivação no mercado e construção de aplicações completas.

PARTE 2: Análise Estratégica (Blindagem do Plano)

Para garantir que o plano acima funcione, adicione estes três pilares invisíveis:

    Inglês Técnico (Desde já): Não espere o fim do curso. Aprenda a ler documentação em inglês no 1º e 2º semestres para aumentar seu teto salarial futuro.

    Networking Intencional: Não seja um "aluno fantasma". Participe de hackathons e adicione professores/colegas no LinkedIn. O estágio muitas vezes vem por indicação.

    Cuidado com a "Curva da Desistência" (Transição 1º > 2º Semestre): Se a lógica de programação estiver difícil, não avance para Frameworks (React, etc) antes de entender a base. A lógica sólida é o que sustenta a carreira.

PARTE 3: Projeto Prático do 1º Semestre
📦 Projeto: "PyStock - Gerenciador de Estoque CLI"

Objetivo: Provar domínio de lógica, manipulação de dados em memória e organização de código.
1. O Cenário

Uma pequena loja precisa controlar produtos via terminal (sem interface gráfica), permitindo cadastrar itens, ver o total financeiro do estoque e realizar vendas.
2. Funcionalidades (Escopo)

O sistema deve rodar em loop (Menu Principal) com as opções:

    Cadastrar Produto: Entrada de Nome, Preço e Quantidade.

        Regra: Não permitir duplicidade de nomes.

    Listar Produtos: Exibir tabela com os itens e mostrar o Valor Total do Estoque (Soma de Preço * Qtd).

    Vender Produto: O usuário digita o nome e a quantidade.

        Regra: O sistema subtrai do estoque. Se estoque < pedido, exibir erro "Estoque insuficiente".

    Buscar Produto: Exibir detalhes de um item específico.

    Sair.

3. Requisitos Técnicos (O que o mercado avalia)

    Modularização: Código dividido em funções (def cadastrar(), def menu()).

    Estrutura de Dados: Uso de Lista de Dicionários.

        Ex: [{ "nome": "Mouse", "preco": 50.0, "qtd": 10 }]

    Tratamento de Erros: Uso de try/except para evitar que o programa feche se o usuário digitar letras no lugar de números.

    Diferencial (Bônus): Persistência de dados. Salvar o estoque em um arquivo .txt para que os dados não sumam ao fechar o programa.

4. Estrutura de Pastas (Git)
Plaintext

/PyStock
│── main.py          # Código fonte
│── dados.txt        # Banco de dados simples
│── .gitignore       # Arquivo de configuração Git
└── README.md        # Documentação profissional do projeto

Documento gerado em parceria com seu Assistente IA - Fev/2026
