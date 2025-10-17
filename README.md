# ES-2025-Grupo Augusto/Kauan Cervejaria-BS
Atividade Engenharia de Software

1.1 Propósito

Este projeto tem como objetivo desenvolver um sistema de controle de produção e vendas para a Cervejaria BeboSim.
O sistema visa otimizar processos internos, integrar operações de fábrica, controlar estoque, gerenciar campanhas publicitárias e aprimorar o acompanhamento das equipes de vendas e clientes.

1.2 Escopo do Projeto

O sistema abrangerá o cadastro e o gerenciamento de:
Produtos (cervejas, refrigerantes, águas);
Unidades de produção (fábricas);
Embalagens;
Equipes de vendas, vendedores e gerentes;
Clientes (pessoas jurídicas);
Pedidos de venda;
Campanhas publicitárias.
Também controlará o relacionamento entre essas entidades (como produção por fábrica, histórico de funcionários, pedidos e campanhas ativas).

1.3 Definições, Acrônimos e Abreviações

GCS / Gerenciamento de Configuração de Software
IEEE / Institute of Electrical and Electronics Engineers
PO / Product Owner
SM / Scrum Master

2. Descrição Geral
2.1 Perspectiva do Produto
O sistema será uma aplicação web responsiva, acessível via navegador em computadores e dispositivos móveis, substituindo controles manuais e planilhas.

2.2 Funções do Produto

Principais funcionalidades:
Gestão de Produção: cadastro de produtos, fórmulas, unidades e controle de estoque.
Gestão de Vendas: cadastro de equipes, vendedores e clientes, emissão de pedidos e cálculo de comissões.
Gestão de Campanhas: registro de campanhas publicitárias, controle de preços promocionais e análise de retorno.
Relatórios Gerenciais: vendas, produção, desempenho e campanhas.

2.3 Tipos de Usuário

Gerente-Geral, Acessa todos os módulos do sistema, com foco em relatórios e indicadores de desempenho.
Gerente de Produção, Gerencia o cadastro de produtos, fórmulas e unidades de produção.
Gerente de Vendas, Gerencia equipes de vendas, vendedores e acompanha o desempenho das vendas.
Vendedor, Cadastra clientes e emite pedidos de venda.

2.4 Restrições

Sistema web responsivo;
Controle de acesso por nível de permissão;

3. Requisitos Funcionais e Não Funcionais
3.1 Requisitos Funcionais

Cadastrar produtos (nome, estoque, preço, comissão, fórmula).
Registrar fábricas (nome, CNPJ, endereço, área e telefone).
Controlar embalagens (nome, material, custo, volume).
Gerenciar equipes de vendas e histórico de gerência.
Cadastrar vendedores e gerentes com dados pessoais e históricos.
Registrar clientes (razão social, CNPJ, contato).
Emitir e armazenar pedidos de venda com múltiplos produtos.
Controlar campanhas publicitárias (nome, duração, produtos, preços promocionais e retorno esperado).

3.2 Requisitos Não Funcionais

Interface intuitiva e responsiva;
Controle de versão via Git;
Integração contínua com testes automatizados;

4. Arquitetura do Sistema

A arquitetura será baseada em camadas (MVC), com:
Frontend: React ou Angular;
Backend: Java Spring Boot ou Node.js;
Banco de Dados: PostgreSQL ou MySQL;
Controle de Versão: Git + GitHub.

5. Gerenciamento de Configuração de Software (GCS)

Controle de Versão: Git e GitHub;
Modelo de Branch: GitFlow (main, develop, feature, release, hotfix);
Controle de Mudanças: Commits vinculados a issues e pull requests;
Integração Contínua (CI): GitHub Actions para testes e builds automáti

7. Autores

Augusto Altenhofen
Kauan Henrique Cichovicz

8. Licença
Este projeto é licenciado sob a Licença MIT.
