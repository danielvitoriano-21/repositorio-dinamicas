# Especificação de Metadados do Repositório de Dinâmicas

Este documento define o padrão de metadados adotado no repositório
de dinâmicas reutilizáveis, inspirado na Reusable Asset Specification (RAS)
da OMG.

## Estrutura Geral

Cada dinâmica deve possuir um arquivo `metadata.yaml`
na sua respectiva pasta.

## Campos Obrigatórios

### Identificação
- id: Identificador único da dinâmica (ex: DS-001)
- titulo: Nome da dinâmica
- tipo: Soft Skill ou Hard Skill
- versao: Versão do ativo
- autor: Criador do ativo
- data_criacao: Data de criação

### Classificação
- categoria
- area_conhecimento
- palavras_chave

### Descrição
- descricao_resumida
- objetivos

### Contexto de Uso
- publico_alvo
- tempo_execucao_minutos
- tamanho_grupo_min
- tamanho_grupo_max
- nivel_complexidade
- contexto_aplicacao

### Recursos
- materiais_necessarios

### Governança
- licenca
- status (rascunho, validado, arquivado)

## Organização do Repositório

repositorio-dinamicas/
├── softskills/
└── hardskills/

Cada dinâmica deve estar dentro de uma pasta própria contendo:

- dinamica.md (descrição textual completa)
- metadata.yaml (metadados estruturados)
